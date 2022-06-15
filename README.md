# sample-nextjs-basic-auth-password

## Demo

https://nextjs-basic-auth-password.vercel.app/

Login credentials:

- Username: `4dmin`
- Password: `testpwd123`

### Clone and Deploy

[`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app)を実行するか、本リポジトリをクローンする。

```bash
npx create-next-app --example https://github.com/vercel/examples/tree/main/edge-functions/basic-auth-password basic-auth-password
# or
yarn create next-app --example https://github.com/vercel/examples/tree/main/edge-functions/basic-auth-password basic-auth-password
```

development serverを起動

```bash
npm install
npm run dev

# or

yarn
yarn dev
```

## 参考リンク
公式ドキュメント: Middleware

https://nextjs.org/docs/advanced-features/middleware

公式Example

https://github.com/vercel/examples/tree/main/edge-functions/basic-auth-password
