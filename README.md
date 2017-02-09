# WordPressのプラグインなどを日本語に翻訳するための用語集

WordPressのプラグインなどを日本語に翻訳するための用語集ファイルです。繰り返しプラグインやテーマなどを翻訳する場合に便利に利用できるように整備していきます。

特定のプラグインに固有の語は掲載せず、一般的な言葉を追加していくことを想定しています。

## ファイル形式

拡張子は`.txt`とします。タブ区切りの3カラムのリストで、左側から、

1. 原文（英語）
2. 訳文（日本語）
3. コメント

となります。

```
taxonomy	タクソノミー	例外で長音付き
"Sorry	"		※この部分は翻訳しません。
role	権限グループ
RSS	RSS
```

上の例では、原文（原語）である`taxonomy`に対して、`タクソノミー`という訳文（訳語）が充てられて、`例外で長音付き`というコメントが添えられています。2行目の`Sorry `に対しては訳語が無く、コメントがあります。コメントがない場合や英語と日本語で表記が同じものもあります。

## 最初のバージョンの出自

[WordPress.org にある用語集](https://translate.wordpress.org/projects/wp/dev/ja/default/glossary)をベースとしています。[WordPress.com](https://translate.wordpress.com/projects/wpcom/ja/default/glossary)から不要なものを除いて足しています。

## 利用方法

翻訳メモリや用語集をサポートするソフトウェアやサービスにインポートして利用してください。

- [OmegaT 取扱説明書 第19章 用語集 \(Glossaries\)](http://omegat.sourceforge.net/manual-latest/ja/chapter.glossaries.html)
- 
