# Third-party notices

## .NET and WPF

Copyright Microsoft Corporation and contributors.

Licensed under the MIT License. Source and notices: https://github.com/dotnet/runtime and https://github.com/dotnet/wpf

## FFmpeg

This distribution includes an unmodified shared Windows build of FFmpeg produced by BtbN FFmpeg-Builds. The inspected build configuration is LGPL version 3 or later (`--enable-version3`) and does not enable GPL or nonfree mode. The executables and shared libraries remain separate third-party works and are invoked out-of-process.

Bundled build identification: `N-125708-gccc57378b3-20260721`. The public download release for Kadr must include the matching FFmpeg source archive and build information as separate assets. These FFmpeg sources are provided to satisfy the rights granted by GNU LGPL and are not the proprietary source code of Kadr.

FFmpeg source: https://ffmpeg.org/download.html  
Build project and corresponding source references: https://github.com/BtbN/FFmpeg-Builds  
License text shipped with the binaries: `tools/FFMPEG-LICENSE.txt`

Recipients may replace the files in `tools` with a compatible FFmpeg build. The application requires `ffmpeg.exe`, `ffprobe.exe`, and their shared DLL dependencies.

## OpenH264

The selected FFmpeg build enables Cisco OpenH264. OpenH264 source is BSD-2-Clause. Cisco's binary distribution and patent-license terms may apply depending on how binaries are obtained and redistributed.

Source and license: https://github.com/cisco/openh264

## Inno Setup

Inno Setup is supported by the optional `installer/Kadr.iss` script and is not required by the default build. It is not embedded as a runtime library. It is distributed under the Inno Setup License.

License: https://jrsoftware.org/files/is/license.txt

## Pillow

Pillow is used only by `scripts/generate-icon.py` during asset development; it is not included in the application or installer. Pillow is distributed under the HPND License.

Source and license: https://github.com/python-pillow/Pillow

