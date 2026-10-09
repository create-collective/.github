# Contributing to Create Collective

Thanks for helping keep the Naya Create working. This guide covers every repository in the
organization that doesn't have a CONTRIBUTING file of its own. Where a repository's README lists
build steps or checks, those apply too.

## Ways to help

- **Report a bug.** Open an issue in the project's repository. Say which version of the project
  you run, your OS and its version, both halves' firmware versions and your module firmware, what
  you did, what you expected and what happened. Attach the log if the project writes one; each
  README says where it lives. In OpenFlow, **More → Bug Report** in the top bar does this for you.
- **Settle an open question.** The knowledge base lists what we don't know yet and what would
  settle it. Many need only a board on a firmware version we haven't seen, or another OS, and a
  read-only check.
- **Fix or improve the docs.** Corrections to the knowledge base are welcome as issues or pull
  requests. Give the firmware versions, host OS and date behind your observation.
- **Write code.** Look for open issues, or open one describing what you'd like to change.

## Before you open a pull request

- For anything bigger than a small fix, open an issue first so we can agree on the approach before
  you spend time on it.
- Keep each pull request to one change.
- Run the project's checks. Each README lists them, for example `cargo test` and
  `cargo clippy --all-targets` for Create Companion.
- Say what you changed and how you tested it, and whether that was on hardware.

## Working with hardware

- **Redact identifiers.** Never post serial numbers, Bluetooth addresses or UUIDs from your board,
  in issues, logs or captures.
- **Don't attach vendor files.** Refer to Naya's firmware images and installers by version and
  hash instead of uploading them;
  [create-legacy-firmware](https://github.com/create-collective/create-legacy-firmware) has the
  catalogue.
- **Keep the safety checks.** If a change writes to a keyboard (flashing, settings, pairing), say
  which boards and firmware versions you tested it on. A change that weakens hash verification or
  skips a confirmation won't be merged.

## What we won't accept

- Ways to extract keys from a keyboard or to bypass its protections.
- Decompiled vendor code. Names, offsets and behavior are fine; function bodies are not.
- Material you don't have the right to share.

## Licensing

By contributing, you agree that your contribution is licensed under the license of the repository
you contribute to (MIT, Apache-2.0 or CC BY 4.0; see its LICENSE file).

## Conduct

Everyone taking part follows our [Code of Conduct](CODE_OF_CONDUCT.md).
