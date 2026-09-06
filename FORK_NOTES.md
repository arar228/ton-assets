# Fork context

This is a fork of [tonkeeper/ton-assets](https://github.com/tonkeeper/ton-assets),
an ecosystem registry of public TON addresses and asset metadata. Upstream
authorship and contribution guidance remain in [README.md](README.md).

## Repository role

The repository is a data/contribution workspace, rather than an independently
developed full-stack application. Review the commit comparison with upstream to
attribute individual changes; the presence of this fork does not claim authorship
of the upstream registry.

Asset addresses are public identifiers. Keeping them in JSON/YAML is part of the
registry's purpose; they are different from wallet signing keys or credentials.

To propose an asset update, follow the current upstream submission requirements
and preserve its schema and validation workflow. This fork's snapshot is dated by
its commit history and should not be assumed to track the latest upstream data.
