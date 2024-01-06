# kurukuru

```shell
pnpm add kurukuru
npm install kurukuru
yarn add kurukuru
```

stdout へクルクルスピン出力

Crucial spin output to stdout

```js
import { spin, spinEnd } from 'kurukuru'

spin({ suffix: ' kurukuru' }) // ⠙ kurukuru
spin({ suffix: ' kurukuru' }) // ⠹ kurukuru
spin({ suffix: ' kurukuru' }) // ⠸ kurukuru
spin({ suffix: ' kurukuru' }) // ⠼ kurukuru

spinEnd() // return cursor
```
