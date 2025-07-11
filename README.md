# Awesome SpiceDB

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![Docs](https://img.shields.io/badge/docs-authzed.com-%234B4B6C "Authzed Documentation")](https://docs.authzed.com)
[![Discord Server](https://img.shields.io/discord/844600078504951838?color=7289da&logo=discord "Discord Server")](https://discord.gg/jTysUaxXzM)
[![Twitter](https://img.shields.io/badge/twitter-%40authzed-1D8EEE?logo=twitter "@authzed on Twitter")](https://twitter.com/authzed)

An awesome list for the [SpiceDB] ecosystem.

Have questions? Join our [Discord].

Looking to contribute? See [CONTRIBUTING.md].

[SpiceDB]: https://github.com/authzed/spicedb
[Discord]: https://authzed.com/discord
[CONTRIBUTING.md]: https://github.com/authzed/spicedb/blob/main/CONTRIBUTING.md

## Contents

- [Awesome SpiceDB](#awesome-spicedb)
  - [Contents](#contents)
  - [Blog Posts](#blog-posts)
    - [English](#english)
    - [日本語](#日本語)
    - [中文](#中文) 
  - [Clients](#clients)
    - [Official Libraries](#official-libraries)
    - [Third-party Libraries](#third-party-libraries)
  - [Communities](#communities)
  - [Developer Tools](#developer-tools)
    - [Official Tools](#official-tools)
    - [Third-party Tools](#third-party-tools)
  - [Examples](#examples)
  - [Integrations](#integrations)
    - [Official Integrations](#official-integrations)
    - [Third-party Integrations](#third-party-integrations)
  - [Services](#services)
  - [Testing](#testing)

## Blog Posts

_Posts written about SpiceDB usage and development_

### English

- [Authzed's Official Blog](https://authzed.com/blog)
- [ABAC on SpiceDB: Enabling Netflix’s Complex Identity Types](https://netflixtechblog.com/abac-on-spicedb-enabling-netflixs-complex-identity-types-c118f374fa89)
- Abhishek Koserwal's SpiceDB Setup Guide: [Part 1](https://akoserwal.medium.com/a-comprehensive-guide-to-setting-up-spicedb-with-postgresql-and-a-monitoring-stack-b250f31d7775), [Part 2](https://akoserwal.medium.com/part-2-a-comprehensive-guide-to-setting-up-spicedb-operator-with-postgresql-and-a-monitoring-stack-3b3f92e20d77)
- [Modeling Google Drive in SpiceDB](https://www.mbilski.com/posts/fine-grained-authorization-made-easy-modeling-google-drive-in-spicedb)
- [KPMG: Getting Started with SpiceDB in .NET](https://medium.com/kpmg-uk-engineering/getting-started-with-spicedb-in-net-741e353a4d83)
- [Spicing up the Authorization Layer at Quizizz](https://eng.quizizz.com/p/spicing-up-the-authorization-layer)

### 日本語

- [SpiceDBで認可制御するLambda Authorizerを作ってみた](https://zenn.dev/manaty226/articles/96b6b693c6621c)
- [分散モノリスを解消して、モジュラモノリスとして扱うために](https://logmi.jp/tech/articles/329073)

### 中文

- [[源码]spicedb: 源码阅读之第一篇(热点缓存)](https://kylinlingh.github.io/2023/06/28/%E6%BA%90%E7%A0%81-spicedb-%E6%BA%90%E7%A0%81%E9%98%85%E8%AF%BB%E4%B9%8B%E7%AC%AC%E4%B8%80%E7%AF%87-%E7%83%AD%E7%82%B9%E7%BC%93%E5%AD%98/)
- [[源码]spicedb: 源码阅读之第二篇(k8s 部署和运行)](https://kylinlingh.github.io/2023/07/19/%E6%BA%90%E7%A0%81-spicedb-%E6%BA%90%E7%A0%81%E9%98%85%E8%AF%BB%E4%B9%8B%E7%AC%AC%E4%BA%8C%E7%AF%87-k8s-%E9%83%A8%E7%BD%B2/)
- [Chen Tian, SVP TubiTV China, presents SpiceDB](https://zhuanlan.zhihu.com/p/685603356)

## Clients

_Clients for interacting with SpiceDB_

### Official Libraries

- [authzed-go](https://github.com/authzed/authzed-go) - Official client library for Go
- [authzed-java](https://github.com/authzed/authzed-java) - Official client library for JVM languages in Java
- [authzed-node](https://github.com/authzed/authzed-node) - Official client library for NodeJS in JavaScript/TypeScript
- [authzed-py](https://github.com/authzed/authzed-py) - Official client library for Python
- [authzed-rb](https://github.com/authzed/authzed-rb) - Official client library for Ruby
- [authzed-dotnet](https://github.com/authzed/authzed-dotnet) - Official client library for Dotnet/CSharp

### Third-party Libraries

- Golang
  - [danhtran94/authzed-codegen](https://github.com/danhtran94/authzed-codegen) - Type-Safe stubs code generator for your AuthZed schemas
- .NET
  - [jalexsocial/spicedb](https://github.com/JalexSocial/SpiceDb) - gRPC client library in C#
- BEAM
  - [goodhamgupta/authzed-ex](https://github.com/goodhamgupta/authzed_ex) - gRPC client library in Elixir
- JavaScript/Typescript
  - [quizizz/spicedb-wrapper](https://github.com/quizizz/spicedb-wrapper) - Lightweight client wrapper of [authzed-node](https://github.com/authzed/authzed-node)
  - [SchoolAI/spicedb-zed-schema-parser](https://github.com/SchoolAI/spicedb-zed-schema-parser) - A tool to generate schema-aware typescript types and a type-safe wrapper for [authzed-node](https://github.com/authzed/authzed-node)
- JVM
  - [quarkiverse/quarkus-authzed-client](https://github.com/quarkiverse/quarkus-authzed-client) - gRPC client integration for Quarkus
  - [oviva-ag/spicegen](https://github.com/oviva-ag/spicegen) - type-safe client generator from a schema
- PHP
  - [alsbury/chiphpotle-rest](https://github.com/alsbury/chiphpotle-rest) - HTTP client library in PHP
  - [linkorb/spicedb-php](https://github.com/linkorb/spicedb-php) - HTTP client library in PHP
  - [linkorb/spicedb-bundle](https://github.com/linkorb/spicedb-bundle) - SpiceDB client Symfony Bundle
- Rust
  - [bitskico/authzed-rs](https://github.com/BitskiCo/authzed-rs) - gRPC client library in Rust
  - [structionsite/spicedb-client-rust](https://github.com/StructionSite/spicedb-client-rust) - gRPC client library in Rust
  - [Lur1an/spicedb-rust](https://github.com/Lur1an/spicedb-rust) - Opinionated SpiceDB gRPC client library in Rust

## Communities

_Online forums for discussing SpiceDB and meeting other users_

- [SpiceDB Discord](https://authzed.com/discord) - Discord community for SpiceDB
- [Authzed Linen](https://linen.authzed.com) - Searchable archive for the SpiceDB Discord
- [StackOverflow](https://stackoverflow.com/questions/tagged/spicedb) - StackOverflow questions tagged with SpiceDB
- [Twitter](https://twitter.com/authzed) - Official Authzed Twitter account

## Developer Tools

_Tools that help enhance the experience of using SpiceDB_

### Official Tools

- [Playground](https://play.authzed.com) - Official SpiceDB schema development environment
- [SpiceDB Operator](https://github.com/authzed/spicedb-operator) - Official Kubernetes Operator for running SpiceDB
- Thumper (proprietary) - Official load generation tool for SpiceDB
- [VS Code extension](https://marketplace.visualstudio.com/items?itemName=authzed.spicedb-vscode) - Official SpiceDB Visual Studio Code Extension
- [zed](https://github.com/authzed/zed) - Official command-line tool for managing SpiceDB

### Third-party Tools

- [spicedb-operator-libsonnet](https://github.com/jsonnet-libs/spicedb-operator-libsonnet) - Jsonnet library for the SpiceDB Operator
- [bushelpowered/spicedb-operator-chart](https://github.com/bushelpowered/spicedb-operator-chart) - Helm chart to install the SpiceDB Operator
- [mleonidas/tree-sitter-authzed](https://github.com/mleonidas/tree-sitter-authzed) - Neovim tree-sitter grammar and syntax for SpiceDB schemas
- [nhedger/vscode-spicedb](https://github.com/nhedger/vscode-spicedb) - Third-party VSCode extension
- [chiperific/vscode_authzed_syntax](https://github.com/chiperific/vscode_authzed_syntax) - Third-party VSCode syntax highlighting
- [dguhr/keycloak-spicedb-eventlistener](https://github.com/DGuhr/keycloak-spicedb-eventlistener) - Syncs changes to [Keycloak](https://www.keycloak.org) users and groups to SpiceDB
- [thomasdarimont/custom-opa-spicedb](https://github.com/thomasdarimont/custom-opa-spicedb) - Third-party build of Open Policy Agent with a plugin to query SpiceDB
- [umbrellaassociates/opa-spicedb](https://github.com/umbrellaassociates/opa-spicedb) - Third-party build of Open Policy Agent with a plugin to query SpiceDB
- [mejaz/spicedb-ui](https://github.com/mejaz/spicedb-ui) - Third-party SpiceDB web interface that allows inspection and management of a running SpiceDB instance

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

- [guicassolato/authorino-spicedb](https://github.com/guicassolato/authorino-spicedb) - Implementation of [Envoy external authz](https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_authz_filter) that can be driven by SpiceDB
- [gitpod-io/gitpod](https://github.com/gitpod-io/gitpod) - GitPod's support for fine-grained authorization leverages SpiceDB
- [infratographer/permissions-api](https://github.com/infratographer/permissions-api) - The default authorization strategy for Infratographer leverages SpiceDB
- [raystack/frontier](https://github.com/raystack/frontier) - Cloud-native, role-based user management system and authorization server for your applications and API endpoints
- [wolfi-dev/os](https://github.com/wolfi-dev/os/blob/main/spicedb.yaml) - Container build toolchain that packages SpiceDB
- [koralium/flowtide](https://koralium.github.io/flowtide/docs/connectors/spicedb) - Data streaming engine, can read/write data into SpiceDB and can also denormalize SpiceDB permissions when integrating with other databases/systems.
- [Redpanda connector - spicedb_watch](https://docs.redpanda.com/redpanda-connect/components/inputs/spicedb_watch/) - Consumes messages from the Watch API of a SpiceDB instance. This input is useful if you have downstream applications that need to react to real-time changes in data managed by SpiceDB.

## Services

_Managed services that operate SpiceDB for you_

- [SpiceDB Dedicated](https://authzed.com/pricing) - Private, isolated clusters operated by the experts at Authzed
- [SpiceDB Serverless](https://app.authzed.com) - Self-service shared clusters operated by Authzed

## Testing

_Tools and libraries used to test or validate usage of SpiceDB_

- [authzed/action-spicedb-validate](https://github.com/authzed/action-spicedb-validate) - GitHub Action for validating your SpiceDB schema
- [authzed/action-spicedb](https://github.com/authzed/action-spicedb) - GitHub Action for integration testing your application with SpiceDB
- [northone-inc/local-spicedb](https://github.com/northone-inc/local-spicedb) - Node library for running SpiceDB ephermally for testing
