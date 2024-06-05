# @nandordudas/tsconfig

> [!IMPORTANT]
> This package was originally created by [@total-typescript/tsconfig], [@total-typescript/ts-reset] and [@tsconfig/strictest].
> I have since customized it with my own work. Special thanks to the authors of these repositories for their hard work.

## Usage

- create new [personal access token] (PAT)
- log in with npm to your GitHub registry
  - set your username and PAT as password
  - `npm login --scope=@nandordudas --auth-type=legacy --registry=https://npm.pkg.github.com`
- check logged in user
  - `npm whoami --registry=https://npm.pkg.github.com`

```bash
npm install --global @antfu/ni
ni --save-dev @nandordudas/tsconfig
```

[@total-typescript/tsconfig]: https://github.com/total-typescript/tsconfig
[@total-typescript/ts-reset]: https://github.com/total-typescript/ts-reset
[@tsconfig/strictest]: https://github.com/total-typescript/strictest
[personal access token]: https://github.com/settings/tokens/new?description=Read%20GitHub%20packages&scopes=read:packages
