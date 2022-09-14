# 英語ニュースサイトから記事情報を取得
記事情報のテキスト全文やキーワードやサマリーを表示

<br>

## 対象記事
![画像1](./Newspaper-Exercises1-1.png)

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
![画像2](./Newspaper-Exercises1-2.png)

<br>

## 対象記事の作成者
```
article.authors
```
![画像3](./Newspaper-Exercises1-3.png)

<br>

## 対象記事の全文
```
article.text
```
![画像4](./Newspaper-Exercises1-4.png)

<br>

## ライブラリのインポート
```
import nltk
nltk.download('punkt')
```
![画像5](./Newspaper-Exercises1-5.png)

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
![画像6](./Newspaper-Exercises1-6.png)

<br>

## 対象記事のサマリー
```
article.summary
```
![画像7](./Newspaper-Exercises1-7.png)

<br>
