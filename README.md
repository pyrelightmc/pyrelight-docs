# Pyrelight docs

Documentation for Pyrelight's Minecraft plugins, built with
[Mintlify](https://mintlify.com) and published at
**[pyrelight.mintlify.app](https://pyrelight.mintlify.app)**.

## Structure

One folder and one navigation tab per plugin:

```
rlogin/                     rLogin — authentication for Paper, Folia and Velocity
├── introduction.mdx
├── installation.mdx
├── quickstart.mdx
├── configuration/
├── features/
├── reference/
└── help/
```

Adding a plugin means creating its folder and appending a tab to
`navigation.tabs` in `docs.json`. Nothing existing has to move.

## Working locally

```bash
npm i -g mint
mint dev
```

Serves the site at `http://localhost:3000`. Run it from the repo root, next to
`docs.json`.

## Publishing

Pushing to `main` deploys automatically through the Mintlify GitHub app.

## Keeping it accurate

These pages describe real behaviour, not intended behaviour. When a plugin's
defaults, commands or config keys change, the docs change in the same release —
a setting documented here should be findable in that plugin's source.

| | |
|---|---|
| rLogin | [github.com/pyrelightmc/rlogin](https://github.com/pyrelightmc/rlogin) |
| Discord | [discord.gg/5tuSrNRk3a](https://discord.gg/5tuSrNRk3a) |
