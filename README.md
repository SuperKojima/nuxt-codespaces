# Nuxt on Bun

Nuxt.js学習の第一歩のための環境。

## Docs

- [Vue.js](https://ja.vuejs.org/)
- [Nuxt.js](https://nuxt.com/)
- [Nitro](https://nitro.unjs.io/guide)
- [h3](https://h3.unjs.io/guide)
- [Vite](https://ja.vite.dev/)
- [Tailwind CSS](https://tailwindcss.com/docs/aspect-ratio)
- [Bun](https://bun.sh/)

## Commands

```bash
# 開発サーバー起動
bun dev

# コーディングルールチェック
bun lint
bun lint:fix
```

もし型でエラー出てるけど絶対大丈夫だと思ったら以下を試すと良い。

```bash
rm -r .nuxt
bun postinstall
# cmd + shift + P
# -> Reload Window
```

## Modules

- [Nuxt ESLint](https://eslint.nuxt.com/)
- [Nuxt Tailwind](https://tailwindcss.nuxtjs.org/)
