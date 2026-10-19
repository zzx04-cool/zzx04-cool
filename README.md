# Hi, I'm Tsuki 👋

Into AI agents and the infrastructure underneath them — TypeScript / Python, open source.

## 🔨 Selected open-source contributions

- **[agentconnect](https://github.com/agentconnect-md/agentconnect)** — a multi-agent platform bridging IM to AI coding agents. Hardened the sandbox shim's Git exec policy: replaced the blanket `git config` admission with an exact managed-credential allowlist ([#2894](https://github.com/agentconnect-md/agentconnect/pull/2894), merged).
- **[evalscope](https://github.com/modelscope/evalscope)** — a streamlined framework for efficient LLM/VLM evaluation and benchmarking. Fixed Terminal-Bench Codex agent compatibility: skipped the unsupported `max_turns` parameter for Harbor 0.24.0's Codex schema ([#1846](https://github.com/modelscope/evalscope/pull/1846), merged).
- **[cherry-studio](https://github.com/CherryHQ/cherry-studio)** — an AI desktop assistant built with Electron and React. Fixed the translate language selector leaking raw language codes into its closed trigger: the display label now uses the flag and localized name, with the code kept for search filtering ([#21993](https://github.com/CherryHQ/cherry-studio/pull/21993), merged).
- **[KiroCrew](https://github.com/kirodotdev/KiroCrew)** — a self-improving persistent workspace for AI coding agents (Python). Fixed `prepare-pr`'s `--reviewers` pin silently disabling the unanswered CONCERNS gate: the pin-independent whole-design verdicts are now merged into the gate, so a design CONCERNS still blocks auto-merge ([#21808](https://github.com/kirodotdev/KiroCrew/pull/21808), merged).

## 📊 GitHub Stats

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=zzx04-cool&show_icons=true&theme=dark&hide_border=true" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zzx04-cool&layout=compact&theme=dark&hide_border=true" alt="Top languages" />
</p>

<!--
卡片的 theme=dark 与深色 IDE 习惯一致；想换亮色改成 theme=default。
-->
