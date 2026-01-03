Thanks for your interest in contributing to AerynOS.

# Table of Contents

- [Getting Help](#getting-help)
  - [Documentation](#documentation)
  - [Chat](#chat)
- [Ways to Contribute Beyond Code](#ways-to-contribute-beyond-code)
- [Reporting Issues](#reporting-issues)
- [Submitting Code](#submitting-code)
  - [Coding Style](#coding-style)
  - [Submitting PRs](#submitting-prs)

# Getting Help

## Documentation

- [aerynos.dev](https://aerynos.dev/) - Documentation about the ideas behind the OS, the packaging process, and other core concepts.

## Chat

All discussion takes place in the [AerynOS Zulip organization](https://aerynos.zulipchat.com/).

- [General Zulip channel](https://aerynos.zulipchat.com/#narrow/channel/543066-General/topic//with/565983725)
- [Development Zulip channel](https://aerynos.zulipchat.com/#narrow/channel/543142-Development/topic//with/565911053)
- [Documentation Zulip channel](https://aerynos.zulipchat.com/#narrow/channel/543227-Documentation/topic//with/566079322)
- [Webdev Zulip channel](https://aerynos.zulipchat.com/#narrow/channel/543225-Web-Development)
- [Packaging Zulip channel](https://aerynos.zulipchat.com/#narrow/channel/543228-Packaging/topic//with/566120303)

# Ways to Contribute Beyond Code
Contributions are not limited to code. We welcome help with documentation, translations, testing, user feedback, design, and community support. If you’re unsure where to start, ask in the General Zulip channel.

# Reporting Issues

If you find any bugs, inconsistencies or other problems, feel free to submit
a GitHub issue on the appropriate repository.
If you’re unsure which repository is appropriate, ask in the General Zulip channel or open the issue where it seems most relevant — we can move it if needed.

If you run into problems getting started, let us know — improving the contributor experience is important to us. Please search for existing issues before opening a new one.

# Submitting Code

Ready to contribute code? The following guidelines should help you get started.

## Coding Style

Follow the existing coding style and patterns used in the repository.

We use [rustfmt] to ensure consistent code formatting and [clippy]
to catch common mistakes not caught by the compiler
as well as enforcing a few custom code style choices.

Before committing your changes, run `cargo fmt` to format the code
(if your editor / IDE isn't set up to run it automatically),
and `cargo clippy --workspace` to run lints.

Sometimes, you may see lints that are unrelated to the code you modified.
You can ignore those, or try to fix them as a separate contribution.

[rustfmt]: https://github.com/rust-lang/rustfmt#readme
[clippy]: https://github.com/rust-lang/rust-clippy#readme

## Submitting PRs

Once you're ready to submit your code, create a pull request,
and one of our maintainers will review it.
Reviews may take some time depending on maintainer availability.
Once your PR has passed review, a maintainer will merge it and you're done! 🎉
