# Local AI and privacy

Kodo is designed so that AI-assisted coding can happen without uploading source code to a cloud AI provider.

## What stays on the device

- prompts sent to Kodo's local model
- source code processed by the local model
- generated responses and proposed edits handled by the app
- downloaded model files, unless the user removes them

Kodo uses Qwen models through `llama.cpp` for local inference. The operating system may reclaim memory or limit performance under pressure, so model speed and capacity vary by device.

## When Kodo uses the network

Network access is expected when you explicitly use a network feature:

- downloading an AI model
- cloning, pulling from or pushing to GitHub
- opening an SSH, SFTP or FTP connection
- loading remote content requested by a project or preview

Those services have their own privacy policies and security properties. Kodo cannot make a third-party server or repository private; users remain responsible for the endpoints and credentials they choose.

## Credentials

Server credentials are stored in Apple Keychain. Prefer key-based SSH authentication, a dedicated non-root user and least-privilege access. Never post credentials or connection details in public GitHub issues.

## App privacy information

Apple currently lists Kodo as collecting no data. See the [App Store listing](https://apps.apple.com/app/id6781042920) and [official privacy policy](https://www.ttstudio.net/en/privacy.html?app=kodo) for the current disclosures.
