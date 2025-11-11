# ゲームデザイン実習（2025年度入学生向け）

- [シラバス](design_2025_syllabus.pdf)
- [Google Meet](https://meet.google.com/bwb-njcm-udh)
- [講義日程](thu.md)
- [URLなどの報告](https://docs.google.com/forms/d/e/1FAIpQLSfXGJvYbiwt1qQLB5GhHJJFp_NxH939IvLUvGuzuWzW6WgUvQ/viewform?usp=dialog)
- [Slack](https://datgm25.slack.com)

## ゲーム画面の録画

- Windowsの機能を使う
  - ゲームを実行する
  - Win + Alt + Rキーで、録画開始。同じ操作で、録画停止
  - Win + Gキーでメニューを表示して、カメラアイコンをクリックして、キャプチャを表示を選択すると、録画した動画を確認できる
- ChatGPTで、「Unity Recorderを使って、プレイ画面を録画する手順を示せ」と聞く

## 後期6回目(11/13)

### 今後の1年生の進行

- ポートフォリオの作成
- DATフェスタのデータを取りまとめて、可能な範囲でWeb公開

### 予定

- 展示成果の共有と講評
  - DATフェスタに展示した実行ファイルを、指定のフォルダーへコピーして提出。すでに展示版になっていたらこの作業は不要
  - DATフェスタ講評
- [ポートフォリオページの作成](https://docs.google.com/document/d/1QbUmT97-DdaIApRuugYi3A8OdDgw58fw0C4l4QOCtzg/)
  - ポートフォリオとは何か、作る際に最初にやること、などを確認
    - [ゲームクリエイターズギルド. ポートフォリオは自分ブランディング！見せ方を設計しよう【ゲーム業界就活】](https://game.creators-guild.com/g4c/shukatsu-20210215)
  - ポートフォリオの例
    - [過去の講義の作例](https://github.com/tanakaedu/portfolio-with-markdown/blob/main/portfolio-example.md)
    - [2024年度の作例](https://github.com/datgm24/portfolio)
- DATフェスタ版のビルドデータ、インストカードのデータ、プロジェクトの提出
  - Unity
    - インストカードのデータを、Unityのプロジェクトフォルダーにコピーする
    - GitHubに最新版をコミット、プッシュ
  - ティラノ
    - プロジェクトフォルダーをZIP圧縮する
    - `Z:\2025\student\gp1\DATフェスタ展示版プロジェクト一式`フォルダーを開いて、新しいフォルダーを作成して、フォルダー名を作品名に変更
    - 圧縮したZIPファイルと、インストカードのデータを作成したフォルダーにコピーする





## 後期3-5回目(10/16, 23, 30)

### 内容

- 質問があれば、[URLなどの報告](https://docs.google.com/forms/d/e/1FAIpQLSfXGJvYbiwt1qQLB5GhHJJFp_NxH939IvLUvGuzuWzW6WgUvQ/viewform?usp=dialog)から、URL欄に質問を書いて送信してください
- Unity6.2への移行
  - GitHubへ、最新版をコミットして、プッシュ
  - unity6_0というブランチを作成
  - mainブランチに戻して、Unity6.2で開く
  - 問題なければ、Unity6.2で開発を継続
  - 問題が出たら、unity6_0ブランチに切り替えて、これまでのバージョンで開発する
- DATフェスタ企画の検討と共有
  - [DATフェスタ作業メモ](https://docs.google.com/document/d/1hlvOA0Y5QwyDMy0n_DADNNKveL0U5viiOXfaFvGjaDk/)
- 作業リストの進捗チェック
- 進捗を聞き取りながら、企画概要をまとめる

### インストラクションカードの作成
- [インストラクションカードとは](https://ja.wikipedia.org/wiki/%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%A9%E3%82%AF%E3%82%B7%E3%83%A7%E3%83%B3%E3%82%AB%E3%83%BC%E3%83%89)
  - [例](https://www.google.com/search?q=%E3%82%A2%E3%83%BC%E3%82%B1%E3%83%BC%E3%83%89%E3%82%B2%E3%83%BC%E3%83%A0+%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%82%AB%E3%83%BC%E3%83%89&source=lnms&tbm=isch&sa=X&ved=2ahUKEwj4_tjW6tXzAhVFeXAKHTSpBNcQ_AUoAXoECAEQAw&biw=1035&bih=891&dpr=1)
  - A4カラー or A3カラーの横 1ページ
  - アクリルスタンドで立てる(A4縦)か、モニターに貼る(A3横)
  - ゲームタイトル、ゲーム概要、操作説明、ルール、開発メンバークレジットを書く
  - PowerPointを使って、A4の縦方向に設定する例。それぞれ、作りたいカードにあわせて読み替える
    - デザインタブに切り替え
    - スライドのサイズから、ユーザー設定のスライドのサイズを選択
    - スライドのサイズ指定をA4、印刷の向きをスライドの縦を選択してOK


## 後期2回目(10/9)

### 話題

- [「ティアキン」スクラビルドは“12万通り”全組み合わせを手作業チェック！ 「ムリでは？」から始まる実装までの道のり](https://game.watch.impress.co.jp/docs/kikaku/1617761.html)

### 内容

- DATフェスタ企画の検討と共有
  - [DATフェスタ作業メモ](https://docs.google.com/document/d/1hlvOA0Y5QwyDMy0n_DADNNKveL0U5viiOXfaFvGjaDk/)
- 作業リストの進捗チェック
- 進捗を聞き取りながら、企画概要をまとめる




## 後期1回目(10/2)

### 話題

- [ゲームクリエイター甲子園2025](https://game.creators-guild.com/gck/)

### 内容

- DATフェスタ企画の検討と共有
  - [DATフェスタ作業メモ](https://docs.google.com/document/d/1hlvOA0Y5QwyDMy0n_DADNNKveL0U5viiOXfaFvGjaDk/)
- 仕様と作業リスト作成
- ゲーム画面の録画
  - Windowsの機能を使う
    - ゲームを実行する
    - Win + Alt + Rキーで、録画開始。同じ操作で、録画停止
    - Win + Gキーでメニューを表示して、カメラアイコンをクリックして、キャプチャを表示を選択すると、録画した動画を確認できる
  - ChatGPTで、「Unity Recorderを使って、プレイ画面を録画する手順を示せ」と聞く


---

## 15回目(9/4)

### 内容

- DATフェスタに向けた企画の検討
  - 夏休み課題の展示の希望
  - 作りたい作品の概要
- 現時点での意向の共有
  - [講評と改善点の検討](https://docs.google.com/document/d/1UL6mu3DTwFP3z9VKShZu_RMezRj1IhaHHxXTxTKv290/)
- 企画と仕様の検討
  - 後期1回目で確認予定（10/2）


## 夏休み課題(ゲームデザイン実習、ゲームプログラミング共通)
以下のうち１つを選んで、夏休み中に完成させて、プロジェクトを提出する。

- 選択肢１　Unityの教科書の改造
  - 4章以降のサンプルを完成させる
  - プログラムの変更が伴うアレンジを１つ以上考えて、アレンジ版を作成する
  - OK例　新しいアイテムを追加 / 新しい敵を追加 / 新しい操作を追加
  - NG例　絵の差し替えのみ / アニメの変更のみ
- 選択肢２　オリジナルゲームを完成させる
  - 自分で考えた企画を完成させる
  - 使用するツールは学校で使えるものなら自由(Unity, GDevelop, ティラノスクリプト, Light.vnなど)
- 選択肢３　ネット上で見つけたチュートリアルの改造
  - ネット上でブログなどで紹介されている作品を完成させる
  - 選択肢1と同じくプログラムの改変を伴う改造をする


## 14回目(8/28)

### 話題

- [Power Jump & Power Kick!!](https://am1tanaka.itch.io/pwjp-pwkick) Kenney Jam 2025参加作品

### 内容

- 夏休み課題のとりまとめとWeb公開用素材の提出
- 夏休み課題の共有(10時から)
- [講評と改善点の検討](https://docs.google.com/document/d/1UL6mu3DTwFP3z9VKShZu_RMezRj1IhaHHxXTxTKv290/)

### 提出

- README.txt
  - 参考にしたものがあれば、その書籍名やURLと、自分で何を改造したかを書く
  - 公開していない場合は公開先は不要
  - 同様に、書くことがない項目は、削除する
  - README.txtの作例
    - [よけとるのREADME.txtの作例](https://github.com/datgm25/design/blob/main/README_yoketoru.txt)
    - [Power Jump & Power Kick!!のREADME.txtの作例](https://github.com/datgm25/design/blob/main/README_pjpk.txt)
- ゲーム内容がわかるスクリーンショット1枚以上
- 提出先
  - フォルダー`Z:\2025\student\gp1\gp1夏休み`内に `出席番号 + 名前` のフォルダー(00tanakaなど)を作成して、その中にREADME.txtファイルとスクリーンショットファイルを提出する

### スクリーンショットの撮り方
- Windowsキー + Shiftキー + Sキーを押す
- マウスで、ゲーム画面の範囲をドラッグして、コピー
- スタートメニュー > ペイントを起動
- Ctrl + Vキーで、貼り付け
- 指定のフォルダーへ、screenshot.pngなどで保存

## 13回目(7/17)

### ゲーム制作班

- 調査結果の共有

### プログラム班

- 習作ゲーム「よけとる」の開発
  - 習作ゲーム「よけとる」の企画と仕様
    - [よけとる2021試遊版](https://github.com/datgm21/yoketoru2021-demo)
    - [よけとる企画構想書](https://docs.google.com/document/d/1hSRJ4GtA8nCIfHVwJks-NzTap1iFulJQMzFpX0I6xWs/)
    - [よけとる試作版仕様書](https://docs.google.com/spreadsheets/d/16jNh4mKVjusu1bzpv06IbR8abfwVfFfFzKCNs7Byw8g/)
  - [作業メモ](https://docs.google.com/document/d/139s2h5dCGH0fvh0j7tg-gKrNKlMCavxMkTygmcRwSQg/)

## 11, 12回目(7/3, 10)

### 話題

- [ITmedia. ゲーム開発者100人超に聞く「生成AI、もう使ってる？」　クリエイティブ分野での利用度は](https://www.itmedia.co.jp/news/articles/2507/10/news042.html)

### ゲーム制作班

- 自力で使えそうなゲーム制作ツールを調べて選ぶ。管理者権限が不要なものであること。以下、候補例
  - [ティラノビルダー](https://b.tyrano.jp/)
  - [ティラノスクリプト](https://tyrano.jp/)
  - [Microsoft MakeCode Arcade](https://arcade.makecode.com/)
  - [GDevelop](https://gdevelop.io/ja-jp)
  - [WOLF RPGエディター](https://www.silversecond.com/WolfRPGEditor/)
    - [学生の記事](https://am1.space/dat/gp2/2024/06sakamoto.pdf)
  - [Mind Render](https://mindrender.jp/)
    - [学生の記事](https://am1.space/dat/gp2/2023/rep_tama.pdf)
  - [RAPTEX](https://raptex.jp/)
- 説明が英語でも、ブラウザーの翻訳機能や、Google翻訳、スマホのGoogleアプリの翻訳機能、[DeepL](https://www.deepl.com/ja/translator)などで、日本語にできる
- 10, 11回目で、ツールの選択と使い方の調査と、制作するゲーム内容を検討する。12回目に、状況の共有予定
- **学習のための基礎力を身に着けることが目的なので、成果が出なくても構わない**。自分のペースで、ドキュメントを探したり、読んだり、試したりすることが大切。1年間を費やすぐらいの気持ちで、じっくりと腰を据えて取り組んでほしい

### プログラム班

- 習作ゲーム「よけとる」の開発
  - 習作ゲーム「よけとる」の企画と仕様
    - [よけとる2021試遊版](https://github.com/datgm21/yoketoru2021-demo)
    - [よけとる企画構想書](https://docs.google.com/document/d/1hSRJ4GtA8nCIfHVwJks-NzTap1iFulJQMzFpX0I6xWs/)
    - [よけとる試作版仕様書](https://docs.google.com/spreadsheets/d/16jNh4mKVjusu1bzpv06IbR8abfwVfFfFzKCNs7Byw8g/)
  - [作業メモ](https://docs.google.com/document/d/139s2h5dCGH0fvh0j7tg-gKrNKlMCavxMkTygmcRwSQg/)


## 10回目(6/26)

### 内容

- キャラのプレハブを揃える
  - [Unityのキャラクター用のゲームオブジェクトの構築](https://docs.google.com/document/d/1wsdsAdmLVoHagV71I1wJHpxXExgws9N6eZL54hWnLr8/)
    - [キャラ作成の作業メモ](https://docs.google.com/document/d/19vK5O5WOXNgs9MqsggJ9h80lp9jvd-NKs1KSADd6pXQ/)
    - [必要な素材のリスト](https://docs.google.com/document/d/1jG55JBt66CVDBo8DmrLqCd7bnXH700PUSmkFwVCZzuk/)
  - unitypackageで書き出す
    - [こちら](https://docs.google.com/document/d/10UpsXhB-dGMrBqmMvZow-xGcs57YMysIfNekGgEWkzM/)の「プレハブやシーンの受け渡しの手順」を参照
- よけとるのモックアップ作成
  - [作業メモ](https://docs.google.com/document/d/139s2h5dCGH0fvh0j7tg-gKrNKlMCavxMkTygmcRwSQg/)の続き
  - 書き出したunitypackageを、よけとるのプロジェクトに読み込む
    - [こちら](https://docs.google.com/document/d/10UpsXhB-dGMrBqmMvZow-xGcs57YMysIfNekGgEWkzM/)の「unitypackageファイルを統合する」を参照
  - 仮のタイトル、ゲーム、ゲームオーバー、クリアシーンを作成する
- アセット探し
  - Googleドキュメントを新規に作成して、名前をYoketoruMemoにする
    - グラフィックやフォント、音素材の入手元URLを記入
    - その他、何かあればここにメモしておく
  - BGMと効果音を探す
- モックアップの構造の確認


## 9回目(6/19)

### 内容

- ワンキーゲームと習作ゲームのキャラを作る
  - [Unityのキャラクター用のゲームオブジェクトの構築](https://docs.google.com/document/d/1wsdsAdmLVoHagV71I1wJHpxXExgws9N6eZL54hWnLr8/)
    - [キャラ作成の作業メモ](https://docs.google.com/document/d/19vK5O5WOXNgs9MqsggJ9h80lp9jvd-NKs1KSADd6pXQ/)
  - 習作ゲーム「よけとる」の企画と仕様
    - [よけとる2021試遊版](https://github.com/datgm21/yoketoru2021-demo)
    - [よけとる企画構想書](https://docs.google.com/document/d/1hSRJ4GtA8nCIfHVwJks-NzTap1iFulJQMzFpX0I6xWs/)
    - [よけとる試作版仕様書](https://docs.google.com/spreadsheets/d/16jNh4mKVjusu1bzpv06IbR8abfwVfFfFzKCNs7Byw8g/)
  - 前回のUnityプロジェクトで、よけとる用のキャラのプレハブを作る
    - [必要な素材のリスト](https://docs.google.com/document/d/1jG55JBt66CVDBo8DmrLqCd7bnXH700PUSmkFwVCZzuk/)
    - [UnityのプロジェクトをGitで管理するように設定して、GitHubにPublishする手順](https://github.com/datgm22/design/blob/main/github-unity.md)
  - アセットストアの利用
  - [Kenney.nl](https://kenney.nl)
  - 入手元のURLを記録しておくこと (自作データなら不要)
    - クレジット画面を作って、記録すると楽。1週間ゲームジャムのunityroomには使用アセットの登録欄があるので、そこに記載しておけばよい。ドキュメントに記載でもよい
- モックアップの構造の確認
- 参考
  - [ProBuilderの利用](https://docs.google.com/document/d/129pS_YQPJq3srmxEqCDMUX8a9aqGGnTy0OzaEPsajXU/)


### 参考資料
- [Unityでモックアップ作成](https://docs.google.com/document/d/17WatyZDngqasXH0k6hKGg8V-_9kEqqOViAhxmiuofhI/)
- [UnityのプロジェクトをGitで管理するように設定して、GitHubにPublishする手順](https://github.com/datgm22/design/blob/main/github-unity.md)
- [UnityのUI](https://docs.google.com/document/d/1oUDdWBGk2XUjAyt7RLHL2a1shBwrZp-ghrOb4wzGddk/)
- [Coliss. 2024年用、日本語のフリーフォントまとめ](https://coliss.com/articles/freebies/japanese-free-fonts.html)
- [TextMesh Pro向け ASCIIコード+JIS第1水準の文字](https://am1tanaka.hatenablog.com/entry/2019/10/14/183408)

## 8回目(6/12)

### 内容

- [著作権概論](https://docs.google.com/document/d/15zRG0hcf9OU3TFoJ5vZL43AGPKCqewpD7KS_QYwntaA/)
- [ProBuilderの利用](https://docs.google.com/document/d/129pS_YQPJq3srmxEqCDMUX8a9aqGGnTy0OzaEPsajXU/)
- モックアップ続き

## 7回目(6/5)

### 話題

- [GIGAZINE. 破産したAI企業が提供していたコーディングAIが実は700人のエンジニアによる人力サービスだったと判明](https://gigazine.net/news/20250604-builder-ai-business/)

### 内容

- Unityでモックアップ作成-文字の表示-
  - u0515のCanvas Scalerから
  - [UnityのUI](https://docs.google.com/document/d/1oUDdWBGk2XUjAyt7RLHL2a1shBwrZp-ghrOb4wzGddk/)
  - [TextMesh Proの使い方](https://am1.jp/tutorials/unity/tmpro/)
  - [Coliss. 2025年用、日本語のフリーフォント767種類のまとめ](https://coliss.com/articles/freebies/japanese-free-fonts.html)
  - [TextMeshPro向け　ASCIIコード＋JIS第1水準の文字](https://am1tanaka.hatenablog.com/entry/2019/10/14/183408)
- 前回のワンキーゲームのモックアップを作る
- 成果を[Gootle Meet](https://meet.google.com/bwb-njcm-udh)で共有

## 6回目(5/29)

### 内容

- [文字のデザイン](http://am1.space/dat/design/design5-font.pdf)
  - [図](http://am1.space/dat/design/design5-font-fig.pdf)
- [Unityでモックアップ作成](https://docs.google.com/document/d/17WatyZDngqasXH0k6hKGg8V-_9kEqqOViAhxmiuofhI/) 復習
- Unityでモックアップ作成-文字の表示-
  - [UnityのUI](https://docs.google.com/document/d/1oUDdWBGk2XUjAyt7RLHL2a1shBwrZp-ghrOb4wzGddk/)
  - [TextMesh Proの使い方](https://am1.jp/tutorials/unity/tmpro/)
  - [Coliss. 2025年用、日本語のフリーフォント767種類のまとめ](https://coliss.com/articles/freebies/japanese-free-fonts.html)
  - [TextMeshPro向け　ASCIIコード＋JIS第1水準の文字](https://am1tanaka.hatenablog.com/entry/2019/10/14/183408)


## 5回目(5/22)

### 話題
- プロトタイプの例 [hempuli. TROVEMOUNT](https://hempuli.itch.io/trovemount?ac=qfCyYFQF-tw)

### 内容
- [レイアウト FOTORIA. 三分割法で写真の構図をバッチリ決定！イラストで撮影方法を解決](https://fotoria.net/ja/blog/bc/photo-shoot-techniques/sc/composition/ar/rule-of-thirds/)
- [色のデザイン](http://am1.space/dat/design/design4-color.pdf)
  - [図](http://am1.space/dat/design/design4-color-fig.pdf)
- 演習：企画の構想
  - ワンキーゲームの構想をまとめる
    - [ゲームの企画の鍵](https://docs.google.com/presentation/d/1drsBdUCuIgHrFO0VtAAmZxRTV8mqrM6x0UHr9U23YyY/)
    - 画面レイアウトや、面白場面を考える
    - 参考
      - [ジャンプ＆ポン](https://docs.google.com/document/d/1094vOcSmarVTz6oveydEAVjaPNaae-sdmGNZ643abgQ/)
      - [フルーツ洞窟](https://docs.google.com/presentation/d/15gL8iBUboiPvj6Po5NBouCa3Ge-vZpoxNUheVFlVe7Q/) 
  - Googleスライドで、新規作成
  - ドキュメント名を、ワンキー：氏名
  - 仮タイトルを表紙に（最後でよい）
  - 操作方法とルール
  - 画面レイアウトのラフスケッチ 960x540px
  - 面白場面のラフスケッチ
  - 右上の共有をクリックして、制限付きをクリック＞リンクを知っている全員に変更
  - リンクをコピー＞完了
  - [こちら](https://docs.google.com/forms/d/e/1FAIpQLSfXGJvYbiwt1qQLB5GhHJJFp_NxH939IvLUvGuzuWzW6WgUvQ/viewform?usp=dialog)にURLを貼り付けて共有


## 4回目(5/15)

### 内容

- [形のデザイン](https://am1.space/dat/design/design3-shape.pdf)
  - [Unityでモックアップ作成](https://docs.google.com/document/d/17WatyZDngqasXH0k6hKGg8V-_9kEqqOViAhxmiuofhI/)
- [ゲームメカニクス　ボードゲーム版](https://docs.google.com/document/d/1xGz1yZG_H4op19PyiOO5Bu4Gt9dHdlRItBZq05MFeYc/)
  - 演習は飛ばす

## 3回目(5/8)

### 内容

- 前回のブレスト企画をまとめる
  - 参考
    - [EIKIさん. ゴリラが人類を強制的にSTAY HOMEさせるゲーム](https://youtu.be/-qWwYVWgczA?t=6719)・・・アイディアの転がし方、発注、ペース、進め方
    - [tnkさん. 「斬新さ」から考えるゲーム開発](https://youtu.be/-qWwYVWgczA?t=3002)・・・プランナー的視点、斬新なアイディア
    - [ゲームクリエイターズギルド. Reverse Room](https://game.creators-guild.com/g4c/23951/?utm_source=rss&utm_medium=rss&utm_campaign=23951)
    - [nekogeek. カジュアルゲームの最新ゲームを50本遊んで、企画の方向を考えよう](https://nekogeek.jp/play-casual-games-a-lot/)
    - 作例
- Googleスライドを以下の手順で共有する
  - 右上の 共有 をクリック
  - リンクを知っている全員に変更 をクリック
  - リンクをコピー をクリックして、完了をクリック
  - [こちら](https://docs.google.com/forms/d/e/1FAIpQLSfXGJvYbiwt1qQLB5GhHJJFp_NxH939IvLUvGuzuWzW6WgUvQ/viewform?usp=dialog) を開いて、氏名に名前を入力、URL欄を右クリックして、Ctrl + V キーでコピーしていたリンクを貼りつけて送信
- [Google Meet](https://meet.google.com/bwb-njcm-udh)で企画案の共有
- [ゲームメカニクス　ボードゲーム版](https://docs.google.com/document/d/1xGz1yZG_H4op19PyiOO5Bu4Gt9dHdlRItBZq05MFeYc/)
  - ゲームの歴史まで

## 2回目(5/1)

### 話題

- [unity1week online共有会 #15](https://www.youtube.com/live/wmF1z5Epr1g?feature=shared)
  - 他校の学生さんの活動例 [えふぇこ: u1w反省会](https://www.youtube.com/watch?v=wmF1z5Epr1g&t=4486s)
- [1週間ゲームジャム](https://unityroom.com/unity1weeks)

### 内容

- 講義
  - [スライド:ゲームの定義や要素からミニゲームを考える](https://docs.google.com/presentation/d/16VJ2M9ly2rlyg_CSHn2PX-UxZdwWcwDsLYLpMEWOknA/)
    - 復習 + 緊張と解放
  - [ゲームデザインの基礎](https://docs.google.com/document/d/1ItqVAv-e-dnThzUF1o-8xucq7l95gel6FF9-96kBkpo/)
    - [Unity Learning Material. たのしさの作り方 ](https://learning.unity3d.jp/2618/)
    - [Jesse Schell's ゲームデザインレンズデッキ](http://deck.artofgamedesign.com/#/?lang=jp)のカードリストを眺める
  - [ゲームクリエイター甲子園](https://game.creators-guild.com/gck/) 受賞作品をみて、要素を確認する
    - 過去の大会 > 見たい年度 > 結果発表はこちら！をクリック
- 参考
  - [遠藤雅伸. ゲーム道に通じるユーザーの振る舞いとゲームデザインへの応用](https://www.teu.ac.jp/ap_page/koukai/2019_03_3endo.pdf)

### 演習１：グループでアイディアを出し

- ブレスト
  - [面白法人カヤック. 始まりも終わりもブレスト](https://www.kayac.com/vision/brainstorm)
- 手順
  - [こちら](https://docs.google.com/spreadsheets/d/1NvhnYIoOGHVTS_dtwY_9lWs1cJ3J5DwJrwq9PHmBWt8/)を右クリックして、新しいタブで開く
    - シートの下から自分のグループのタブをクリックして開く
    - A列に、ホワイトボード側の人から順に思いついた単語を入力していく
    - ※ブレストの目的は、普通は出ないような飛躍的な案を出すこと

### 演習２：ブレストで出た単語から3つのランダムワードを使った企画を考える

- スライドの準備
  - https://drive.google.com を開く
  - 左上の新規ボタンを押す
  - Googleスライドをクリック
  - 無題のスライド の部分をクリックして、「企画演習：氏名」と入力。氏名の部分は自分の名前
  - ランダムで選ばれた自分のグループの単語をスライドに貼り付ける
- 以下の項目をGoogleスライドにまとめる
  - ゲームのコードネーム(仮のタイトル)
  - コアステートメント
  - 画面のサムネイル
    - 手書きやペイント、図形などを使って、画面のサムネイルを作成(線を太めにして、しっかりと端を閉じると奇麗に見える)
      - 参考： [ArtStation. Gameplay & Level Design](https://www.artstation.com/channels/gameplay_and_level_design?sort_by=trending)
  - 具体的な操作方法
  - ルール(何をやるのか。あるいは、どうなったらダメなのか。など)
  - 世界観(いつ、どこ、だれ。ハイパーカジュアル系など、これがないものもあるので、ない時はなしでよい)
- 考えるヒント
  - 選択と解放や、何を試すかを考えて、面白さを狙う
  - プレイヤーが「これは面白い！」と感じるクライマックスの瞬間を考える
  - ゲームデザインレンズデッキの1～5を参考にする
  - 考えた理由を最大に強調するための操作方法、ルール、ステージ、設定などを考える

# 1回目(4/17)

- [ガイダンス](https://docs.google.com/presentation/d/1tvOISbFwll-c7fmJ7qJVIciTp3ZknSEr/)
- [環境の準備](https://docs.google.com/document/d/16MW6maMYvt8m-60RM5wU_LzJ5r-3Hm0WTnxoBGDzxIA/)
  - Googleアカウント / Slack / GitHub / 作業用フォルダー
  - ツールについて
    - プログラムやアプリの使い方の管理、文章作成者が決まっているようなもの：GitHub
    - 大きな画像や動画など：Googleドライブ
    - 意見交換：Slack(3ヶ月で消えるので消えてもよい質疑応答や進捗の共有、ブレストなど。クラス以外には非公開)
    - 企画書や仕様書、確認事項など、手軽に共有したり編集できて残しておきたい文章：Googleドキュメント、ワークシート、Notion, Trelloなど
- 講義
  - [キー入力の練習](https://docs.google.com/document/d/1SUtdf1lu0dVyzqLkJZUX2G7YmtKZszW3AjBcBmu7Pao/)
  - [スライド:ゲームの定義や要素からミニゲームを考える](https://docs.google.com/presentation/d/16VJ2M9ly2rlyg_CSHn2PX-UxZdwWcwDsLYLpMEWOknA/)
