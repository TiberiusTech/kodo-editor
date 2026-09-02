# Kodo

[![Kodo — private AI code editor for iPhone and iPad](https://www.ttstudio.net/assets/kodo/kodo-og.png)](https://www.ttstudio.net/en/kodo.html)

**A code editor for iPhone and iPad, with on-device AI and SSH.**

[Download on the App Store](https://apps.apple.com/app/id6781042920) · [Product page](https://www.ttstudio.net/en/kodo.html) · [Information & resources](https://www.ttstudio.net/en/kodo-press.html) · [Changelog](https://www.ttstudio.net/en/kodo-changelog.html)

> This is Kodo's public documentation, support and issue-tracking repository. The Kodo application source code is proprietary and is not published here.

## Why Kodo

Kodo is built for developers who want useful coding tools on iPhone or iPad without sending source code to a cloud AI service. It combines a native editor, downloadable Qwen models running through `llama.cpp`, remote-development tools and practical offline utilities in one app.

| Capability | What Kodo provides |
| --- | --- |
| Private AI | On-device Qwen inference after a model is downloaded |
| AI editing | Inline autocomplete, chat and an agent workflow with diff review |
| Remote development | Interactive SSH terminal plus SFTP and FTP file access |
| GitHub workflows | Clone, update and push repositories from the app |
| Data tools | SQLite playground and CSV/TSV editing |
| Editor | 150+ syntax profiles, formatter support, Emmet and web preview |
| Privacy | No Kodo account, no cloud AI and no tracking |

## A practical iPad workflow

1. Open or create a local workspace.
2. Edit with syntax highlighting, snippets, formatting and optional on-device AI.
3. Review AI-generated changes before applying larger edits.
4. Preview HTML or Markdown locally.
5. Connect over SSH when the project needs a server, compiler or full runtime.

## Privacy model

- AI prompts and source code are processed on the device by the selected local model.
- Server credentials are stored in Apple Keychain.
- Network access is used only for actions that inherently require it, such as downloading a model, using GitHub or connecting to a remote server.
- Apple currently lists Kodo as collecting no data.

Read [how local AI and network access work](docs/AI-AND-PRIVACY.md).

## Important limits

Kodo is a mobile coding workspace, not a full local replacement for Xcode or a desktop IDE.

- It does not locally execute or compile Python, PHP, Swift or other general-purpose runtimes.
- HTML and Markdown can be previewed locally.
- A remote machine or server can provide the runtime, compiler and services for larger projects.
- Performance and available model sizes depend on the device's memory and storage.

See the [FAQ](docs/FAQ.md) and [remote-development guide](docs/REMOTE-DEVELOPMENT.md).

## Feedback and support

- Found a reproducible problem? [Open a bug report](https://github.com/TiberiusTech/kodo-editor/issues/new?template=bug_report.yml).
- Have a workflow improvement in mind? [Request a feature](https://github.com/TiberiusTech/kodo-editor/issues/new?template=feature_request.yml).
- Need private help? See [SUPPORT.md](SUPPORT.md).
- Found a security issue? Follow [SECURITY.md](SECURITY.md) and do not post it publicly.

Please never include passwords, private keys, access tokens, server addresses, private source code or confidential logs in a public issue.

## Repository scope

This repository contains public product documentation, release information and community templates. Documentation fixes and improvements are welcome. It does not contain the Kodo application source code, downloadable AI models or third-party runtime binaries.

© 2026 TT Studio. Kodo and its application code are proprietary software.
