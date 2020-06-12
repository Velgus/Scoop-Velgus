
scoop-Velgus
===

A Scoop bucket with a few applications.

Installation
--------

In PowerShell:
```
# Install Scoop
set-executionpolicy unrestricted -scope cu
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')

# Add Bucket
scoop bucket add Velgus https://github.com/Velgus/scoop-Velgus.git

# Install apps
scoop install <Scoop App Name>
```

Manifests
------------

| App                                                                                                             | Scoop Name                    | Description                                                                                          |
|-----------------------------------------------------------------------------------------------------------------|-------------------------------|------------------------------------------------------------------------------------------------------|
| [Color Sustainer](https://www.guru3d.com/files-details/color-sustainer-download.html "Color Sustainer")         | `color-sustainer`             | An ICC profile enforcer                                                                              |
| [CPKeeper](http://goebish.free.fr/cpk "CPKeeper")                                                               | `cpkeeper`                    | A tool to apply and lock ICC profile files                                                           |
| [Fork for Windows](https://git-fork.com/windows "Fork for Windows")                                             | `fork`                        | A fast and friendly git client for Mac and Windows                                                   |
| [PDF-XChange Editor Portable](https://www.tracker-software.com/product/pdf-xchange-editor "PDF-XChange Editor") | `pdf-xchange-editor-portable` | A small, fast, and feature-rich PDF viewer/editor                                                    |
| [PeaZip Portable](https://www.peazip.org/ "PeaZip Portable")                                                    | `peazip-portable`             | A free file archiver utility, based on Open Source technologies
| [wox-for-scoop](https://github.com/Velgus/wox-for-scoop "wox-for-scoop")                                        | `wox-for-scoop`               | Launcher for Windows, an alternative to Alfred and Launchy - build for improved usage with Scoop     |
| [wox-for-scoop-dev](https://github.com/Velgus/wox-for-scoop "wox-for-scoop")                                    | `wox-for-scoop-dev`           | Launcher for Windows, an alternative to Alfred and Launchy - dev build for improved usage with Scoop |
