<!-- .slide: data-background="#FEF5E4" -->

# OSS開発風 学習スタイル

## 実践的プログラミング

---

<!-- .slide: data-background="#FEF5E4" -->
## OSS (Open Source Software)

インターネットを通じて、ソースコードを公開し、誰でも無償で自由に使用、複製、改変、再配布、自ら開発したプログラムへの組み込みが行えるようなソフトウェア。


---

<!-- .slide: data-background="#FEF5E4" -->
## OSS定義(1)

- ソフトウェアを自由に販売したり無料で配布したりできること
- ソースコードを入手できること
- ソースコードを改良したり派生ソフトウェアを作成したりできること
- 作者のソースコードの完全性を維持すること
- 個人やグループを差別しないこと

----

<!-- .slide: data-background="#FEF5E4" -->
## OSS定義(2)

- 利用分野に対して差別しないこと
- 再配布するときに追加ライセンスを必要としないこと
- ライセンスは特定の製品に依存しないこと
- 一緒に配布される他のソフトウェアを制限しないこと
- 技術的に中立であること


---

<!-- .slide: data-background="#FEF5E4" -->
## OSS開発の流れ

![](https://i.imgur.com/j4XWN01.png)
![](https://i.imgur.com/8KHLrRr.png)


---

<!-- .slide: data-background="#FEF5E4" -->
## 旧OSS開発コミュニケーション

```
プロジェクトによって手段・ルールが異なる
```

- メーリングリスト
- IRC
- インスタントメッセージ

---

## 旧OSS開発ソースコード管理

<!-- .slide: data-background="#FEF5E4" -->

```
プロジェクトによって手段が異なる
結果、数人の管理者しかソースコードを管理ができない
```

- サーバで直接ファイル管理
- 集中型バージョン管理システム(Subversion)

---

<!-- .slide: data-background="#FEF5E4" -->
## SVN

```
集中型は、リポジトリが単一のため中途半端であったり、
問題があるかもしれないコードはマージされない。
```

![](https://i.imgur.com/romH3ZV.jpg)


---

## Git

<!-- .slide: data-background="#FEF5E4" -->

```
個々人でリポジトリを持つことができ、
ローカル内で気軽に同じ環境で変更を加えることができる。
```

![](https://i.imgur.com/OCh372h.jpg)


---

<!-- .slide: data-background="#FEF5E4" -->
## GitHub

![](https://i.imgur.com/z4WvEj8.png =250x100)


- Gitを利用したリポジトリホスティングサービス
- 誰でも気軽にソースコードを公開できる
- 機能の修正・変更を行う手段を提供(Pull Request)
- 用途毎にコミュニケーション手段を提供
  - Issue(問題・機能追加の報告に関する掲示板)
  - Gitter(エンジニアコミュニティ向けチャット)
  - Project(タスク管理)


---

<!-- .slide: data-background="#FEF5E4" -->
## 自動テスト

- 公開されたプログラムは、どのような機能を持ち、どのような挙動をするか 十分テストされていれば、ユーザがそれを使うかどうかの判断材料となる。

- 人間が手ではなく、プログラムによって書いたテストのことを**テストコード**と呼び、それによってテストを行うことを**自動テスト**と呼ぶ


---

<!-- .slide: data-background="#FEF5E4" -->
## Continuous Integration

- CI ... Continuous Integration
  - 日本語: 継続的インテグレーション
- 主にプログラマのアプリケーション作成時の*品質改善*や*納期短縮*のための習慣のこと
- 狭義には*ビルド*や*テスト*、*インスペクション*などを継続的に実行していくことを意味する


---

<!-- .slide: data-background="#FEF5E4" -->
## OSS開発風 学習スタイル

![](https://i.imgur.com/PNMqScG.png)







