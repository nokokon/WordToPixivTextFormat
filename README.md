# WordToPixivTextFormat

## 概要
Wordドキュメントをpixiv小説のテキストフォーマットに変換します。

## ライセンス
MIT License

## 留意事項
1. Wordドキュメントには加工を行いませんが、必ず「上書き保存」の上、実行してください。
2. 変換されたテキストデータ内容はクリップボードに保存されます。

## 動作環境
Microsoft(c) Word 2019, Microsoft(c) Word 365
※想定ではMicrosoft(c)  Word 2010以降で動作する設計です。

## 使用
1. ダウンロードした.basファイルを、VBEでインポートします。
2. 参照設定から「VBScript Regular Expressions 5.5」チェックします。
3. ToPixivTextFormat関数を実行します。

## 変換される機能
### セリフ段落
加工は行いません。

### 地の文段落
先頭に全角スペースを連結します。

### ルビ
pixivルビに変換します。

### 見出し 1　～　見出し 9スタイル段落
pixiv見出しに変換します。

### 表題、副題スタイル段落
加工は行いません。
