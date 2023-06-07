This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
```

## Issue

Present when importing `'@ninetailed/experience.js'` in middleware.ts -

```
- error Error [TypeError]: labels.entries is not a function or its return value is not iterable
    at processing (evalmachine.<anonymous>:786:43)
    at Object.toASCII (evalmachine.<anonymous>:828:22)
    at domainToASCII (evalmachine.<anonymous>:1446:27)
    at parseHost (evalmachine.<anonymous>:1371:27)
    at URLStateMachine.parseHostName (evalmachine.<anonymous>:1761:22)
    at new URLStateMachine (evalmachine.<anonymous>:1534:48)
    at Object.module2.exports.basicURLParse (evalmachine.<anonymous>:2100:19)
    at new URLImpl (evalmachine.<anonymous>:2828:31)
    at Object.exports.setup (evalmachine.<anonymous>:3037:16)
    at new URL (evalmachine.<anonymous>:3091:26) {
  digest: undefined
}
```
