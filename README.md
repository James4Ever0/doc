# doc

Doc is a programming language agnostic documentation generation tool.

**Highlights**
- Fault tolerant
- Programming language agnostic
- Multi-language documentation support
- Customizable file exclusion pattern
- Generation progress visualization
- Processing time estimation
- Caching docs by hashing
- Easy installation and usage
- Intuitive and informative UI
- Using OpenAI-compatible API

## Installation

```bash
pip3 install doc3
```

## Usage

```bash
doc --help
doc --list-langs
```

```bash
doc generate
doc generate --langs en,de,zh,fr,jp
```

```bash
doc estimate
doc estimate --langs en,de,zh,fr,jp
```

```bash
doc serve
doc serve --port 8002 --host 0.0.0.0
doc serve --browse
```

## How it works

Doc chops your code into segments and query documentation from LLM. After that, it groups docs two by two and reduce them recursively, till it gets the summary.

Doc creates a beautiful static website for your codebase, meaning you can deploy to Github pages for free.

## .docignore

Just like `.gitignore` but better. Control files to document at granual level.

### Syntax

## Browsing Doc

## Hosting Doc

## Roadmap

[x] - English language support

