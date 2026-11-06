# BSS Commission

BSS Commission is a Windows app for commissioning Harman BSS Soundweb London
systems. It reads the design stored on your BLU, then lets you set levels,
watch meters, back up and restore settings, and locate devices on the
network.

## Supported products

- BSS Soundweb London BLU-50, BLU-100, BLU-101, and BLU-103 signal processors
- BSS EC-4BV and EC-8BV keypads

## Download

To get the latest version, go to the
[Releases page](https://github.com/Madison-AV/bss_commission-releases/releases/latest)
and download `BSS_Commission_<version>.zip`. The zip contains the installer
and the release notes for that version.

## Install

To install BSS Commission, do the following:

1. Extract the zip.
1. Run `bss_commission_setup_<version>.exe`.
1. Accept the licence, and then choose an install folder.
1. When Windows asks to add the firewall rule
   **BSS Commission (HiQnet UDP 3804)**, click **Yes**. The rule lets the
   app find your BLU devices and receive their meters.

The installer installs the app for the current user only, and adds
**BSS Commission** to the Start menu. If you skip the firewall prompt,
Windows asks again the first time you run the app.

To update, run the installer for the new version. You don't need to
uninstall the old one first.

## Documentation

To open the user guide, start BSS Commission and click **Help > Documentation**.

## Licence

BSS Commission is licensed under the Madison Software Licence. For the full
terms, see [LICENSE.txt](LICENSE.txt). The source code isn't public.

Copyright 2026 Madison Group Enterprises Pty Ltd.
