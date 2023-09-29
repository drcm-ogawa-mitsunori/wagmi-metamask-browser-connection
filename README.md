# Wagmi Metamask Browser Connection

モバイル Metamask Browser にて [Wagmi](https://github.com/wagmi-dev/wagmi) を使って Metamask と接続するコードです。
`window.ethereum` の挿入タイミングが環境によって異なるが故に正しく MetamaskConnector を拾えてないという状況があり、それを検証し対策を練ります。

## 環境

- Node.js
  - `18.18.0`
- npm
  - `10.1.0`
- TypeScript
- React

## 開発

### サーバー起動

```
$ npm run dev
```
