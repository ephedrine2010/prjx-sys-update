# POS_X — Releases

Built release artifacts for the **POS_X** Windows desktop application, published
by [Velopack](https://velopack.io).

This repository contains **no source code**. It exists only to host the compiled
installer and update packages as GitHub Release attachments. Nothing is committed
to the repository tree itself — every artifact lives on a
[Release](../../releases).

## For end users

**Please don't download files from this page.**

You get the POS_X installer directly from us. Once installed, the application
checks for and applies its own updates automatically — there is nothing here for
you to download or run manually.

## For support staff

The latest installer is always the `Setup.exe` asset attached to the release
marked **Latest** on the [Releases page](../../releases/latest).

Direct link to the current installer:

```
https://github.com/ephedrine2010/prjx-sys-update/releases/latest/download/pos_x-stable-Setup.exe
```

Only hand this to a customer when a normal install or self-update has failed and
you've been asked to reinstall.

Releases are published on the `stable` channel; the update feed the application
reads is `releases.stable.json`, attached to the same release.
