# try-puppeteer

### Puppeteer
https://github.com/GoogleChrome/puppeteer

### 環境準備

```bash
docker-compose build
```

### packageインストール

```
docker-compose run --rm api npm install
```

### puppeteer実行

ここにキャプチャ画像が生成されます<br>
https://github.com/tkabeee/try-puppeteer/tree/master/app/screenshot

```bash
docker-compose run --rm api node script.js
```

実行しているスクリプトファイルはこれ<br>
https://github.com/tkabeee/try-puppeteer/blob/master/app/script.js<br>

あとはご自由にどうぞー