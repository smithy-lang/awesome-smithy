# Awesome Smithy

[<img src="smithy.svg" align="right" width="300">](https://smithy.io)

*Awesome Smithy* is a curated list of awesome build-tools, code-generators, examples, and other resources related to
the [Smithy IDL](https://github.com/awslabs/smithy).

If you want your component to appear here, send a pull request to this repository to add it (see the [contribution
guidelines](CONTRIBUTING.md) for more information).

The Smithy team cannot vouch for the stability or production-worthiness an item on this list unless it has the icon
<img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> next to it. This icon means the
component is an official project supported by the [Smithy](https://github.com/smithy-io) team.
Official Smithy team projects with the 🚧 icon next to them are still a work-in-progress and are not production-ready.


## Contents
* [Build tools](#build-tools)
* [Code Generators](#code-generators)
    * [Client Code Generators](#client-code-generators)
    * [Server Code Generators](#server-code-generators)
* [IDE Support](#ide-support)
* [Implementations](#implementations)
* [Model Converters](#model-converters)

## Build tools
* [Smithy CLI](https://github.com/awslabs/smithy/tree/main/smithy-cli) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Smithy CLI is used to build, validate, diff, and transform Smithy models.
* [Gradle Plugin](https://github.com/awslabs/smithy-gradle-plugin) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Integrates Smithy with the Gradle build system.
* [SBT Plugin](https://disneystreaming.github.io/smithy4s/docs/overview/sbt) - Community supported plugin that integrates smithy with the SBT build system for Scala.

## Code Generators
### Client Code Generators
* [TypeScript](https://github.com/awslabs/smithy-typescript) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Typescript.
* [Golang](https://github.com/awslabs/smithy-go) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Golang.
* [Rust](https://github.com/awslabs/smithy-rs) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Rust.
* [Kotlin](https://github.com/awslabs/smithy-kotlin) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Kotlin.
* [Swift](https://github.com/awslabs/smithy-swift) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Swift.
* [Scala Code Generation for Smithy](https://github.com/disneystreaming/smithy4s) - Community plugin for generation of clients in Scala.

### Server Code Generators
* [TypeScript](https://github.com/awslabs/smithy-typescript) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Server generator for TypeScript.
* [Rust](https://github.com/awslabs/smithy-rs) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Server generator for Rust.

## IDE Support
* [Smithy LSP](https://github.com/awslabs/smithy-language-server) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - A Language Server Protocol implementation for the Smithy IDL.
* [Visual Studio Code Plugin](https://github.com/awslabs/smithy-vscode) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Visual Studio Code extension to recognize and highlight the Smithy IDL.
* [Intellij plugin](https://github.com/awslabs/smithy-intellij) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Provides IDE integration for the Smithy IDL within IntelliJ IDEA.
* [iancaffey/smithy-intellij-plugin](https://github.com/iancaffey/smithy-intellij-plugin) - Community plugin for IDE integration for the Smithy IDL in Intellij IDEA.
* [Tree Sitter Grammar for Smithy](https://github.com/indoorvivants/tree-sitter-smithy) - Included in [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) to provide syntax highlighting in Neovim.

## Implementations
* [Smithy Reference Implementation](https://github.com/awslabs/smithy) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Smithy reference implementation in Java
* [Atelier](https://github.com/johnstonskj/rust-atelier) - Community implementation of Smithy in Rust

## Model Converters
* [OpenAPI](https://smithy.io/2.0/guides/converting-to-openapi.html#smithy-to-openapi) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Converts Smithy models to [OpenAPI](https://www.openapis.org/)
* [JSONSchema](https://github.com/awslabs/smithy/tree/main/smithy-jsonschema) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Converts Smithy models to [JSONSchema](https://json-schema.org/)
* [Cloud Formation Resource Schemas](https://smithy.io/2.0/guides/generating-cloudformation-resources.html#smithy-to-cloudformation) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Generating Cloudformation resource schemas from Smithy models


## Contribute
Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

