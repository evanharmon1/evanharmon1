<!--
  evanharmon1 profile README
  Layout: minimal — sparse prose, badges, and two auto-updated sections:
  a GitHub stats card (github-metrics.svg) and the blog feed.
  Two GitHub Actions keep them fresh — see .github/workflows/.
-->

[evanharmon.com](https://evanharmon.com) &nbsp;·&nbsp; [ponderous.dev](https://ponderous.dev) &nbsp;·&nbsp; [sommerlawn.com](https://sommerlawn.com) &nbsp;·&nbsp; [kctechenthusiasts.com](https://kctechenthusiasts.com) &nbsp;·&nbsp; [lawnomator.com](https://lawnomator.com)

![evanharmon.com](https://img.shields.io/website?url=https%3A%2F%2Fevanharmon.com&label=evanharmon.com&up_message=online&down_message=offline&style=flat)
![ponderous.dev](https://img.shields.io/website?url=https%3A%2F%2Fponderous.dev&label=ponderous.dev&up_message=online&down_message=offline&style=flat)
![sommerlawn.com](https://img.shields.io/website?url=https%3A%2F%2Fsommerlawn.com&label=sommerlawn&up_message=online&down_message=offline&style=flat)
![kctechenthusiasts.com](https://img.shields.io/website?url=https%3A%2F%2Fkctechenthusiasts.com&label=kc%20tech%20enthusiasts&up_message=online&down_message=offline&style=flat)
![lawnomator.com](https://img.shields.io/website?url=https%3A%2F%2Flawnomator.com&label=lawnomator&up_message=online&down_message=offline&style=flat)

---

### 🧰 My setup

My coding environment is [Ghostty](https://ghostty.org) and VS Code running [zsh](https://www.zsh.org) + [Oh My Zsh](https://ohmyz.sh) with a
[Starship](https://starship.rs) prompt and [tmux](https://github.com/tmux/tmux/wiki). Everything is installed with
[Homebrew](https://brew.sh) and [my dotfiles](https://github.com/evanharmon1/harmon-dotfiles) are templated and synced across machines with
[chezmoi](https://www.chezmoi.io) (so `.zshrc`, Ghostty, Starship, git, etc. are one `chezmoi apply` away).
I do most of my coding in self-hosted dev containers provisioned with [Coder](https://coder.com),
which act as always-on remote environments for myself and agentic AI tools like [Claude](https://www.anthropic.com/claude-code), [Codex](https://github.com/openai/codex), and [agent-deck](https://github.com/asheshgoplani/agent-deck) so they can be run collaboratively or autonomously.
I make extensive use of the [go-task](https://taskfile.dev) (`Taskfile.yml`) task runner for AI and human use. I think and take notes in [Obsidian](https://obsidian.md) which you can see here - [Memex](https://evanharmon.com/memex).

**Languages:**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat&logo=gnubash&logoColor=white)

**Frameworks & runtime:**
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat&logo=astro&logoColor=white)
![TanStack](https://img.shields.io/badge/TanStack-FF4154?style=flat&logo=reactquery&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-EE342F?style=flat&logo=convex&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat&logo=pnpm&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white)

**Terminal & tooling:**
![Ghostty](https://img.shields.io/badge/Ghostty-1C1C1C?style=flat&logo=ghostty&logoColor=white)
![chezmoi](https://img.shields.io/badge/chezmoi-2088FF?style=flat&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMjE5IDk5OSI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTYzNCAyNWwyNDQgMjA2IDI0NSAyMDUgOTEgNzcgLTExOSAwIC0xNTMgMCAwIDI1OGM5OCwyMyAxOTIsNjAgMjc5LDEwOCAtMTkxLC01NCAtNDAxLC03NSAtNjE4LC01NCAtMjE4LDIxIC00MjAsODIgLTU5NywxNzIgODEsLTY4IDE3MSwtMTI1IDI3MCwtMTY3IC0yLDEgLTQsMiAtNiwybDAgLTMxOSAtMTUzIDAgLTExOSAwIDkxIC03NyAyNDUgLTIwNSAyNDQgLTIwNiAyOCAtMjMgMjggMjN6bTMwOCA3NDZjLTMsLTEgLTYsLTIgLTksLTIgMywwIDYsMSA5LDJ6bS0xMCAtM2MtMywwIC02LC0xIC05LC0yIDMsMSA2LDIgOSwyem0tMTAgLTJjLTMsMCAtNiwtMSAtOSwtMiAzLDEgNiwyIDksMnptLTEwIC0yYy0zLDAgLTYsLTEgLTgsLTEgMiwwIDUsMSA4LDF6bS0xMSAtMmMtMiwwIC01LC0xIC03LC0xIDIsMCA1LDEgNywxem0tOSAtMmMtMywwIC01LC0xIC04LC0xIDMsMCA1LDEgOCwxem0tMTEgLTJjLTIsMCAtNCwwIC03LC0xIDMsMSA1LDEgNywxem0tMTAgLTFjLTIsLTEgLTQsLTEgLTYsLTEgMiwwIDQsMCA2LDF6bS0xMCAtMmMtMiwwIC00LC0xIC02LC0xbDAgLTE0MCAwIC0xMDEgMCAtODcgMTIxIDAgLTE1NCAtMTI5IC0yMTYgLTE4MiAtMjE3IDE4MiAtMTUzIDEyOSAxMjEgMCAwIDg3IDAgMTAxIDAgMTg1IDAgMGM3NiwtMjYgMTU1LC00MyAyMzgsLTUxIDkwLC05IDE3OSwtNiAyNjYsN3ptLTU0OSA2MGMtMSwxIC0zLDEgLTQsMiAxLC0xIDMsLTEgNCwtMnptLTkgNGMtMSwwIC0zLDEgLTUsMSAyLDAgNCwtMSA1LC0xem0tOSAzYy0yLDEgLTQsMiAtNiwzIDIsLTEgNCwtMiA2LC0zem0tOSA0Yy0yLDEgLTQsMiAtNiwyIDIsMCA0LC0xIDYsLTJ6Ii8+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTUzMiA0NDVjMCwtNDAgMzMsLTczIDc0LC03MyA0MCwwIDczLDMzIDczLDczIDAsMjggLTE0LDUyIC0zNiw2NGw3IDEzIDQ1IDc3IC04OSAwIC04OSAwIDQ1IC03NyA3IC0xM2MtMjIsLTEyIC0zNywtMzYgLTM3LC02NHoiLz48L3N2Zz4=)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=vscodium&logoColor=white)
![zsh](https://img.shields.io/badge/zsh-F15A24?style=flat&logo=zsh&logoColor=white)
![Starship](https://img.shields.io/badge/Starship-DD0B78?style=flat&logo=starship&logoColor=white)
![Homebrew](https://img.shields.io/badge/Homebrew-FBB040?style=flat&logo=homebrew&logoColor=black)
![tmux](https://img.shields.io/badge/tmux-1BB91F?style=flat&logo=tmux&logoColor=white)
![1Password](https://img.shields.io/badge/1Password-0094F5?style=flat&logo=1password&logoColor=white)

**Infra & cloud:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?style=flat&logo=hetzner&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat&logo=digitalocean&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)

---

### 📊 Stats

<!--
  Rendered by .github/workflows/metrics.yml (lowlighter/metrics) into a static,
  committed SVG — github-metrics.svg — regenerated daily. A committed file served
  by GitHub can't be rate-limited or paused like the old
  github-readme-stats.vercel.app cards were. Tune the language filters, template,
  and plugins in that workflow. Java/HTML and a few legacy repos are excluded so
  the language breakdown reflects the current stack.
-->
<p align="center">
  <img src="./github-metrics.svg" alt="Evan Harmon's GitHub metrics" />
</p>

---

### 🧱 Harmon Platform

My custom development platform with machine configuration, DevOps systems, homelab infrastructure, and automation repos that work together to help me develop software and manage my homelab:

| Repo | What it is |
| --- | --- |
| [**harmon-init**](https://github.com/evanharmon1/harmon-init) | Template repo that automatically bootstraps & standardizes new repos (CI/CD, devcontainers, AI steering, tooling). |
| [**harmon-devkit**](https://github.com/evanharmon1/harmon-devkit) | Reusable boilerplates & code templates, standalone scripts, and AI assets (skills, prompts, agents). |
| [**harmon-dotfiles**](https://github.com/evanharmon1/harmon-dotfiles) | Shell & app dotfiles (zshrc, git config, shell aliases, etc.), managed declaratively with chezmoi. |
| [**harmon-ops**](https://github.com/evanharmon1/harmon-ops) | Personal machine bootstrapping, package management & dev-environment setup across macOS/Windows/Linux. |
| **harmon-infra** | Homelab infrastructure as code — Terraform, Ansible, and Docker Compose services. |

---

### ✍️ From my blog

Latest posts from [evanharmon.com](https://evanharmon.com/blog) (auto-updated):

<!-- BLOG-POST-LIST:START -->
- [KC Tech Enthusiasts - Agentic AI Design Patterns with Claude Code](https://evanharmon.com/blog/kcte-claude-code-agentic-ai-design-patterns)
- [KC Tech Enthusiasts - AI Platforms](https://evanharmon.com/blog/kcte-ai-platforms)
- [The Phoenix Project Book Summary](https://evanharmon.com/blog/book-summary-phoenix-project)
- [How to setup git to use a different git commit identity based on the repo&#39;s directory](https://evanharmon.com/blog/how-to-setup-git-to-use-a-different-git-commit-identity-based-on-the-repos-directory)
<!-- BLOG-POST-LIST:END -->

---

<sub>📍 Kansas City, MO</sub>
