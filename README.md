# Mnemonic Splitter

Split a mnemonic seed phrase (12, 15, 18, 21 or 24 words) into 3 shards. Any 2 of the 3 shards reconstruct the original phrase, using an overlapping-window scheme.

> Handle real seed phrases only on a trusted, offline machine. This project has not been independently audited.

## Features

- Split a phrase into 3 shards
- Recover the phrase from any 2 shards
- Multi-wallet and crypto helper tools

## Tech stack

React 19, Vite, Tailwind CSS 4, TypeScript

## Getting started

**Prerequisites:** Node.js 20 or newer.

```bash
npm install
npm run dev      # development server
npm run build    # production build in dist/
```

## Project structure

```text
components/   SplitTab, RecoverTab, ShareDisplay, MultiWallet, CryptoTools, CryptoUtils
types.ts
App.tsx
```
