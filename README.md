# 日本語訳にあたっての注意書き
この和訳は完全に個人の利用に閉じた範囲での利用を想定しています。  
また著者である、 [jorgef](https://github.com/jorgef) さんには公開に関して必要な事柄があれば教えてほしいという問い合わせをしている状況にあります。  
内容やライセンスから見ても個人の利用の範囲での訳をした上でこのような形で公開状態にするのはなんら違反的ではないという想定でこのような形で公開している状態です。

# 概要

フレームワークを利用することで、engineering managers は、各ポジションに期待されることや、キャリアラダーの次のレベルに到達するための計画について、メンバーと有意義な会話をすることができます。

フレームワークは、米国のテック企業ではある程度標準的な役割とレベルを使用していますが、すべての企業でそのまま利用できるわけではありません。ここにある情報をベースラインとして使用し必要に応じて柔軟に適用してください。

フレームワークは、レーダーチャートに大きく依存して、特定のポジションのさまざまな視点と期待を視覚的に示します。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="charts/template-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="charts/template.png">
  <img alt="Template Chart" src="charts/template.png">
</picture>

# キャリアラダー

フレームワークには、４つの異なるラダーがあります:

* [**開発者**](Developer.md): プログラマーまたはソフトウェアエンジニアとしても知られる役割には、深いレベルの技術的専門知識が必要です。
* [**テックリード**](TechLead.md): 開発リーダーとしても知られる役割は、システムのオーナーであり、実践的な開発、アーキテクチャの知識、およびプロダクトのサポートの間で絶妙なバランスを必要とします。
* [**テクニカルプログラムマネージャー**](TechnicalProgramManager.md): 複数のチームにまたがる意思決定を調整し、完了に導く責任を負う役割。
* [**エンジニアリングマネージャー**](EngineeringManager.md): 開発マネージャーとしても知られる役割は、持続的なデリバリ、キャリアの成長、チームの幸福度に責任を負います。

もしも [テックリード](TechLead.md) と [エンジニアマネージャー](EngineeringManager.md) の違いについてピンと来ていない場合には、 [テックリード vs エンジニアマネージャー](TechLead-EngineeringManager.md) のページに詳細な比較が書かれているので参照してほしい。

| Level | Seniority | [開発者](Developer.md) | [テックリード](TechLead.md) | [テクニカルプログラムマネージャー](TechnicalProgramManager.md) | [エンジニアリングマネージャー](EngineeringManager.md) |
| :---: | :---: | :---: | :---: | :---: |  :---: |
| 1 | No | [D1](Developer.md#d1---developer-1) | | | |
| 2 | No | [D2](Developer.md#d2---developer-2) | | | |
| 3 | No | [D3](Developer.md#d3---developer-3) | | | |
| 4 | Yes | [D4](Developer.md#d4---developer-4) | [TL4](TechLead.md#tl4---tech-lead-4) | [TPM4](TechnicalProgramManager.md#tpm4---technical-program-manager-4) | |
| 5 | Yes | [D5](Developer.md#d5---developer-5) | [TL5](TechLead.md#tl5---tech-lead-5) | [TPM5](TechnicalProgramManager.md#tpm5---technical-program-manager-5) | [EM5](EngineeringManager.md#em5---engineering-manager-5) |
| 6 | Yes | [D6](Developer.md#d6---developer-6) | [TL6](TechLead.md#tl6---tech-lead-6) | [TPM6](TechnicalProgramManager.md#tpm6---technical-program-manager-6) | [EM6](EngineeringManager.md#em6---engineering-manager-6) |
| 7 | Yes | [D7](Developer.md#d7---developer-7) | [TL7](TechLead.md#tl7---tech-lead-7) | [TPM7](TechnicalProgramManager.md#tpm7---technical-program-manager-7) | [EM7](EngineeringManager.md#em7---engineering-manager-7) |

(詳細は役職名をクリックしてください)

# 軸

上記のチャートには、以下の5つの軸があります:
* **Technology**: 技術スタックとツールに関する知識
* **System**: システムに対するオーナーシップの度合い、レベル
* **People**: チームとの関係性
* **Process**: 開発プロセスへの関与のレベル
* **Influence**: 現状のポジションの影響範囲

`※図に表示された言葉なのであえて日本語に訳すことはしておらず以下では、英語表記のままとする。`

**Influence** 軸は、他と直交しておりすべての軸に適用されるため、*異なった次元* と見なすことができます。

各軸には、5 つの異なるレベルのパフォーマンスがあります。すべてのレベルに前のレベルが含まれていることが着目すべき重要な点です。たとえば、 Technology 軸で *evangelizes* を実行している人は、 *specializes*、*adopts* も行うことができることを表現しています。

各レベルの詳細は後述しています。

# Levels
`※各レベルについては、図に表示された言葉なのであえて日本語に訳すことはしていない。`

## Technology

1. **Adopts**: チームによって決定されたテクノロジーとツールを積極的に学び、取り入れる。
2. **Specializes**: 1つまたは複数の技術領域において頼りになる人物であり、新しい技術を学ぶために率先して行動している。
3. **Evangelizes**: 調査、実証実験の実装、チームに新しいテクノロジーを導入する。
4. **Masters**: システムの技術スタック全体について非常に深い知識を持っている。
5. **Creates**: 内部または外部のチームによって広く使用されるような新しいテクノロジーを設計および作成する。

## System

1. **Enhances**: システムを改善および新機能とバグ修正を実行できる。
2. **Designs**: システムの技術的負債を削減しながら、中規模から大規模なサイズの機能の設計および実装をする。
4. **Owns**: システムの運用と監視を担当し、その SLA を気にしている。
5. **Evolves**: 将来の要件をサポートするためにアーキテクチャを進化、改善させ、SLA を定義する。
6. **Leads**: システムの技術的卓越性をリードし、停止を軽減するための計画を作成する。

## People

1. **Learns**: 他の人からすぐに学び、必要に応じて定常的にステップアップする。
2. **Supports**: 他のチームメンバーを積極的にサポートし、彼らが成功するのを助ける。
3. **Mentors**: 他の人がキャリア成長を加速できるようメンタリングを行、そのメンバーが力を発揮できるように導く。
4. **Coordinates**: チームメンバーの間に入り、効果的なフィードバックを提供したり、議論を円滑にする。
5. **Manages**: チームメンバーをマネージすることでキャリア、期待、パフォーマンス、幸福度に貢献する。

## Process

1. **Follows**: チームのプロセスに従い、継続的に機能群を本番環境に提供する。
2. **Enforces**: チームのプロセスを実施し、チーム全員がメリットとトレードオフを確実に理解できるようにする。
3. **Challenges**: 改善する方法を探し、チームプロセスに対して挑戦的になる。
4. **Adjusts**: チームのプロセスのバランスをとり、フィードバックに耳を傾け、変更を通じてチームを導く。
5. **Defines**: 敏捷性と規律のバランスをとりながら、チームの成熟度に適したプロセスを定義する。

## Influence

1. **Subsystem**: 1つ以上のサブシステムに影響が与えている。
2. **Team**: チームの特定の部分だけではなく、チーム全体に影響を与えている。
3. **Multiple Teams**: 自分のチームだけではなく、他のチームにも影響を与えている。
4. **Company**: 開発組織全体に影響を与えいてる。
5. **Community**: 技術コミュニティに影響を与えている。

# FAQs

**すべての軸を満たしていない場合はどうなりますか?**

それはごく普通に発生することです。人は通常、ある分野では強く、別の分野では弱くなります。このフレームワークは、メンバーの昇進を判断するチェックリストとして使用するのではなく、キャリアパスについて有意義な会話をするための手引きとして利用する。

**組織のキャリアラダーと異なる場合はどうすべきですか？**

このフレームワークはオープンソースとして公開しているため、組織に合わせて適応することができます。[チャートテンプレート](charts/template.png) を改変することで独自のレベルを定義してください。

**メンバーはいつ次のレベルに移ることができますか？**

企業は通常、正式に昇進する前に *継続して数ヶ月* の間、次のレベルのパフォーマンスを出していることを期待しています。

**メンバーとの議論にあたって必要な裏付けはどのように収集すればいいですか？**

チームによって様々なあった裏付けの収集方法があります。次の方法の組み合わせを使用することが推奨です:
* 1on1
* 同僚や他のチームからのフィードバック
* 自己評価

**フレームワークは、各レベルのより具体的な例を挙げることはできますか？**

具体的な例を挙げるには、そのチームの働き方、システムアーキテクチャ、技術スタックについて知る必要があります。各チームの中で独自の例を定義することが推奨されます。

**フレームワークのレベルが7までなのはどうしてですか？**

レベル8以上は企業によって大きく異なります。様々な組織では、組織構造の高い位置に多様なレベルの役割を設ける傾向があります。

**他の参照情報などはありますか？**

* [The Manager's Path](http://shop.oreilly.com/product/0636920056843.do): Camille Fournier は、多くのエンジニアリング職の期待と課題を見事に説明しています。 また、彼女は第9章でキャリアラダーを書くにあたって良いアドバイスを提供しています。

* [How to Be Good at Performance Appraisals](https://store.hbr.org/product/how-to-be-good-at-performance-appraisals-simple-effective-done-right/10295): Dick Grote が、仕事の責任を定義する方法とパフォーマンス (結果と行動) を評価する方法を簡単な言葉で説明しています。

# その他のページ

* [**開発者**](Developer.md)
* [**テックリード**](TechLead.md)
* [**テクニカルプログラムマネージャー**](TechnicalProgramManager.md)
* [**エンジニアリングマネージャー**](EngineeringManager.md)
* [**テックリード vs エンジニアリングマネージャー**](TechLead-EngineeringManager.md)
* [**マネージャーのマネジメント**](Managing-Managers.md)
