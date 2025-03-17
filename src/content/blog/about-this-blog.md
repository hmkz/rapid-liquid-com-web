---
title: 'AIで開発したサイト'
pubDate: 'March 18 2025'
description: 'このサイトはCursorで作成しました。'
heroImage: '/blog-placeholder-3.jpg'
---

### AIで開発したサイト

このブログを含めたサイト全体はCursorで作成しました。
モデルはCluade-3.7-Sonnetです。スタックとしては以下のような感じです。

- Next.jsで構築
- Markdownでコンテンツを管理
- SSG（Static Site Generation）で高速表示
- Cloudflare pagesでホスティング

### プロンプト

以下の感じのプロンプトで指示しています。

これでここまでできるのならばかなりすごいことですね。

```
個人事業のポータルサイトを作成します。ドメインはrapid-liquid.comでRapid Liquidという名前です。
事実上何もしていないのでページ構成としてはTopページはサイト名をデザイン性高く表示してください。 
/blogでブログを運営します。next.jsでSSGとして運用できるようにしてください。blogはmarkdownで書けるようにしてください
TOPページはサイトロゴとブログへのパス以外は削除してください
ロゴのフォントをFuturaに、日本語のフォントをM PLUS 1pに変更して下さい
```

### .cusorruleからUserRulesへの移行

プロジェクト単位の指示は.cursorrulesを利用していましたが、DeprecatedとのことなのでUserRulesに徐々に移行していきたいです。
