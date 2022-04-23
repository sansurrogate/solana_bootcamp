# solana_bootcamp
solana bootcamp

## 環境構築
npmでプロジェクト構築&typescript関連のインストール
```sh
npm init
npm install typescript ts-node
npm install @types/node -D
```

solana-web3.jsのインストール
```sh
npm install @solana/web3.js
```

### solana関連の各種ツールインストール
[こちら](https://github.com/LearnWithArjun/solana-env-setup/blob/main/mac_or_linux_setup.md)を参考にした

1. rustのインストール ([参考](https://www.rust-lang.org/tools/install))
    ```sh
    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
    ```

1. solana toolのインストール ([参考](https://docs.solana.com/cli/install-solana-cli-tools))
    ```sh
    sh -c "$(curl -sSfL https://release.solana.com/v1.10.8/install)"
    ```
