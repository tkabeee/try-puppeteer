# try-puppeteer

__Puppeteer__
https://github.com/GoogleChrome/puppeteer

### 環境準備

'''bash
docker-compose build
'''

### packageインストール

'''
docker-compose run --rm api npm install
'''

### puppeteer実行

ここにキャプチャ画像が生成されます
https://github.com/tkabeee/try-puppeteer/tree/master/app/screenshot

'''bash
docker-compose run --rm api node script.js
'''