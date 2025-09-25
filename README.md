# Day08 — Currency Converter / 為替レート変換アプリ

A simple **currency converter web app** built with JavaScript.  
JavaScript で作成したシンプルな **為替レート変換アプリ** です。

👉 [Live Demo on GitHub Pages](https://YOUR-USERNAME.github.io/app-008-currency-converter/)

---

## Features / 機能
- Convert between major currencies (JPY, USD, EUR, GBP, etc.)  
  主要通貨間（JPY, USD, EUR, GBP など）の換算  
- **Swap** From ↔ To  
  通貨の入れ替え（From と To をスワップ）  
- **Favorites**: pin frequently used currencies  
  よく使う通貨をお気に入りに保存  
- **History**: recent 10 conversions stored locally  
  直近10件の換算履歴をローカル保存  
- **1-hour cache** for API results  
  レートは1時間キャッシュして高速化  

---

## How to Use / 使い方
1. Get a free API key from [ExchangeRate-API](https://www.exchangerate-api.com/)  
   [ExchangeRate-API](https://www.exchangerate-api.com/) で無料APIキーを取得  
2. Open `index.html` and replace `YOUR_API_KEY_HERE` with your key  
   `index.html` 内の `YOUR_API_KEY_HERE` を自分のキーに置き換え  
3. Open the file in your browser or deploy via GitHub Pages  
   ファイルをブラウザで開く、または GitHub Pages で公開  

---

## Notes / 注意
- For **learning use only**. Free API plan has limits and no commercial use.  
  **学習用途限定**。無料プランには制限があり、商用利用は不可です。  
- API key is visible in the client code. For production, use a server-side proxy.  
  APIキーはクライアントコードに表示されます。実運用ではサーバ側で管理してください。  

---

## License
MIT
