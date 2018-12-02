# DockerLocalDev

Local development using docker.

## Installation

Coming soon...

## How to use

In your project directory run the following command

```bash
localdev <tool_name> <command> [args]
```

Example: to convert DocBook to PDF using asciidoctor-fopub tool

```bash
localdev asciidoctor-fopub fopub sample.xml
```

## Available tools

- [asciidoctor](https://github.com/DockerLocalDev/asciidoctor-localdev)
- [asciidoctor-fopub](https://github.com/DockerLocalDev/asciidoctor-fopub-localdev)

## TODO

- [ ] Each project must save each tool version
- [ ] Support for configuring tool
