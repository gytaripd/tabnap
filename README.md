# tabnap

MV3 extension playground: page reading-time estimator

## Getting started

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## What it does

- Per-tab time persisted to chrome.storage
- Manifest V3, service worker based
- Popup shows today's total focus time
- No remote calls, everything stays local

## Examples

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```
