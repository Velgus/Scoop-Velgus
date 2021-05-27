Scoop-Velgus [![Build status](https://ci.appveyor.com/api/projects/status/ckomgtl07nog4wws?svg=true)](https://ci.appveyor.com/project/Velgus/scoop-velgus)
===

A [Scoop](https://scoop.netlify.com/ "Scoop") bucket with a few applications.

Installation
------------

`scoop bucket add Velgus https://github.com/Velgus/scoop-Velgus.git`

Manifests
---------

| App                                                                                      | Scoop Name            | Description                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|------------------------------------------------------------------------------------------|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Bitwarden](https://bitwarden.com/ "Bitwarden")                                          | `bitwarden-portable`  | Password management solutions for individuals, teams, and business organizations. Included here until the version in the `extras` bucket [is fixed](https://github.com/lukesampson/scoop-extras/pull/4844) to use the actual portable version, instead of the version that automatically installs to "Add or remove programs" whenever there is an auto-update, breaking multiple [scoop principles](https://github.com/lukesampson/scoop/wiki/So-What). |
| [Device Cleanup Tool](https://www.uwe-sieber.de/misc_tools_e.html "Device Cleanup Tool") | `device-cleanup-tool` | A tool to remove non-present devices from the Windows Device Management.                                                                                                                                                                                                                                                                                                                                                                                 |
| [Flawless Widescreen](https://www.flawlesswidescreen.org "Flawless Widescreen")          | `flawless-widescreen` | A tool for crafting fixes and patches to get games functioning correctly in UltraWide/Surround/Eyefinity gaming resolutions.                                                                                                                                                                                                                                                                                                                             |

Moved To Known Bucket
---------------------
| App                                                                                                     | Scoop Name           | Bucket                                                         | Pull Request                                                           |
|---------------------------------------------------------------------------------------------------------|----------------------|----------------------------------------------------------------|------------------------------------------------------------------------|
| [Color Sustainer](https://www.guru3d.com/files-details/color-sustainer-download.html "Color Sustainer") | `color-sustainer`    | [extras](https://github.com/lukesampson/scoop-extras "extras") | [#2712](https://github.com/lukesampson/scoop-extras/pull/2712 "#2712") |
| [CPKeeper](http://goebish.free.fr/cpk "CPKeeper")                                                       | `cpkeeper`           | [extras](https://github.com/lukesampson/scoop-extras "extras") | [#2712](https://github.com/lukesampson/scoop-extras/pull/2712 "#2712") |
| [Fork](https://git-fork.com "Fork")                                                                     | `fork`               | [extras](https://github.com/lukesampson/scoop-extras "extras") | [#2520](https://github.com/lukesampson/scoop-extras/pull/2520 "#2520") |
| [PDF-XChange Editor](https://www.tracker-software.com/product/pdf-xchange-editor "PDF-XChange Editor")  | `pdf-xchange-editor` | [extras](https://github.com/lukesampson/scoop-extras "extras") | [#2747](https://github.com/lukesampson/scoop-extras/pull/2747 "#2747") |
| [PeaZip](https://www.peazip.org "PeaZip")                                                               | `peazip`             | [extras](https://github.com/lukesampson/scoop-extras "extras") | [#2599](https://github.com/lukesampson/scoop-extras/pull/2599 "#2599") |
