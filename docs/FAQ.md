# Frequently asked questions

## Is Kodo open source?

No. This repository is public for documentation, support and issue tracking. The Kodo application source code is proprietary.

## Does Kodo send my source code to a cloud AI?

Kodo's AI runs on the device using a downloaded Qwen model through `llama.cpp`. Prompts and source code processed by that model are not sent to a Kodo cloud AI service.

Network access is still required for actions such as downloading a model, using GitHub or connecting to a server you choose.

## Does local AI work offline?

Yes, after a compatible model has been downloaded. The available model size and performance depend on device memory, storage and thermal conditions.

## Can Kodo run Python, PHP or Swift locally?

No. Kodo does not bundle general-purpose local runtimes or compilers for Python, PHP, Swift and similar stacks.

Kodo can preview HTML and Markdown locally. For other runtimes, use SSH and remote files with a machine or server that has the required tools installed.

## Is Kodo a full replacement for Xcode or a desktop IDE?

No. Kodo is designed as a focused mobile workspace for editing, local AI assistance, lightweight data work and remote development. Native app builds, complex toolchains and demanding runtimes still belong on an appropriate Mac, PC or server.

## Does Kodo require an account or subscription?

Kodo currently requires no Kodo account and is available without a subscription. Refer to the App Store for the current price and availability in your region.

## Where are server credentials stored?

Kodo stores server credentials in Apple Keychain. You should still use a dedicated non-root account, least-privilege permissions and key-based authentication when your server supports it.

## Which files and languages can I edit?

Kodo includes more than 150 syntax profiles, including common web, scripting, systems, mobile, configuration and data formats. Syntax support means editing and highlighting; it does not imply that a language runtime is bundled locally.

## Where should I report a bug?

Use the [bug report form](https://github.com/TiberiusTech/kodo-editor/issues/new?template=bug_report.yml) for public, reproducible problems. Use [private support](../SUPPORT.md) when a report requires confidential details. Security vulnerabilities must follow [SECURITY.md](../SECURITY.md).
