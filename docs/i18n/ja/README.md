# 枯山水アーキテクチャ

<p align="center">
  <img src="https://assets.nullvariant.com/karesansui-architecture/images/karesansui.webp" alt="デジタル枯山水" width="600">
</p>

*ソフトウェアプロジェクトのための設計思想*

> **枯山水**（かれさんすい）は、砂と石で山水を表現する日本庭園の様式です。
> この思想は効率追求のミニマリズムではありません。シンプルに見えるものに深く投資します。

---

## 石を置く

庭師は問います。

「この石はなぜここにあるのか？」

答えられない石は、置くべきではありません。

あなたのソフトウェアという庭も、同じ問いに直面しています。

---

## 核心

どのプロジェクトにも、その存在理由となる核心があります。

それは驚くほど小さいかもしれません。100行で書けるかもしれません。

だからこそ、残りのすべてを「どのように置くか」に費やすことができるのです。

---

## 石

動きません。庭の中心です。

コア機能。それがなければプロジェクトではなくなるもの。

これが石です。他のすべては、この石を輝かせるために存在します。

---

## 砂紋

石の周りに描かれた波紋です。

石そのものではありませんが、石を石たらしめるもの。

90%のテストカバレッジ。構造化されたログ。タイムアウト処理。入力バリデーション。

砂紋は気づかれません。しかし砂紋のない庭は、ただの荒れ地です。

---

## 点景

庭に物語を与える小さな存在です。灯籠や苔のように、なくても庭は成立するが、あれば庭に個性が生まれるもの。

多言語対応。アイコン。追加機能の連携。

点景がなくても庭は存在できます。しかし点景があれば、庭は「誰かの庭」になります。

---

## 置かない石

最も重要な決断は、何を置かないかです。

外部API統合。認証ウィザード。設定の自動検出。

便利かもしれません。しかし置いた瞬間、それは別の庭になります。

枯山水の本質は、余白にあります。

---

## なぜ小さな庭なのか

自然界はなぜ美しいのでしょうか。

それは、壊れながら成立するように設計されているからかもしれません。

自然界には、すべてを支配する中心がありません。同期は弱く、最終的に整合すればよしとします。ルールは局所的で、環境ごとに異なります。

そして落ちる個体は、自然に落ちます。

人間社会は違う道を選びました。「落ちる個体を落とさないようにする」。この瞬間から、システムは必ず重くなります。

救済のための結合。公平のための一律ルール。予測のための標準化。どれも尊い意図から始まりましたが、工学的には依存の増加、退出の困難、割り込みの地獄を生みます。

始めることは簡単です。畳むときに、本当の重さがわかります。

だから私は、小さな庭を選びます。

疎結合で、可逆で、自己完結していて、いつでも終われるもの。

小さな命が一生を終えるように、ごくシンプルな機能を、ただ豊かに表現する。

それが、この庭です。

---

## 過剰について

「やりすぎだ」と言われます。

その通りです。

しかし趣味の庭にROIを問う者はいません。

カバレッジバッジを並べるのは、額縁に絵を飾るようなものです。美しいから、そこにあります。

---

## これは何ではないか

枯山水は西洋のミニマリズムではありません。

西洋のミニマリズムは問います：「何を削れるか？」
枯山水は問います：「何が残るに値するか？」

西洋のミニマリズムはコストと労力を節約するために削ります。
枯山水はシンプルに「見せる」ために莫大な投資をします。

本物の枯山水では、砂紋は毎日描き直されます。楽に見えるものほど、最も労力を要します。

「無駄を省け」では本質を見失います。「動けばいい」の居場所はここにはありません。

この庭では、砂紋と点景こそが豊かさです——削るべき無駄ではありません。

枯山水は、ミニマルに「見える」意図的な豊かさです。

---

## 作務

誰も訪れない庭を、なぜ手入れするのでしょうか。

静かに座ることで静寂を見出す者もいます。
行為の中に——集中し、急がず、没頭して——静寂を見出す者もいます。

これを**作務**（さむ）といいます。禅寺で行われる、瞑想としての作業です。
結果を得るための作業ではありません。プロセスそのものが目的の作業です。

庭師は完璧を作ろうと力みません。
庭師は手入れをします。戻ってきます。また手入れをします。

砂紋を描くことは、残されたパターンのためではありません。
明日、そのパターンはまた描き直されます。
これは徒労ではありません。これが要点です。

テストは数字に到達するために書くのではありません。
ドキュメントは読者のために作るのではありません。
コードと向き合い、理解を深める行為そのものに意味があります。

手入れすること、それ自体が修行です。

ゴールはありません。
求める拍手もありません。

手入れするという行為——静かに、着実に、ここに——
それ自体が報酬です。

---

## 起源

2003年。[CSS Zen Garden](http://www.csszengarden.com/)。

ひとつのHTMLを変えずに、CSSだけで無限のデザインを表現するプロジェクトがありました。

制約の中にこそ自由があります。

あの庭で学んだことが、この庭の種子となりました。

---

## 終章

枯山水アーキテクチャはオープンソースの仮面をかぶったアートです。

ユーザーにとっては、ツールとして機能します。
作り手にとっては、庭として存在します。

どちらも真実です。どちらも本物です。

だから庭師は満足しています。

---

## バッジ

この思想に共感したなら、あなたのプロジェクトで以下のバッジを使ってください：

[doc-url]: https://github.com/nullvariant/karesansui-architecture

### 石 (🪨)

| プレビュー | Markdown |
|---------|----------|
| [![Karesansui](https://img.shields.io/badge/🪨_Karesansui-Architecture-lightgrey)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🪨_Karesansui-Architecture-lightgrey)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🪨_Karesansui-Architecture-555)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🪨_Karesansui-Architecture-555)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🪨_Karesansui-Architecture-e8dcc8)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🪨_Karesansui-Architecture-e8dcc8)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🪨_Karesansui-Architecture-333)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🪨_Karesansui-Architecture-333)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🪨_Karesansui-Architecture-4a5568)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🪨_Karesansui-Architecture-4a5568)](https://github.com/nullvariant/karesansui-architecture)` |

### 禅 (🧘)

| プレビュー | Markdown |
|---------|----------|
| [![Karesansui](https://img.shields.io/badge/🧘_Karesansui-Architecture-lightgrey)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🧘_Karesansui-Architecture-lightgrey)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🧘_Karesansui-Architecture-555)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🧘_Karesansui-Architecture-555)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🧘_Karesansui-Architecture-e8dcc8)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🧘_Karesansui-Architecture-e8dcc8)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🧘_Karesansui-Architecture-333)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🧘_Karesansui-Architecture-333)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🧘_Karesansui-Architecture-4a5568)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🧘_Karesansui-Architecture-4a5568)](https://github.com/nullvariant/karesansui-architecture)` |

### 波 (🌊)

| プレビュー | Markdown |
|---------|----------|
| [![Karesansui](https://img.shields.io/badge/🌊_Karesansui-Architecture-lightgrey)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🌊_Karesansui-Architecture-lightgrey)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🌊_Karesansui-Architecture-555)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🌊_Karesansui-Architecture-555)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🌊_Karesansui-Architecture-e8dcc8)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🌊_Karesansui-Architecture-e8dcc8)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🌊_Karesansui-Architecture-333)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🌊_Karesansui-Architecture-333)](https://github.com/nullvariant/karesansui-architecture)` |
| [![Karesansui](https://img.shields.io/badge/🌊_Karesansui-Architecture-4a5568)][doc-url] | `[![Karesansui](https://img.shields.io/badge/🌊_Karesansui-Architecture-4a5568)](https://github.com/nullvariant/karesansui-architecture)` |

---

## 採用プロジェクト

この思想を採用しているプロジェクト：

- [Git ID Switcher](https://github.com/nullvariant/nullvariant-vscode-extensions/tree/main/extensions/git-id-switcher) - 最初の庭

---

## ライセンス

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

この思想は自由に共有し、改変できます。出典を明記してください。
