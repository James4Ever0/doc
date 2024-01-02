# doc

Doc is a programming language agnostic documentation generation tool.

**Highlights**
- Programming language agnostic
- Multi-language documentation support
- Processing time estimation
- Easy installation and usage
- Intuitive and informative UI
- Using OpenAI-compatible API

## Usage

```bash
doc --help
doc --list-langs
```

```bash
doc generate
doc generate --langs en,de,cn,fr,jp
```

```bash
doc estimate
doc estimate --langs en,de,cn,fr,jp
```

## How it works

Doc chops your code into segments and query documentation from LLM. After that, we group docs two by two and reduce them recursively, till we get the summary.

Doc creates a beautiful static website for your codebase, meaning you can deploy to Github pages for free.

## .docignore

Just like `.gitignore` but better. Control files to document at granual level.

### Syntax

## Browsing Doc

## Hosting Doc

## Roadmap

[x] - English language support

