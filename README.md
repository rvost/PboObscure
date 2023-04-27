# PboObscure

The project aims to provide the DayZ modding community with a free and open source obfuscation tool.

## Project State

**❗ The project is at a very early stage of development.**

The v0.1.0 [release](https://github.com/rvost/PboObscure/releases/tag/0.1.0) is based on [@FlipperPlz](https://github.com/FlipperPlz) `FPacker` with some modifications that make it *suitable for practical use*.
Unfortunately, the code for this version is not yet available, as it is mostly made up of decompiled sources.
The source code will gradually become available as I rewrite and/or refactor existing code to a quality that I'm ready to share.

As with the original `FPacker`, the current version is a prototype that provides protection against opening PBOs with some popular tools such as ExtractPbo, PboManager or PboSpy, but fails to protect against a determined attacker.

## ⚠ Disclaimer

* **Obfuscation is not encryption!**
  This *can help prevent intellectual property theft*, but **should not be considered as protection for sensitive data**.
  
  **Secrets (e.g. Discord API keys) should never be placed in client-side** PBOs. Instead, consider using server-side mod for such scenarios.

  The project aims to provide protection against opening PBOs with some popular tools such as:
   * built-in `BankRev`;
   * Mikero's `ExtractPbo`;
   * [PboManager](https://github.com/winseros/pboman3)
   * [PboSpy](https://github.com/rvost/PboSpy)
   
   **There is no guarantee of protection against a determined attacker.**
  
* **Using such a tool to build mods doesn't exempt you from complying with the [BI's Tools EULA](https://community.bistudio.com/wiki/End_User_License_Agreement_for_BI%27s_Tools)**.
  In fact, the current version uses `CfgConvert` from DayZ Tools to binarize configurations, so your usage must be in accordance with the license.

## Usage

You can get [latest](https://github.com/rvost/PboObscure/releases/latest) version on [Releases page](https://github.com/rvost/PboObscure/releases).
Actual executable can be downloaded from the *Assets* section. 

Since the project is at a very early stage of development, the user interface can vary significantly between releases.
Please refer to the release notes for more release specific usage information.

## Issues

If you find a bug or have a feature request, please use [Issues](https://github.com/rvost/PboObscure/issues) to report it. 
Please use the appropriate template for your issue.
