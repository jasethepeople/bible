# bible

A single self-contained HTML app served at the repo root.

## Features

The repo holds one 260 KB file, `Biblical-Library.html`: a bundled, single-file React application (Tailwind-styled, Google Fonts Fraunces/Instrument Serif). The existing README is just the title. The HTML `<title>` is "React Artifact", so this appears to be a self-contained web artifact (a Biblical library reader) exported as one static file. No source files, build config, or descriptions are included, so features cannot be enumerated beyond what the single page delivers.

## Tech stack

Plain static HTML/JS (bundled React, Tailwind CSS classes inlined). Served on Vercel.

## Getting started

No build step — `vercel.json` rewrites `/` to `/Biblical-Library.html`, so it deploys as a static site on Vercel.

## Project structure

```
├── Biblical-Library.html   # the entire app (single bundled file)
├── vercel.json             # rewrites / → /Biblical-Library.html
└── README.md               # title only
```

## Status

Near-empty / single-artifact repo. It works as a static page, but there is no source tree to develop against.
