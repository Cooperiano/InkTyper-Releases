<p align="center">
  <img src="assets/inktyper-icon.png" width="112" alt="InkTyper app icon">
</p>

<h1 align="center">InkTyper Releases</h1>

<p align="center">
  Voice to text from your desktop — with a global shortcut, tray controls, and optional AI editing.
</p>

<p align="center">
  <a href="https://inktyper.ledgendaryanimal.top/">Website</a> ·
  <a href="https://github.com/Cooperiano/InkTyper-Releases/releases/latest">Latest release</a> ·
  <a href="https://inktyper.ledgendaryanimal.top/privacy/">Privacy</a>
</p>

This public repository is the official release index and binary mirror for InkTyper. It contains installers, checksums, release notes, and user-facing documentation. Product source code and internal infrastructure are not published here.

中文：这是 InkTyper 的官方公开发布仓库，用于提供安装包、SHA-256 校验值、版本说明和用户文档；不包含产品源码与内部基础设施配置。

## Linux download

InkTyper 2.0.17 is available for x86_64 Linux:

- Debian / Ubuntu: `InkTyper-2.0.17-Linux-amd64.deb`
- Other desktop distributions: `InkTyper-2.0.17-Linux-x86_64.AppImage`

Download both files from the [v2.0.17 release](https://github.com/Cooperiano/InkTyper-Releases/releases/tag/v2.0.17).

### Install the Debian package

```bash
sudo apt install ./InkTyper-2.0.17-Linux-amd64.deb
```

### Run the AppImage

```bash
chmod +x InkTyper-2.0.17-Linux-x86_64.AppImage
./InkTyper-2.0.17-Linux-x86_64.AppImage
```

InkTyper uses X11/XWayland on Linux so global shortcuts and text insertion work consistently across supported desktop environments.

## Verify the download

Compare the downloaded file with `SHA256SUMS` from the same release:

```bash
sha256sum -c SHA256SUMS
```

Expected v2.0.17 checksums:

```text
66f37cd107d61c2913193b7026a342e3a4223f4cb0dd0bd837c412bc9d5300f3  InkTyper-2.0.17-Linux-x86_64.AppImage
461bf2ad1daad4639aba9eb8ac8564a1bc20910a530104bfa9dc9587eb56f849  InkTyper-2.0.17-Linux-amd64.deb
```

## What is synchronized?

When you sign in, supported InkTyper clients can synchronize account-scoped preferences and History. History synchronization stores final text only, retains up to 30 days and 500 items, and propagates deletion. Raw transcription text is not returned by the History API. Guest History remains local to the device.

## Support and security

- For normal bugs or installation problems, [open an issue](https://github.com/Cooperiano/InkTyper-Releases/issues/new/choose).
- For security-sensitive reports, follow [SECURITY.md](SECURITY.md) and do not post secrets or personal data in a public issue.
- Read the official [privacy policy](https://inktyper.ledgendaryanimal.top/privacy/).

## License

[MIT](LICENSE).

The MIT license applies only to the original documentation and repository metadata in this repository. It does not apply to InkTyper application binaries, installers, release assets, logos, or unpublished product source code. Those items are not relicensed by this repository license. Third-party components retain their respective licenses.
