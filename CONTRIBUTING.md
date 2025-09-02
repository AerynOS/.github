Welcome! Thanks for showing interest in contributing to our project!

# Table of Contents

- [Looking for Help?](#looking-for-help)
  - [Documentation](#documentation)
  - [Chat Rooms](#chat-rooms)
- [Reporting Issues](#reporting-issues)
- [Submitting Code](#submitting-code)
  - [Coding Style](#coding-style)
  - [Submitting PRs](#submitting-prs)

# Looking for Help?

Here is a list of helpful resources you can consult:

## Documentation

- [aerynos.dev](https://aerynos.dev/) - Documentation about the ideas behind the OS, the packaging process and some other things

## Chat Rooms

All of these are part of the [AerynOS Matrix space](https://matrix.to/#/#aerynos:matrix.org).

- General Matrix room: [#AerynOS:matrix.org](https://matrix.to/#/#AerynOS:matrix.org)
- Development Matrix room: [#AerynOS-Dev:matrix.org](https://matrix.to/#/#AerynOS-Dev:matrix.org)
- Documentation Matrix room: [#aerynos-documentation:matrix.org](https://matrix.to/#/#aerynos-documentation:matrix.org)
- Webdev Matrix room: [#AerynOS-web:matrix.org](https://matrix.to/#/#AerynOS-web:matrix.org)

# Reporting Issues

If you find any bugs, inconsistencies or other problems, feel free to submit
a GitHub issue on the appropriate repository.
If you don't know which one that is, you can ask in the "General" Matrix,
or just take your best guess (we can move the issue afterwards if it's in the wrong place).

Also, if you have trouble getting on board, let us know
so we can help future contributors to the project overcome that hurdle too.

# Submitting Code

Ready to contribute some code? Great! Here are some guidelines to follow to help you on your way:

## Coding Style

In general, try to replicate the coding style that is already present.

We use [rustfmt] to ensure consistent formatting code and [clippy]
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
Once your PR has passed review, a maintainer will merge it and you're done! 🎉
