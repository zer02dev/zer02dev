# filip.bragiel.dev

Personal site — interactive terminal interface.

## structure

```
index.html              # terminal shell — single file, no build step
content/
  about.md              # about me
  contact.md            # contact info
  motorsport.md         # racing background
  projects/
    bimmerdaten.md
    e36-samuraj.md
    gps-lap-timer.md
    homelab.md
    meshtastic.md
    circuit-bending.md
```

## adding a project

1. Create `content/projects/my-project.md` with frontmatter:

```md
---
title: My Project
tags: tag1 tag2 tag3
status: active | in-progress | ongoing
repo: https://github.com/...
---

# My Project

Description here...
```

2. Register it in `index.html` in the `FS` object under `projects > children`:

```js
'my-project.md': { type: 'file', src: 'content/projects/my-project.md' },
```

That's it.

## deploy

Push to `gh-pages` branch or configure GitHub Pages to serve from `main`.
No build step required.

## commands

| command | description |
|---------|-------------|
| `ls` | list files |
| `cd <dir>` | change directory |
| `cat <file>` | read file |
| `pwd` | current path |
| `open <url>` | open link |
| `neofetch` | system info |
| `clear` | clear terminal |
| `history` | command history |
| `help` | all commands |

Tab autocomplete and ↑/↓ history navigation work.
