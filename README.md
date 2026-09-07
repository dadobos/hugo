# Hugo

A personal Hugo project.

## Prerequisites

- [Hugo](https://gohugo.io/installation/)
- Git

## Getting Started

Clone the repository and start the local development server:

```bash
git clone https://github.com/dadobos/hugo.git
cd hugo
hugo server
```

Open the local URL printed in the terminal, usually:

```text
http://localhost:8765/
```

## Common Commands

```bash
# Start development server
hugo server --port=8765

# Include draft content
hugo server -D

# Build the site
hugo
```

## Project Structure

```text
content/      Site content
layouts/      Custom templates
static/       Static assets
themes/       Hugo themes
config.*      Site configuration
public/       Generated site output
```

## Deployment

Build the site with:

```bash
hugo
```

The generated files will be available in the `public/` directory.
