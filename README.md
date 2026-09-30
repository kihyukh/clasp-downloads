# Clasp

A desktop workspace for academic papers and Markdown notes.

[Website](https://clasp-research.glossy-dove-7475.chatgpt.site/) · [Downloads](https://github.com/kihyukh/clasp-downloads/releases) · [Report an issue](https://github.com/kihyukh/clasp-downloads/issues)

Read PDFs beside your notes, highlight and cite passages, connect research ideas,
and collaborate in shared workspaces. Sign in inside the app to get started.

## Install

- **Mac:** Apple Silicon (M1 or newer), macOS 13 or later. The v1.1.1 download is
  awaiting Apple notarization; check the release notes for availability.
- **Windows:** Windows 10 or later, Intel/AMD x64. Run the `.exe` installer. The
  initial Windows release is unsigned, so Windows may show an unknown publisher
  warning. Installation is per-user; uninstalling preserves your workspace data.

Download installers and their SHA-256 checksum files from the same release.
On Windows, use `Get-FileHash <installer> -Algorithm SHA256`; on Mac, use
`shasum -a 256 <archive>` to compare the downloaded file with its checksum.

Your first sign-in and workspace download need an internet connection. Previously
cached workspaces and notes remain available offline. The Chrome connector
currently supports macOS; use **Add papers** in Clasp on Windows.

This repository contains official download assets and installation notes.
Application source is maintained separately. Please do not include private papers,
account details, or access tokens when reporting an issue.
