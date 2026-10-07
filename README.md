<div align="center">

# my-pi-extensions

**Pi extensions I build — and the third-party ones I recommend.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Pi packages](https://img.shields.io/badge/Pi-package%20gallery-111111.svg)](https://pi.dev/packages)

English | [简体中文](./README_zh.md)

</div>

---

A curated index of extensions for the [pi coding agent](https://github.com/earendil-works/pi).
Source code lives in each extension's own repository; this repo only maintains this README.

## My extensions

| Extension | Status | Category | What it does |
| --- | --- | --- | --- |
| [pi-speed](https://github.com/Wade11s/pi-speed) | 🚀 Actively improving | Status-bar metrics | Shows time to first token, generation speed, and cumulative session time in pi's native UI. |
| [pi-x-search](https://github.com/Wade11s/pi-x-search) | 🚀 Actively improving | X search | Lets the agent research public X/Twitter content through the official xAI API. |
| [pi-explain](https://github.com/Wade11s/pi-explain) | 🚧 In development | Content generation | Turns an explanation into clear prose, a static diagram, or an interactive web page. |
| [pi-stepfun](https://github.com/Wade11s/pi-stepfun) | 🔧 Maintained | Model provider | Brings the StepFun (阶跃星辰) Step Plan subscription models into pi. |
| [pi-radeon-cloud-cn](https://github.com/Wade11s/pi-radeon-cloud-cn) | 🔧 Maintained | Model provider | Adds an AMD Radeon Cloud CN model provider to pi. |
| [pi-web-toolkit](https://github.com/Wade11s/pi-web-toolkit) | ⚠️ Deprecated | Web search & scraping | A local-first web research toolkit that searches, batch-fetches, and interactively browses pages. |

Most extensions need **Node.js ≥ 22.19**. After installing or updating one, run `/reload` in an
open session or restart pi.

## Installing and managing packages

```bash
pi install npm:pi-web-toolkit              # from npm
pi install git:github.com/Wade11s/pi-speed # from a git repo
pi install -l npm:pi-stepfun               # project-level (.pi/settings.json)
pi -e npm:pi-stepfun                       # try once, without saving

pi list                                    # list installed packages
pi update npm:pi-stepfun                   # update
pi remove npm:pi-stepfun                   # uninstall
```

## Contributing

Issues and PRs belong on the individual extension's repository, not here. This repo only
maintains this README.

## License

[MIT](./LICENSE) © 2026 Wade Huang
