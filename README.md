# @penosext/miniapp-app-template

Private template for an independently versioned Miniapp application.

The application owns its pages, contract selection, mock APIs, app manifest, device ID, and verification workflow. It consumes capability packages by standard `@penosext/miniapp-*` names from GitHub Packages; it does not use workspace-relative source paths.

The template uses `private: true` and `license: UNLICENSED`. Do not copy third-party fonts, dictionary data, icons, or SDK files into a generated application without retaining their original permissions.

## Commands

```bash
pnpm install
pnpm generate
pnpm test
pnpm typecheck
pnpm build
```

Set `GITHUB_TOKEN` or `NODE_AUTH_TOKEN` with `read:packages` before `pnpm install`.
