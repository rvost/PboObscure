# PboObscure

The project aims to provide the DayZ modding community with a free and open source obfuscation tool.

## Project State

**The project is at a very early stage of development.**

The v0.1.0 [release](https://github.com/rvost/PboObscure/releases/tag/0.1.0) is based on [@FlipperPlz](https://github.com/FlipperPlz) `FPacker` with some modifications that make it *suitable for practical use*.
Unfortunately, the code for this version is not yet available, as it is mostly made up of decompiled sources.
The source code will gradually become available as I rewrite and/or refactor existing code to a quality that I'm ready to share.

As with the original `FPacker`, the current version is a prototype that provides protection against opening PBOs with some popular tools such as [PboManager](https://github.com/winseros/pboman3) or [PboSpy](https://github.com/rvost/PboSpy), but fails to protect against a determined attacker.

⚠ **Obfuscation is not encryption!**
Secrets (such as Discord API keys) should never be placed in client-side PBOs.