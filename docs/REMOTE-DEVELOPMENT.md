# Remote development with Kodo

Kodo's remote tools are intended for workflows where editing happens on iPhone or iPad and execution happens on a machine with the required runtime.

## Typical setup

1. Prepare a Mac, PC, Linux machine or hosted server with the project runtime and an SSH service.
2. Create a dedicated non-root user with access only to the required project files.
3. Prefer SSH keys over passwords and protect the private key on the Apple device.
4. Connect from Kodo using SSH for terminal work and SFTP for remote files.
5. Run builds, tests, package managers and long-lived services on the remote machine.

## Good fits

- editing a website and deploying to a remote host
- maintaining a small server or Raspberry Pi
- running Python, Node.js, PHP, Rust or other toolchains remotely
- checking logs or applying a focused fix away from a desk
- using `vim`, `htop`, shells and command-line tools through the interactive terminal

## Security recommendations

- do not expose SSH directly without appropriate firewall and authentication controls
- disable remote root login
- use unique credentials and rotate compromised keys immediately
- restrict filesystem permissions to the required project paths
- verify host identity before trusting a new server
- keep the server and SSH implementation patched

Kodo provides the client tools; server hardening and backups remain the server owner's responsibility.
