# @ichiql/spin

```shell
pnpm add @ichiql/spin
npm install @ichiql/spin
yarn add @ichiql/spin
```

stdout へクルクルスピン出力

Crucial spin output to stdout

```js
import { spin, spinEnd } from '@ichiql/spin'

spin({ suffix: ' kurukuru' }) // ⠙ kurukuru
spin({ suffix: ' kurukuru' }) // ⠹ kurukuru
spin({ suffix: ' kurukuru' }) // ⠸ kurukuru
spin({ suffix: ' kurukuru' }) // ⠼ kurukuru

spinEnd() // return cursor
```
