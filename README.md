# voiceink-build

Builds the official open-source [VoiceInk](https://github.com/Beingpax/VoiceInk) (GPL-3.0) v2.20 from source
on a GitHub-hosted `macos-26` runner using the upstream `make local` target (ad-hoc signed, Apple Silicon).

- Upstream commit and whisper.cpp commit are pinned in `.github/workflows/build.yml`.
- Manual trigger only (`workflow_dispatch`); the zipped app is uploaded as a workflow artifact.
- Not affiliated with VoiceInk. If you use VoiceInk, consider supporting the author: https://tryvoiceink.com
