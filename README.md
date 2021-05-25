# SharpFontStandard.Runtimes

Runtime dependencies for SharpFontStandard. That is, the [FreeType](https://www.freetype.org/) binaries structured in accordance with the [package structure rules for architecture-specific (specifically, native) binaries](https://docs.microsoft.com/en-us/nuget/create-packages/supporting-multiple-target-frameworks#architecture-specific-folders).

* `SharpFontStandard.Runtimes.WindowsOnly` [![NuGet version (SharpFontStandard.Runtimes.WindowsOnly)](https://img.shields.io/nuget/v/SharpFontStandard.Runtimes.WindowsOnly.svg?style=flat-square)](https://www.nuget.org/packages/SharpFontStandard.Runtimes.WindowsOnly/): contains 32- and 64-bit Windows DLLs

## Usage

Just add the runtime package as a dependency along with SharpFontStandard. This will work for both applications and libraries.

## Credit

This package is just a distribution of the FreeType binaries in a helpful Nuget package. As such, obviously:

> Portions of this software are copyright ©2015 The FreeType Project (www.freetype.org).  All rights reserved.
