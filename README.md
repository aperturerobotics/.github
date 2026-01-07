<h3 align="center">
  <a href="https://github.com/aperturerobotics" target="_blank" rel="noopener noreferrer">
    <img height="100" src="https://github.com/aperturerobotics/.github/blob/3baf7d875b181ba290c3f7aba9eb4db53f7db0b5/images/aperture-logo.png" alt="Aperture Robotics">
  </a>
  <br/>
  &nbsp;
</h1>
<h3 align="center">
  Modular, lightweight, cross-platform apps with Go and TypeScript.
</h3>
<p align="center">
  Aperture Robotics is an open source focused organization building<br />
  a next-generation development stack for apps w/ Go, Wasm, TypeScript.
</p>
<h3 align="center" style="margin-top: 5px">
  <a href="https://discord.gg/KJutMESRsT">
    <img src="https://img.shields.io/discord/803825858599059487.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge" alt="Support Server" />
  </a>
</h3>

## 🏗️ Projects

Get started building an application with the stack with [the project template]!

[the project template]: https://github.com/aperturerobotics/template

### 🧱 App Stack

- [**ControllerBus**][controllerbus] - Dynamically configurable communicating control loops
- [**Bifrost**][bifrost] - Cross-platform networking engine with pluggable transports
- [**goscript**][goscript] - Transpile Go to TypeScript
- [**ocpipe**][ocpipe] - Build LLM pipelines with OpenCode and Zod

[controllerbus]: https://github.com/aperturerobotics/controllerbus
[bifrost]: https://github.com/aperturerobotics/bifrost
[goscript]: https://github.com/aperturerobotics/goscript
[ocpipe]: https://github.com/s4wave/ocpipe

### <img src="https://raw.githubusercontent.com/skiffos/SkiffOS/master/resources/images/skiff-icon.png" alt="SkiffOS logo" width="28" height="28" style="vertical-align: bottom"/> SkiffOS

[SkiffOS] is a minimal Linux distribution designed to run containers on embedded
devices. It uses [Buildroot] to cross-compile a tiny system image with support
for Docker and other container runtimes. [SkiffOS] enables running any Linux
distribution or application in lightweight containers on embedded hardware.

[SkiffOS]: https://github.com/skiffos/skiffos
[Buildroot]: https://buildroot.org

### 🪶 Lightweight Protobuf

These are lightweight reflection-free code-generation based implementations of
Protobuf designed to optimize binary size and performance, especially for
WebAssembly (wasm) applications.

- [**StaRPC**][starpc] - Protobuf 3 RPC services over any stream multiplexer
- [**protobuf-es-lite**][protobuf-es-lite] - Lightweight TypeScript protobuf implementation
- [**protobuf-go-lite**][protobuf-go-lite] - Lightweight Go protobuf implementation
- [**protobuf-project**][protobuf-project] - Template repository for projects using protobufs

[starpc]: https://github.com/aperturerobotics/starpc
[protobuf-es-lite]: https://github.com/aperturerobotics/protobuf-es-lite
[protobuf-go-lite]: https://github.com/aperturerobotics/protobuf-go-lite
[protobuf-project]: https://github.com/aperturerobotics/protobuf-project

Protobuf libraries like [protobuf-es] and [protobuf-go] focus on spec compliance
and feature-complete implementations. These **lite** libraries focus on just the
base proto2 and proto3 spec including RPCs to simplify the implementation.

[protobuf-es]: https://github.com/bufbuild/protobuf-es
[protobuf-go]: https://github.com/protocolbuffers/protobuf-go

### 📚 Libraries

Common Go/TypeScript libraries:

- [**Common**][common] - Common project configuration files and Protobuf toolchain.
- [**Util**][util] - Go utilities for easy concurrent programming.

Lightweight / modified forks of other libraries:

- [**Cayley**][cayley] - Go Graph database forked from [cayleygraph]
- [**FlexLayout**][flex-layout] - Interactive drag/drop layout manager for React
- [**fastjson**][fastjson] - Reflection-free json parser and validator
- [**go-brotli-decoder**][go-brotli-decoder] - Pure Go Brotli decompressor
- [**go-indexeddb**][go-indexeddb] - Low-level Go driver for IndexedDB in Wasm
- [**go-kvfile**][go-kvfile] - File format for storing a compressed key/value store
- [**go-quickjs-wasi-reactor**][go-quickjs-wasi-reactor] - Go module with embedded QuickJS WASI binary
- [**goprotowrap**][goprotowrap] - Package-at-a-time wrapper for protoc
- [**js-quickjs-wasi-reactor**][js-quickjs-wasi-reactor] - Run QuickJS within JavaScript with WASI
- [**json-iterator-lite**][json-iterator-lite] - Minimal and fast reflection-free json marshal and unmarshal for Go

[cayley]: https://github.com/aperturerobotics/cayley
[fastjson]: https://github.com/aperturerobotics/fastjson
[flex-layout]: https://github.com/aperturerobotics/flex-layout
[go-brotli-decoder]: https://github.com/aperturerobotics/go-brotli-decoder
[go-indexeddb]: https://github.com/aperturerobotics/go-indexeddb
[go-kvfile]: https://github.com/aperturerobotics/go-kvfile
[go-quickjs-wasi-reactor]: https://github.com/aperturerobotics/go-quickjs-wasi-reactor
[goprotowrap]: https://github.com/aperturerobotics/goprotowrap
[js-quickjs-wasi-reactor]: https://github.com/aperturerobotics/js-quickjs-wasi-reactor
[json-iterator-lite]: https://github.com/aperturerobotics/json-iterator-lite
[cayleygraph]: https://cayley.io/
[util]: https://github.com/aperturerobotics/util
[common]: https://github.com/aperturerobotics/common

## 🙋 Support

Please open a [GitHub issue][github-issue] or [email us] with any questions.

Or feel free to reach out on [Matrix Chat][matrix-chat] or [Discord][discord].

[github-issue]: https://github.com/aperturerobotics/.github/issues/new
[matrix-chat]: https://matrix.to/#/#aperturerobotics:matrix.org
[discord]: https://discord.gg/KJutMESRsT
[email us]: mailto:hello@aperture.us

## 📜 License

Most projects are licensed MIT/Apache-2.0.

See the `LICENSE` file in each repository.
