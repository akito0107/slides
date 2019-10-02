<!-- sectionTitle: はじめに -->

## はじめに

---

## 自己紹介

- 伊藤　瑛（いとう　あきと）
- @Akito0107 Twitter / Github
- TypeScript / Go をよく書いています
- メインはバックエンド
- blogやってます=> https://blog.akito0107.dev/

---

## TypeScript とわたし

- 一番最初に触り始めたのは使い始めたのは 2016 年ごろ
  - Node.js 製のサーバサイドアプリケーションの運用をしていた
  - Runtime Error に苦しめられる日々
  - 当時の TypeScript は Third Party 製のライブラリが充実しておらず、余計辛かったので使うのを諦める
- Flow に行ったりしたが、2018 年の春頃から本格的に TypeScript を触り始める
- TypeScript でツール・ライブラリを作るのが趣味
- ライブラリ屋？

---

## 今日伝えたいこと

- TypeScriptの型推論を活用すると、どういったAPIが実現できるのか
- 実例ベースで型のトリックとともにいくつか紹介します
- なにか 1 つでもヒントになれば幸いです！

---

## まえおき

- 型パズルがいくつか出てくる
- こういうこともできるよ、という話
- <strong>すべての TS のコードでこういったことをしよう、という話ではない</strong>

---

## TypeScriptでLibraryを書くメリットはなにか

- Libraryを書く人
    - 型に守られるため堅牢性/メンテナンス性/etcが上がる
- Libraryを使う人
    - (型が正しく提供されていれば)APIの仕様把握のコストが減る
    - IDEの補完による高いDX

### TSでしかできないようなDXを実現してみたい