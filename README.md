# Awesome Smithy

[<img src="smithy.svg" align="right" width="300">](https://smithy.io)

*Awesome Smithy* is a curated list of awesome build-tools, code-generators, examples, and other resources related to
the [Smithy IDL](https://github.com/awslabs/smithy).

If you want your component to appear here, send a pull request to this repository to add it (see the [contribution
guidelines](#contribute) for more information).

The Smithy team cannot vouch for the stability or production-worthiness an item on this list unless it has the icon
<img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> next to it. This icon means the
component is an official project supported by the [Smithy](https://github.com/smithy-lang) team.
Official Smithy team projects with the 🚧 icon next to them are still a work-in-progress and are not production-ready.


## Contents
  - [Contents](#contents)
  - [Build tools](#build-tools)
  - [Code Generators](#code-generators)
    - [Client Code Generators](#client-code-generators)
    - [Server Code Generators](#server-code-generators)
  - [Learning resources](#learning-resources)
  - [IDE Support](#ide-support)
  - [Implementations](#implementations)
  - [Model Converters](#model-converters)
  - [CICD Support](#cicd-support)
    - [GitHub Actions](#github-actions)
  - [Videos](#videos)
  - [Blog Posts](#blog-posts)
  - [Others](#others)
  - [Contribute](#contribute)

## Build tools
* [Smithy CLI](https://github.com/smithy-lang/smithy/tree/main/smithy-cli) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Smithy CLI is used to build, validate, diff, and transform Smithy models.
* [Gradle Plugin](https://github.com/smithy-lang/smithy-gradle-plugin) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Integrates Smithy with the Gradle build system.
* [Mill Plugin](https://disneystreaming.github.io/smithy4s/docs/overview/installation/#mill) - Community supported plugin that integrates smithy with the [Mill build tool](https://github.com/com-lihaoyi/mill).
* [SBT Plugin](https://disneystreaming.github.io/smithy4s/docs/overview/installation/#sbt) - Community supported plugin that integrates smithy with the SBT build system for Scala.

## Code Generators
### Client Code Generators
* [TypeScript](https://github.com/awslabs/smithy-typescript) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Typescript.
* [Golang](https://github.com/aws/smithy-go) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Golang.
* [Rust](https://github.com/awslabs/smithy-rs) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Rust.
* [Ruby](https://github.com/awslabs/smithy-ruby) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Ruby.
* [Kotlin](https://github.com/awslabs/smithy-kotlin) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Kotlin.
* [Swift](https://github.com/awslabs/smithy-swift) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Swift.
* [Scala](https://github.com/disneystreaming/smithy4s) - Community plugin for generation of clients/servers in Scala.
* [Dafny](https://github.com/awslabs/smithy-dafny) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Code generation tools for the [Dafny](https://dafny.org/) verification-aware programming language.
* [Python](https://github.com/smithy-lang/smithy-python) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Client code generation for Python.

### Server Code Generators
* [TypeScript](https://github.com/awslabs/smithy-typescript) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Server generator for TypeScript.
* [Rust](https://github.com/awslabs/smithy-rs) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Server generator for Rust.
* [Scala](https://github.com/disneystreaming/smithy4s) - Community plugin for generation of clients/servers in Scala.


## Learning resources
* [Smithy Examples](https://github.com/smithy-lang/smithy-examples) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - A collection of examples to help you get up and running with Smithy.
* [aws-samples: Typescript Example service](https://github.com/aws-samples/smithy-server-generator-typescript-sample) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Shows how to write a Typescript lambda service using Smithy and call the service using a generated client (see: [blog post](https://aws.amazon.com/blogs/devops/smithy-server-and-client-generator-for-typescript/)).
* [Rust server SDK examples](https://github.com/awslabs/smithy-rs/tree/main/examples) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - a collection of examples using Smithy to generate a Rust server SDK.
* [kubukoz/smithy4s-course](https://github.com/kubukoz/smithy4s-course) - Smithy/Smithy4s course.

## IDE Support
* [Smithy LSP](https://github.com/awslabs/smithy-language-server) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - A Language Server Protocol implementation for the Smithy IDL.
* [Visual Studio Code Plugin](https://github.com/awslabs/smithy-vscode) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Visual Studio Code extension providing a Language Server Protocol implementation for the Smithy IDL.
* [Intellij plugin](https://github.com/awslabs/smithy-intellij) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> 🚧 - Provides IDE integration for the Smithy IDL within IntelliJ IDEA.
* [iancaffey/smithy-intellij-plugin](https://github.com/iancaffey/smithy-intellij-plugin) - Community plugin for IDE integration for the Smithy IDL in Intellij IDEA.
* [Tree Sitter Grammar for Smithy](https://github.com/indoorvivants/tree-sitter-smithy) - Tree-sitter grammar for Smithy. Included in [Neovim](https://github.com/nvim-treesitter/nvim-treesitter) and [Helix](https://docs.helix-editor.com/) by default.
* [Zed extension](https://github.com/joshrutkowski/zed-smithy) - [Zed](https://zed.dev/) extension using [Tree-sitter grammar for Smithy](https://github.com/indoorvivants/tree-sitter-smithy).

## Implementations
* [Smithy Reference Implementation](https://github.com/awslabs/smithy) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Smithy reference implementation in Java
* [Atelier](https://github.com/johnstonskj/rust-atelier) 🚧 - Community implementation of Smithy in Rust

## Model Converters
* [Smithy to OpenAPI](https://smithy.io/2.0/guides/converting-to-openapi.html#smithy-to-openapi) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Converts Smithy models to [OpenAPI](https://www.openapis.org/).
* [Smithy to JSONSchema](https://github.com/awslabs/smithy/tree/main/smithy-jsonschema) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Converts Smithy models to [JSONSchema](https://json-schema.org/).
* [Cloud Formation Resource Schemas](https://smithy.io/2.0/guides/generating-cloudformation-resources.html#smithy-to-cloudformation) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Generating Cloudformation resource schemas from Smithy models.
* [Openapi/JSONSchema to Smithy](https://github.com/disneystreaming/smithy-translate) - smithy-translate : a community-provided CLI tool for best-effort Openapi/JSONSchema to Smithy conversions
* [Smithy to Protobuf](https://github.com/disneystreaming/smithy-translate) - smithy-translate (see above)

## CICD Support
### GitHub Actions
* [setup-smithy](https://github.com/marketplace/actions/setup-smithy) - Install Smithy CLI to your GitHub Workflow.
* [format-smithy](https://github.com/marketplace/actions/format-smithy) - Checks if Smithy Models are formatted.

## Videos
* [Scaling APIs with Smithy](https://www.youtube.com/watch?v=3GpZzu4guTE) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Overview of Smithy's background and features.
* [Abstraction: Creating the Best developer experience / Model-First Design](https://youtu.be/gX2sHQafadA?t=1558) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - An introduction to model first design with Smithy.
* [Building with the new AWS SDKs for Rust, Kotlin, and Swift](https://www.youtube.com/watch?v=Nhk1K1AjYvg) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Explores how these SDKs were built in parallel with Smithy, the commonalities they share, and how to build an app with each one.
* [Simplify building applications with AWS SDKs](https://www.youtube.com/watch?v=7J0UMAGgAdw) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Discusses how Smithy and model-first API design are used at AWS, how the AWS SDKs model client-side primitives such as paginators in Smithy, and how the AWS SDKs are evolving to use a standardized architecture.
* [Introduction to Smithy/Smithy4s](https://www.youtube.com/watch?v=CA8qGXMQ3cE) - Scala Conference talk introducing the Smithy IDL and the Smithy4s library
* [Generating Kotlin SDKs with Smithy](https://www.youtube.com/watch?v=Wsra04prG-E) - KotlinConf talk that provides an overview of Smithy and discusses how `smithy-kotlin` can be used to generate Kotlin SDKs

## Blog Posts
* [Introducing Smithy IDL 2.0](https://aws.amazon.com/blogs/developer/introducing-smithy-idl-2-0/) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Launch announcement for the Smithy IDL 2.0.
* [Introducing the Smithy CLI](https://aws.amazon.com/blogs/developer/introducing-the-smithy-cli/) <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Launch announcement for the Smithy CLI along with examples of how to use the CLI.
* [Developer Preview: Ruby SDK code generation using Smithy](https://aws.amazon.com/blogs/developer/developer-preview-smithy-code-generated-ruby-sdk/)  <img src="smithy-favicon.png" alt="(official)" title="Smithy Official" height="16px"> - Launch announcement for and overview of the AWS Ruby SDK built with Smithy.
* [Smithy4s-full stack](https://blog.indoorvivants.com/2022-06-10-smithy4s-fullstack-part-1) - A series of posts describing an application built with Smithy4s in both front-end and back-end.

## Others
* [Smithy Playground](https://github.com/kubukoz/smithy-playground/) 🚧 - A language server and VS Code client for interactive experimentation with Smithy services.
* [Build Server Protocol](https://github.com/build-server-protocol/build-server-protocol) - an extension to the Language Server Protocol using Smithy as a definition language.
* [Alloy](https://github.com/disneystreaming/alloy/) - a library of Smithy traits providing additional semantics and constraints, used in particular by smithy-translate and smithy4s.

## Contribute
Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
