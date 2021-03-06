Scoop-Velgus [![Build status](https://ci.appveyor.com/api/projects/status/ckomgtl07nog4wws?svg=true)](https://ci.appveyor.com/project/Velgus/scoop-velgus)
===

A [Scoop](https://scoop.netlify.com/ "Scoop") bucket with a few applications.

Installation
------------

`scoop bucket add Velgus https://github.com/Velgus/scoop-Velgus.git`

Manifests
---------

| App                                                                                      | Scoop Name            | Description                                                                                                                                                                                                                                           |
|------------------------------------------------------------------------------------------|-----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [7-Zip Codecs](https://github.com/mcmilk/7-Zip-zstd/ "7-Zip Codecs")                     | `7zip-codecs`         | Additional codecs for the mainline version of 7-Zip. Does nothing with the ZS version of 7-Zip.                                                                                                                                                       |
| [7-Zip ZS](https://github.com/mcmilk/7-Zip-zstd/ "7-Zip ZS")                             | `7zip-zs`             | A multi-format file archiver with high compression ratios, with support of additional Codecs.                                                                                                                                                         |
| [Bitwarden](https://bitwarden.com/ "Bitwarden")                                          | `bitwarden-portable`  | Password management solutions for individuals, teams, and business organizations. The versions in the `extras` bucket will install itself to the system whenever there is an auto-update - this manifest installs the portable version to avoid this. |
| [Brogue CE](https://github.com/tmewett/BrogueCE "Brogue CE")                             | `brogue-ce`           | A single-player strategy game set in the halls of a mysterious and randomly-generated dungeon.                                                                                                                                                        |
| [Device Cleanup Tool](https://www.uwe-sieber.de/misc_tools_e.html "Device Cleanup Tool") | `device-cleanup-tool` | A tool to remove non-present devices from the Windows Device Management.                                                                                                                                                                              |
| [Flawless Widescreen](https://www.flawlesswidescreen.org "Flawless Widescreen")          | `flawless-widescreen` | A tool for crafting fixes and patches to get games functioning correctly in UltraWide/Surround/Eyefinity gaming resolutions.                                                                                                                          |
| [OpenSSH ZS](https://www.openssh.com/ "OpenSSH")                                         | `openssh-zs`          | A suite of secure networking utilities based on the Secure Shell protocol. Requires a Zstandard-compatible archive manager to install.                                                                                                                |
| [ZenTimings](https://zentimings.protonrom.com/ "ZenTimings")                             | `zentimings`          | A free, simple and lightweight app for monitoring memory timings on Ryzen platform.                                                                                                                                                                   |

Moved To Known Bucket
---------------------
| App                                                                                                     | Scoop Name           | Bucket                                                         | Pull Request                                                           |
|---------------------------------------------------------------------------------------------------------|----------------------|----------------------------------------------------------------|------------------------------------------------------------------------|
| [Color Sustainer](https://www.guru3d.com/files-details/color-sustainer-download.html "Color Sustainer") | `color-sustainer`    | [extras](https://github.com/lukesampson/scoop-extras "extras") | [#2712](https://github.com/lukesampson/scoop-extras/pull/2712 "#2712") |
| [CPKeeper](http://goebish.free.fr/cpk "CPKeeper")                                                       | `cpkeeper`           | [extras](https://github.com/lukesampson/scoop-extras "extras") | [#2712](https://github.com/lukesampson/scoop-extras/pull/2712 "#2712") |
| [Fork](https://git-fork.com "Fork")                                                                     | `fork`               | [extras](https://github.com/lukesampson/scoop-extras "extras") | [#2520](https://github.com/lukesampson/scoop-extras/pull/2520 "#2520") |
| [PDF-XChange Editor](https://www.tracker-software.com/product/pdf-xchange-editor "PDF-XChange Editor")  | `pdf-xchange-editor` | [extras](https://github.com/lukesampson/scoop-extras "extras") | [#2747](https://github.com/lukesampson/scoop-extras/pull/2747 "#2747") |
| [PeaZip](https://www.peazip.org "PeaZip")                                                               | `peazip`             | [extras](https://github.com/lukesampson/scoop-extras "extras") | [#2599](https://github.com/lukesampson/scoop-extras/pull/2599 "#2599") |
