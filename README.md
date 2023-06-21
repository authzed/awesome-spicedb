# Awesome SpiceDB

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![Docs](https://img.shields.io/badge/docs-authzed.com-%234B4B6C "Authzed Documentation")](https://docs.authzed.com)
[![Discord Server](https://img.shields.io/discord/844600078504951838?color=7289da&logo=discord "Discord Server")](https://discord.gg/jTysUaxXzM)
[![Twitter](https://img.shields.io/twitter/follow/authzed?color=%23179CF0&logo=twitter&style=flat-square "@authzed on Twitter")](https://twitter.com/authzed)

An awesome list for the [SpiceDB] ecosystem.

Have questions? Join our [Discord].

Looking to contribute? See [CONTRIBUTING.md].

[SpiceDB]: https://github.com/authzed/spicedb
[Discord]: https://authzed.com/discord
[CONTRIBUTING.md]: https://github.com/authzed/spicedb/blob/main/CONTRIBUTING.md

## Contents

- [Awesome SpiceDB](#awesome-spicedb)
  - [Contents](#contents)
  - [Clients](#clients)
    - [Official Tools](#official-tools)
    - [Official Libraries](#official-libraries)
    - [Third-party Libraries](#third-party-libraries)
  - [Communities](#communities)
  - [Examples](#examples)
  - [Integrations](#integrations)
    - [Official Integrations](#official-integrations)
    - [Third-party Integrations](#third-party-integrations)
  - [Services](#services)
  - [Testing](#testing)

## Clients

_Clients for interacting with SpiceDB_

### Official Tools

- Thumper (proprietary) - Official load generation tool for SpiceDB
- [Playground](https://play.authzed.com) - Official SpiceDB schema development environment
- [zed](https://github.com/authzed/zed) - Official command-line tool for managing SpiceDB
- [SpiceDB Operator](https://github.com/authzed/spicedb-operator) - Official Kubernetes Operator for running SpiceDB

### Official Libraries

- [authzed-go](https://github.com/authzed/authzed-go) - Official client library for Go
- [authzed-java](https://github.com/authzed/authzed-java) - Official client library for JVM languages in Java
- [authzed-node](https://github.com/authzed/authzed-node) - Official client library for NodeJS in JavaScript/TypeScript
- [authzed-py](https://github.com/authzed/authzed-py) - Official client library for Python
- [authzed-rb](https://github.com/authzed/authzed-rb) - Official client library for Ruby

### Third-party Libraries

- .NET
  - [jkulubya/authzed-dotnet](https://github.com/jkulubya/authzed-dotnet) (2021) - gRPC client library in C#
  - [amcguier/authzed-dotnet](https://github.com/amcguier/authzed-dotnet) - gRPC client library in F#
  - [jalexsocial/spicedb](https://github.com/JalexSocial/SpiceDb) - gRPC client library in C#
- BEAM
  - [goodhamgupta/authzed-ex](https://github.com/goodhamgupta/authzed_ex) - gRPC client library in Elixir
- JVM
  - [quarkiverse/quarkus-authzed-client](https://github.com/quarkiverse/quarkus-authzed-client) - gRPC client integration for Quarkus
- PHP
  - [alsbury/chiphpotle-rest](https://github.com/alsbury/chiphpotle-rest) - HTTP client library in PHP
  - [linkorb/spicedb-php](https://github.com/linkorb/spicedb-php) - HTTP client library in PHP
- Rust
  - [bitskico/authzed-rs](https://github.com/BitskiCo/authzed-rs) - gRPC client library in Rust
  - [structionsite/spicedb-client-rust](https://github.com/StructionSite/spicedb-client-rust) - gRPC client library in Rust

## Communities

_Online forums for discussing SpiceDB and meeting other users_

- [SpiceDB Discord](https://authzed.com/discord) - Discord community for SpiceDB
- [Authzed Linen](https://linen.authzed.com) - Searchable archive for the SpiceDB Discord
- [StackOverflow](https://stackoverflow.com/questions/tagged/spicedb) - StackOverflow questions tagged with SpiceDB
- [Twitter](https://twitter.com/authzed) - Official Authzed Twitter account

## Examples

_Example usage of SpiceDB and the tools in its ecosystem_

- [authzed/examples](https://github.com/authzed/examples) - Official examples repository
- [SpiceDB Helm Chart](https://github.com/jonwhitty/helm-charts/tree/master/charts/spicedb) - Helm Chart for an example 3-node deployment

## Integrations

_Projects that integrate with SpiceDB_

### Official Integrations

- [authzed/connector-postgres](https://github.com/authzed/connector-postgresql) - Deprecated synchronization between PostgreSQL and SpiceDB
- [authzed/prom-authzed-proxy](https://github.com/authzed/prom-authzed-proxy) - Prometheus proxy that performs SpiceDB permission checks based on labels

### Third-party Integrations

- [bushelpowered/spicedb-operator-chart](https://github.com/bushelpowered/spicedb-operator-chart) - Helm chart to install the SpiceDB Operator
- [mleonidas/tree-sitter-authzed](https://github.com/mleonidas/tree-sitter-authzed) - Neovim tree-sitter grammar and syntax for SpiceDB schemas
- [nhedger/vscode-spicedb](https://github.com/nhedger/vscode-spicedb) - Third-party VSCode extension
- [thomasdarimont/custom-opa-spicedb](https://github.com/thomasdarimont/custom-opa-spicedb) - Third-party Open Policy Agent plugin to query SpiceDB
- [quarkiverse/quarkus-authzed-client](https://quarkus.io/extensions/io.quarkiverse.authzed/quarkus-authzed-client) - gRPC client integration for Quarkus
- [odpf/shield](https://github.com/odpf/shield) - Cloud Native RBAC user management system, identity & access proxy, and authorization server for API endpoints

## Services

_Managed services that operate SpiceDB for you_

- [SpiceDB Dedicated](https://authzed.com/pricing) - Private, isolated clusters operated by the experts at Authzed
- [SpiceDB Serverless](https://app.authzed.com) - Self-service shared clusters operated by Authzed

## Testing

_Tools and libraries used to test or validate usage of SpiceDB_

- [authzed/action-spicedb-validate](https://github.com/authzed/action-spicedb-validate) - GitHub Action for validating your SpiceDB schema
- [authzed/action-spicedb](https://github.com/authzed/action-spicedb) - GitHub Action for integration testing your application with SpiceDB
