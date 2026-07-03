# codex-plugins

Codex plugins by [Sukhrob Ilyosbekov](https://github.com/suxrobgm). Pre-bundled, no install step.

## Use

```bash
codex plugin marketplace add suxrobGM/codex-plugins
codex plugin add jobpilot@sukhrob-codex-plugins
```

Or browse in-session via the `/plugin` menu.

## Plugins

| Plugin | What it does | Source |
| --- | --- | --- |
| [`jobpilot`](./plugins/jobpilot) | Job-search agent - search boards, tailor resumes, auto-apply. Run `$setup` to install the local agent. | [suxrobgm/jobpilot](https://github.com/suxrobgm/jobpilot) |

## Update

```bash
codex plugin marketplace upgrade sukhrob-codex-plugins
```

## How this marketplace works

Plugins are vendored under [`plugins/`](./plugins) as pure Markdown/JSON skill packs - cloning the marketplace is enough, no runtime or install step. Each plugin's source lives in its own repository (see the table above); release artifacts are synced into this marketplace on each release tag.
