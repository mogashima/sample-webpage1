# 企業サイトデモ

## 概要
本プロジェクトはIT系企業向けの企業紹介ページのデモです。
HTMLとSassで構築しており、レスポンシブ対応したシンプルな構成となっています。
フレームワークは使用せず、シンプルなコーディングを心がけています。

## 使用技術
- HTML5
- Sass（SCSS記法）
- JavaScript（Vanilla）
- レスポンシブデザイン

## セットアップ方法
1. Sassのコンパイル環境を用意します。  
   ```bash
   npm install
   ```

2. SCSSをCSSにコンパイルします。

    ```bash
    npm run sass
    ```
    開発中に変更を自動検知してコンパイルした場合は:watchを付けます。
    ```bash
    npm run sass:watch
    ```