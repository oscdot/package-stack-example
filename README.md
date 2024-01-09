## NPM PKG Stack Example

A simple and neat setup for a NPM Package

**Credit where credit is due:**
[Blazing Fast Tips: Publishing to NPM](https://www.youtube.com/watch?v=eh89VE3Mk5g)

## Learnings

- Make sure PR permissions is properly set up for actions in github settings
- `.npmrc` with `autoInstallPeers=true` set to true was necessary for pnpm install --frozen-lockfile to run
- `secrets.NPM_TOKEN` setup required for publish workflow to run
- Make sure `"access": "public" on publishConfig` is added
- If 2FA is setup on NPM account account in NPM, that you disable it for write actions
