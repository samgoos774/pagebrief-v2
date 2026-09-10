# pagebrief-v2

MV3 extension: one click, tl;dr of any article

Built for my own use; public in case it helps someone.

## Examples

```bash
# open any article, click the icon, get a 5-bullet summary
```

## What it does

- Popup shows a 5-bullet summary
- Options page for API base and key
- Reads the page, extracts main text, sends to your endpoint
- Manifest V3 service worker, no build step

## Install

```bash
# chrome://extensions -> load unpacked -> select this folder
# set your API base + key on the options page
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── workflows/
│   │   └── ci.yml
│   └── pull_request_template.md
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── options.html
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```
