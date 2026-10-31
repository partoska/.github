<p align="center">
  <img src="https://avatars.githubusercontent.com/u/274914647?v=4" width="120" alt="Partoska Laboratory logo">
</p>

<h1 align="center">Partoska Laboratory</h1>

<p align="center">
  <strong>Making software as enjoyable as life itself!</strong><br>
  From event media platforms to development libraries, we always create software that puts user experience first.
</p>

<p align="center">
  <a href="https://lab.partoska.com">Website</a> ·
  <a href="https://www.partoska.com">Partoska.com</a> ·
  <a href="mailto:ask@partoska.com">ask@partoska.com</a>
</p>

---

## Open Source

Small, dependency-light tools written in plain C. They run on macOS, Linux, and Windows where noted, and each one ships with an agent skill for AI coding assistants.

| Project | Description | Platforms |
| ------- | ----------- | --------- |
| [**Daemon Pal**](https://github.com/partoska/dpal) (`dpal`) | A compact process supervisor. Start, stop, restart, and persist long-running processes from one small binary, with INI configuration, log rotation, and automatic restarts. | macOS, Linux |
| [**Bikini**](https://github.com/partoska/bikini) (`bikini`, `libbikini`) | A minimal INI query tool and C99 library. Read, list, merge, and edit INI files from shell scripts without `sed` or `awk`. | macOS, Linux, Windows |
| [**p6a**](https://github.com/partoska/p6a-cmd) | The Partoska command-line interface. Manage events, sync and upload photos, and get invite links and QR codes from your terminal. | macOS, Linux, Windows |
| [**Partoska Agent Skills**](https://github.com/partoska/p6a-skills) | Bring Partoska to your AI agent. A Claude Code and Codex plugin for managing event photos through the Partoska MCP server. | Any agent |

## Install

**Homebrew** (macOS, Linux) — [`partoska/homebrew-tap`](https://github.com/partoska/homebrew-tap)

```bash
brew install partoska/tap/dpal
brew install partoska/tap/bikini
brew install partoska/tap/p6a
```

**Scoop** (Windows) — [`partoska/scoop-bucket`](https://github.com/partoska/scoop-bucket)

```powershell
scoop bucket add partoska https://github.com/partoska/scoop-bucket
scoop install partoska/bikini
scoop install partoska/p6a
```

**npm** (macOS, Linux, Windows)

```bash
npm install -g @partoska/dpal
npm install -g @partoska/bikini
npm install -g @partoska/p6a
```

Every GitHub release also ships `.pkg`, `.deb`, `.rpm`, and Windows installers,
archives, bare binaries, and a `SHA256SUMS` file.

**Agent skills** (Claude Code, Codex, Cursor, and others)

```bash
npx skills add partoska/dpal
npx skills add partoska/bikini
npx skills add partoska/p6a-cmd@p6a -g
npx skills add partoska/p6a-skills
```

## Products

- **[Partoska.com](https://www.partoska.com)**: capture important moments
  together. Create events and easily shareable photo albums for your guests.
- **Web Maintenance**: keep your website up to date and secure with our
  maintenance services.

## Contact

Questions, ideas, or bug reports are welcome. Open an issue in the relevant
repository, or write to us at [ask@partoska.com](mailto:ask@partoska.com).

<sub>Partoska Laboratory · Prague, Czech Republic · <a href="https://lab.partoska.com">lab.partoska.com</a></sub>
