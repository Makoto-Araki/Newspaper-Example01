# 英語ニュースサイトから記事情報を取得
記事情報のテキスト全文やキーワードやサマリーを表示

<br>

## 対象記事
![画像1](./image01.png)

<br>

## 対象記事のURL指定
```
url = 'https://edition.cnn.com/2022/09/13/investing/premarket-stocks-trading'
article = Article(url)
```

<br>

## 対象記事のダウンロードと解析
```
article.download()
article.parse()
```

<br>

## 対象記事の発行日時
```
article.publish_date
```
![画像2](./image02.png)

<br>

## 対象記事の作成者
```
article.authors
```
![画像3](./image03.png)

<br>

## 対象記事の全文
```
article.text
```
![画像4](./image04.png)

<br>

## ライブラリのインポート
```
import nltk
nltk.download('punkt')
```
![画像5](./image05.png)

<br>

## 自然言語処理の実行
```
article.nlp()
```

<br>

## 対象記事のキーワード
```
article.keywords
```
![画像6](./image06.png)

<br>

## 対象記事のサマリー
```
article.summary
```
![画像7](./image07.png)

<br>
