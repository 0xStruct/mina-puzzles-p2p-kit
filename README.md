# 🧩 mina-puzzles P2P Kit ⚔️🕹️

This is a general purpose P2P Kit (abstracted out of 🧩 Mina-puzzles).

It offers a ready-to-use scaffold to facilitate peer-to-peer recursive proofs session over websocket to create puzzles/games or other imaginable things.

With powerful Mina recursive proofs, zero-knowledge proofs are done totally off-chain on client side assuring privacy, offering better UX.

## Powered by

- Mina o1js
- Next.js
- Websocket, powered by Ably
- Redis KV storage, powered by Vercel

## How to use the kit

First set `.env`

```zsh
cp .env.example .env
```

```zsh
npm install

# run nextjs in dev mode
npm run dev
```