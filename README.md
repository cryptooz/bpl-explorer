<p align="center">
    <img src="/BPLexplorer.png" />
</p>

# BPL Explorer 3.0

> Designed and developed from the ground-up, using lean & fast developmental frameworks (Tailwind CSS & Vue.JS).

You can access it at [https://bplexp.cryptooz.com/](https://bplexp.cryptooz.com/).

## Build Setup

### 1. Clone the repository

```bash
git clone https://github.com/cryptooz/bpl-explorer
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Build for Production

#### 3.1 Mainnet

```bash
npm build:mainnet
```

#### 3.2 Devnet

```bash
npm build:devnet
```

#### 3.3 Custom

```bash
npm build --network my-custom-network
```

#### 3.4 GitHub Pages

If you are going to host your explorer instance on GitHub Pages you will need to specify your base url in most cases as GitHub Pages serves repositories from sub-directories instead of sub-domains.

```bash
npm build --base https://username.github.io/repository/
```

> This step is not required if you are hosting the explorer on your "root" repository which is usually your username https://username.github.io/.

## 4. History Mode

If you wish to remove the `/#/` from your URLs you can follow those steps https://router.vuejs.org/en/essentials/history-mode.html.

### 4.1 Build

```bash
yarn build:mainnet --history
```

### 4.2 Development

```bash
yarn dev --env.routerMode=history
```

> Keep in mind that this requires you to run your own server and a running instance of nginx.

## 5. Development

#### Mainnet

```bash
yarn dev # or yarn dev:mainnet
```

#### Devnet

```bash
yarn dev:devnet
```

#### Custom

```bash
yarn dev --env.network=custom
```

#### Change Router Mode

```bash
yarn dev --env.routerMode=history
```

## 6. Testing

``` bash
$ yarn test
```

## 7. Security

If you discover a security vulnerability within this package, please send an e-mail to security@ark.io. All security vulnerabilities will be promptly addressed.

## 8. Contributing

* If you find any bugs, submit an [issue](../../issues) or open a [pull-request](../../pulls), helping us catch and fix them.

## 9. Credits

- [Brian Faust](https://github.com/faustbrian)
- [Lúcio Rubens](https://github.com/luciorubeens)
- [Alex Barnsley](https://github.com/alexbarnsley)
- [All Contributors](../../contributors)
- [ARK DEVS]

## 10. License

[MIT](LICENSE) © [BlockPool](https://blockpool.io)
