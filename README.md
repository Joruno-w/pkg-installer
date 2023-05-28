# pkg-installer

[![NPM version](https://img.shields.io/npm/v/pkg-installer?color=a1b858&label=)](https://www.npmjs.com/package/pkg-installer)

Install package programmatically. Detect package managers automatically (npm, yarn, bun and pnpm).
## 🦄️ Usage

```bash
npm i pkg-installer
```

```ts
import { installPackage } from 'pkg-installer'

await installPackage('vite', { silent: true })
```
## License

[MIT](./LICENSE) License © 2023 [Joruno-w](https://github.com/Joruno-w)
