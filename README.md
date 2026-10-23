# FedCLI Binary Releases

This repository contains official ApplexTech FedCLI binary releases and installation guidance. It intentionally does **not** contain proprietary FedCLI source code.

FedCLI is a federated data CLI for relational, NoSQL, search, graph, and cloud data systems. It supports interactive work, scripts, automation, and federated workflows across heterogeneous platforms.

## Install with Homebrew

```bash
brew install applextech/homebrew-tap/fedcli
fedcli --help
```

The formula pins the exact release JAR by SHA-256 and installs Java 17 through Homebrew when needed. The legacy `dbcli` command remains available as a compatibility alias.

## Direct release assets

Each release provides the executable JAR, its SHA-256 checksum, and the applicable license documents. Run the JAR with Java 17 or later:

```bash
java -jar dbcli-<version>.jar --help
```

## License

FedCLI is source-available software distributed under ApplexTech's commercial EULA with a limited free-use license. Commercial production, redistribution, OEM, managed service, and hosted service use require the applicable commercial rights. Read the `LICENSE.md`, `FREE-USAGE-LICENSE.md`, and `EULA.md` assets attached to each release before use.
