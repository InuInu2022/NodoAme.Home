# NodeAme（ノドアメ） :id=nodoame

> [!Note|iconVisibility:hidden]
> 最新版：${tag_name}

しゃべるCeVIOソング補助ツール [#喋らせてみた](https://www.google.com/search?q=%23%E5%96%8B%E3%82%89%E3%81%9B%E3%81%A6%E3%81%BF%E3%81%9F)

## お知らせ

> [!Note]
> ニコニコ動画の公式放送「[ソフトウェアトーク動画投稿祭応援しまくる祭](https://live.nicovideo.jp/watch/lv336019216#32:11)」でご紹介いただきました。

[#投稿祭応援しまくる祭 ご紹介ありがとうございました動画【NodoAme】](https://ext.nicovideo.jp/thumb/sm40237436 ':include :type=iframe width=560px height=200px scrolling=no frameborder=0 style="border:solid 1px #ccc;"')

----

> [!Note]
> 試しに[Twitterコミュニティ](https://twitter.com/i/communities/1500356662636716034)作ってみました！
> Twitterをやられている方はご確認ください！
> https://twitter.com/i/communities/1500356662636716034

## __charm:candy__ これはなに？ :id=whats_nodoame

[CeVIO ソング](https://cevio.jp/products_cevio_ai/)（可不ちゃんなど）をしゃべってる風に歌わせるための補助ツールです。
おまけ機能で歌詞の表記変換(発音通りのひらがな・音素)機能もあります。

![ss](_media/screenshot/main.png ':size=400')

## __el:video-alt__ 紹介動画 :id=movies

- __fa-brands:youtube__ [YouTube](https://youtu.be/lHshJSPfd-M)
- __simple-icons:niconico__ [niconico](https://nico.ms/sm39928066)

[YouTube video player](https://www.youtube.com/embed/lHshJSPfd-M ':include :type=iframe width=560px height=315px allowfullscreen')

[可不ちゃんにしゃべってもらえるソフトつくってみた【NodoAme】#第1回CeVIOクリエイト祭](https://ext.nicovideo.jp/thumb/sm39928066 ':include :type=iframe width=560px height=200px scrolling=no frameborder=0 style="border:solid 1px #ccc;"')


## __bx:bxs-cloud-download__ DL :id=dl

> [!NOTE|label:最新版情報|iconVisibility:hidden]
>
> - バージョン：<strong>${tag_name}</strong>
> <pre>${body}</pre>

<a href="${assets[0].browser_download_url}" class="download"><span class="iconify-inline" data-icon="bx:bxs-cloud-download"></span> 最新版 ${tag_name}<br> ダウンロード</a>

- [過去のバージョン/先行公開版一覧はこちら](https://github.com/InuInu2022/NodoAme.Home/releases)
- ※予備 [bowlroll](https://bowlroll.net/file/269946) pass:カレーうどん

<details id="next-version" style="margin:1em 0;margin:1.5em;">
<summary>次期バージョンの予定</summary>

- v0.3.0 では次を予定しているよ！
  - CeVIOトークの感情合成対応
    - [v0.3.0 alpha-14で対応!](https://github.com/InuInu2022/NodoAme.Home/releases/tag/v.0.3.0-alpha.14)
  - 星界（SEKAI）ちゃん、つづみちゃん（AIソング）、キズナちゃん、POPYちゃん、ROSEちゃん、Ci flowerちゃん、裏命（RIME）ちゃん仮対応
  - VoiSona (旧:CeVIO Pro)/知声ちゃん対応
    - [v0.3.0 alpha-10で対応！](https://github.com/InuInu2022/NodoAme.Home/releases/tag/v.0.3.0-alpha.10)
    - ただし、VoiSona側にバグがあるようで上手くいかないパターンがあります
  - 息継ぎブレス音抑制機能
    - [v0.3.0 alpha-11で対応！](https://github.com/InuInu2022/NodoAme.Home/releases/tag/v.0.3.0-alpha.11)
  - ウソ英語機能
    - CeVIO AI トーク弦巻マキEnglishが必要です！
    - [v0.3.0 alpha-16で対応！](https://github.com/InuInu2022/NodoAme.Home/releases/tag/v.0.3.0-alpha.16)
  - セリフの秒数表示機能
    - [v0.3.0 alpha-20で対応！](https://github.com/InuInu2022/NodoAme.Home/releases/tag/v.0.3.0-alpha.20)

</details>

> [!NOTE]
> ニコニコ動画などでこのツールを使った動画などを公開する場合は、以下のニコニコモンズをコンテンツツリーに登録して下さい！（義務ではありません）
>
> [nc262424](https://commons.nicovideo.jp/material/nc262424)

## __mdi:arm-flex__ できること :id=main_purpose

### CeVIOトークのしゃべりをマネして楽譜データを出力する :id=song_voice_speaking

NodoAmeはCeVIOトーク(CS/AI)のボイスにしゃべらせた音声をマネして、CeVIOソングむけの楽譜データ(ccstファイル)を出力します。
出力したccstファイルをソングエディタ上で再生すると、しゃべってる風に歌ってくれます。

現在は次のトーク音源に対応しています。

- [CeVIO AI](https://cevio.jp/)
- [CeVIO Creative Studio 7](https://cevio.jp/product/ccs/)
- [VOICEVOX](https://voicevox.hiroshiba.jp/)
- 標準音声

CeVIOトーク音源を持っていなくとも、内蔵の**標準トーク音源**や、無料の**VOICEVOX**などの対応他ソフトのトーク音源が使えます。

楽譜データの書き出しは次のソング音源に対応しています。

- CeVIO AI
  - 可不（KAFU）
  - さとうささら
  - 結月ゆかり麗
  - 東北きりたん
  - IA
  - IA English（英語音源なので発音が変です）
  - OИE
  - 東北ずん子
  - 東北イタコ
  - 星界（SEKAI）
- CeVIO Creative Studio 7
  - さとうささら
  - ハルオロイド・ミナミ
  - Color Voice Series
  - IA
  - OИE

> [!NOTE]
> CeVIO AI すずきつづみソング、キズナ(#KZN)、POPY、ROSE、Ci flower、裏命(RIME)も対応予定です。
> また、VoiSona / CeVIO Pro知声(Chis-A)も対応予定です（[先行対応版](https://github.com/InuInu2022/NodoAme.Home/releases/tag/v.0.3.0-alpha.11)）。

> [!ATTENTION]
> ※CeVIO Creative StudioのIA English C向けソング音源は出力できますが、発音がおかしくなると思います。

- CeVIO Creative Studio 7
  - IA English C (Natural / Powerful)

> [!ATTENTION]
> VoiSona（旧：CeVIO Pro（仮））のtssprjに対応したバージョンを先行で公開しています（[先行対応版](https://github.com/InuInu2022/NodoAme.Home/releases/tag/v.0.3.0-alpha.11)）。

- VoiSona（旧：CeVIO Pro（仮））
  - 知声（tssprj出力）（v0.3先行対応版で対応）

[YouTube video player](https://www.youtube.com/embed/NkF28iJwhxQ ':include :type=iframe width=560px height=315px allowfullscreen')

> [!NOTE|label:詳しい説明はこちら！|iconVisibility:hidden]
> __bi:arrow-down-circle-fill__ [ソングボイスにしゃべらせる](#how_to_do_song_voice_speaking)

### 文章の音素表記・ひらがなを表示する :id=show_phonemes

CeVIOで使われる**音素表記**や**発音通りのひらがな**に変換します。

- 「こんにちは、おはよう」
  - 発音通りのひらがな：「`こんにちわ おはよお`」
  - 音素表記：「`koNnichiwa ohayoo`」

オプションをONにすると、めっちゃむずかしい日本語の発音ルールに合わせて自動でそれっぽく変更します。

どちらかというとソングユーザー向けです。
実はこっそり本命機能。

> [!NOTE|label:詳しい説明はこちら！|iconVisibility:hidden]
> __bi:arrow-down-circle-fill__ [音素を調べる](#how_to_check_phonemes)

### カレーうどんをすする :id=curry_udon

> [!NOTE]
> **__maki:restaurant-noodle__ SUSURU～!**

カレーうどんやカレーそば、カレーラーメンをすすっているような声を出せる、隠し機能です。星界ちゃんにパスタをすすってもらうこともできます。

オプションの中に隠されているボタンを押すと、現在の選択されたソングのキャラ向けに出力します（可不ちゃん以外もOK）。

![susuru](_media/screenshot/susuru.png)

元ネタ：

[可不がカレーうどん食べるだけ](https://ext.nicovideo.jp/thumb/sm39669643 ':include :type=iframe width=560px height=200px scrolling=no frameborder=0 style="border:solid 1px #ccc;"')


## __ic:baseline-notification-important__ 大事なこと :id=important

> [!WARNING]
> とっても大事なことなので、読んでね！

- NodoAmeは素人がつくった、プロトタイプのアプリです。自己責任でおねがいします！
- NodoAmeをつかってパソコンが壊れたり、ハッカーに侵入されたり、カレーうどんの汁が服についても責任はとれません！ノークレーム・ノーリターンでおねがいします！
  - ウィルスとかは確認してるんでたぶん大丈夫だとおもいますが…
- **他のキャラクターの声をマネする仕組み**なので、マネする元のキャラの利用規約は調べてください！
  - もしかすると禁止されてるキャラがいるかも？
  - マネと言ってもAIとかすごい技術は使ってないので大丈夫だとはおもいますが…
- 動画とかで使う場合は「 **演技指導：キャラ名** （**ソフト名**） 」みたいな表記してください
  - 同じキャラでも別のソフトで出ていることがあり、そうなると規約も変わってくるので念のためソフトも書いておいた方がいいと思います！
  - ソフト名・キャラ名の表記が必要な場合もあります！

> [!TIP]
> - CeVIOのキャラ利用規約へのリンク
>   - [CeVIOユーザー互助会](https://w.atwiki.jp/ceviouser/pages/49.html#id_e7e64733)
> - VOICEVOX
>   - [公式ページのキャラ紹介](https://voicevox.hiroshiba.jp/)

- CeVIOトークの外部連携インターフェイスは商用利用に制限があります
  - [※通常の楽曲・動画制作と同じです](https://cevio.jp/commercial/)
  - それ以上は商用ライセンスの購入が必要になります
  - NodoAme自体の商用利用はOKですが、ボイス音源やキャラ、CeVIOの商用利用について、該当する場合は連絡してください

> [!TIP]
> - CeVIO: [音声データやキャラクターの利用について](https://cevio.jp/commercial/)
> - VOICEVOX: [利用規約](https://voicevox.hiroshiba.jp/term)

## __bi:patch-check-fill__ ひつようなもの :id=requirements

### ゼッタイ必要 :id=must_requirements

- Windows 10以降
- CeVIO AI または CS または VoiSona ソングエディター＆ボイス
- .NET Framework 4.8
  - ※CeVIOが動く場合はもう入ってます！

### あったらいいな :id=should_requirements

- CeVIO AIトークエディター＆ボイス
- CeVIO CSトークエディター＆ボイス
- VOICEVOX

## __ic:twotone-install-desktop__ インストール :id=how_to_install

1. [ダウンロードする](#DL)
2. ダウンロードした`NodoAme-v【バージョン名】.zip`ファイルを展開する
3. 展開したフォルダをお好きな場所に置く（おこのみで）
4. フォルダの中の`NodoAme.exe`をダブルクリックして実行

- アップデートは上書きして下さい
- アンインストールはフォルダごと消して下さい

## __ant-design:tool-filled__ つかいかた :id=how_to_use

NodoAmeのつかいかたです。まずは[紹介動画](#movies)をみてね！

> [!NOTE|label:まずはこっち！|iconVisibility:hidden]
> __bi:arrow-up-circle-fill__ [紹介動画](#movies)

### ソングボイスにしゃべらせる :id=how_to_do_song_voice_speaking

![](_media/screenshot/select_soft_voice_styles.png)

1. しゃべりを参考にするために、左上のトークソフト、キャラ、感情・スタイル・プリセットを選ぶ
   1. インストールしていないソフトは選んでも動きません
   2. CeVIOトークはトークエディタとトークボイスがインストールされていなければ動きません
   3. VOICEVOXは事前に起動していてください
2. セリフ入力欄にセリフを入れる
4. 試聴ボタンを押して、しゃべり方を確認する
   1. お好みでパラメータを変える
5. 気に入らなければセリフやパラメータ、キャラを変える
6. いい感じになったら、しゃべらせる**ソング**キャラを選ぶ
   1. ![](_media/screenshot/select_export_song_cast.png 'width=150px')
7. 出力ボタンを押す
8. 出力されたccstファイルをCeVIOで読み取って再生する
   1. 最初の設定では自動でCeVIOが起動すると思います
   2. いくつかダイアログがでますがそのまま進めてください
   3. トラックはミュート状態になってますのでソロに切り替えて再生してください
   4. VoiSona（旧：CeVIO Pro）はtssprj形式です
9.  いい感じにしゃべっていたら、「ソングのwav書き出し」でトラック毎に保存してください！
   5. ファイル名がそのままセリフになるので、[Aviutl+かんしくん](https://oov.github.io/aviutl_psdtoolkit/forcepser.html)や[YMM4のカスタムボイス](https://manjubox.net/ymm4/faq/%E3%82%86%E3%81%A3%E3%81%8F%E3%82%8A%E3%83%9C%E3%82%A4%E3%82%B9/%E5%A4%96%E9%83%A8%E3%81%AE%E9%9F%B3%E5%A3%B0%E5%90%88%E6%88%90%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%B3%E3%81%A7%E4%BD%9C%E6%88%90%E3%81%97%E3%81%9F%E9%9F%B3%E5%A3%B0%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%97%E3%81%9F%E3%81%84/)で自動で取り込むことができます

> [!TIP]
> 楽譜データ、といってますが、実は楽譜（ノート）情報はあまりつかっていません。開いてみるとわかります。


### 発音通りのひらがな・音素を調べる :id=how_to_check_phonemes

> [!NOTE]
※音素を調べるだけなら他のトークソフトは不要です。

1. セリフ入力欄にセリフを入れる
2. 右の音素欄に自動で表示される
3. オプションで音素表示を切り替える
4. セリフを入力し直す
   1. オプションはすぐには反映されません！
   2. スペースを入れるなどしてちょっとだけ変えてください！

![](_media/screenshot/options.png)

- セリフ変換オプション
  - 音素/ひらがな表示：音素表示とひらがな表示をきりかえます
  - スペース区切り：スペースで区切るかどうか
- 音素表示オプション
  - 「ん」を変換する：「ん」を`[n][m][N][n,g]`の4パターンに変換します
  - 「が」を変換する：「が」を`[g][n,g]`の2パターンに変換します
  - 無声母音そのまま/小文字化/削除：最初は大文字で表示される無声母音を変換します

> [!ATTENTION|label:注意]
> 音素表示機能はソングボイスにしゃべらせる機能とは（まだ）**連動していません**！「ん」「が」の連動を予定しています。

## __ic:baseline-school__ 動画を作るのに便利な知識

> [!TIP]
> NodoAmeをつかって動画をつくってみよう！
> キャラクターがセリフに合わせて口パクしてくれる動画はカンタンに作れます！
>
> ↓みたいなゲーム実況動画とかが作れます！

<iframe width="560" height="315" src="https://www.youtube.com/embed/z06983dVjng" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### 動作制作ソフト

> [!NOTE]
> 動画をつくるなら、キャラクターの立ち絵や字幕生成が自動でできるソフトがオススメです。

- [AviUtl + 拡張編集プラグイン](http://spring-fragrance.mints.ne.jp/aviutl/) + [PSDToolKit](https://oov.github.io/aviutl_psdtoolkit/index.html) ※無料
- [YMM4(ゆっくりムービーメーカー4)](https://manjubox.net/ymm4/) ※無料
- [レコッテスタジオ](https://www.ah-soft.com/rs/) ※有料

> [!NOTE]
> いぬいぬのオススメはYMM4です！
>
> NodoAmeを使うときは「 [カスタムボイス機能](https://manjubox.net/ymm4/faq/%E3%82%86%E3%81%A3%E3%81%8F%E3%82%8A%E3%83%9C%E3%82%A4%E3%82%B9/%E5%A4%96%E9%83%A8%E3%81%AE%E9%9F%B3%E5%A3%B0%E5%90%88%E6%88%90%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%B3%E3%81%A7%E4%BD%9C%E6%88%90%E3%81%97%E3%81%9F%E9%9F%B3%E5%A3%B0%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%97%E3%81%9F%E3%81%84/)」を使います！

[YMM4+CeVIO解説](https://www.youtube.com/embed/TlqFEtxLsPE ':include :type=iframe width=560px height=315px allowfullscreen')

### 立ち絵の探し方

[PSDTool](https://oov.github.io/psdtool/)というサイトで使えるようにしたpsd形式の立ち絵が多いです！色々なパーツを組み合わせて表情や口パクなどの演技が簡単にできるようになります！

「キャラクター名 立ち絵」で検索すると見つかります！規約をよく読んで使いましょう！

例： [ニコニコ静画で「可不 立ち絵」で検索](https://seiga.nicovideo.jp/search/%E5%8F%AF%E4%B8%8D%20%E7%AB%8B%E3%81%A1%E7%B5%B5?target=illust&track=seiga_illust_keyword)

[ちぇびおで音楽的同位体な可不たん立ち絵var1.0](https://ext.seiga.nicovideo.jp/thumb/im10864398 ':include :type=iframe width=312px height=176px scrolling=no')

[可不　立ち絵](https://ext.seiga.nicovideo.jp/thumb/im10775264 ':include :type=iframe width=312px height=176px scrolling=no')

[カレーうどん付き可不 立ち絵素材](https://ext.seiga.nicovideo.jp/thumb/im10877460 ':include :type=iframe width=312px height=176px scrolling=no')

[【トークロイド】可不立ち絵素材](https://ext.seiga.nicovideo.jp/thumb/im10888205 ':include :type=iframe width=312px height=176px scrolling=no')

[【立ち絵】可不](https://ext.seiga.nicovideo.jp/thumb/im10888910 ':include :type=iframe width=312px height=176px scrolling=no')

[【立ち絵】デフォルメ 可不](https://ext.seiga.nicovideo.jp/thumb/im10889287 ':include :type=iframe width=312px height=176px scrolling=no')

[デフォルメ立ち絵 いいね押し忘れ防止ver.](https://ext.seiga.nicovideo.jp/thumb/im10809604 ':include :type=iframe width=312px height=176px scrolling=no')

[【立ち絵】知声](https://ext.seiga.nicovideo.jp/thumb/im10906631 ':include :type=iframe width=312px height=176px scrolling=no')


> [!NOTE]
> YMM4で使うためには少し素材の書き出し方に工夫が必要です。
> [立ち絵機能](https://manjubox.net/ymm4/faq/%E7%AB%8B%E3%81%A1%E7%B5%B5%E6%A9%9F%E8%83%BD/)

## ⚠プロトタイプ版の制限 :id=not_support_on_prototype

> [!ATTENTION]
NodoAmeはプロトタイプ版なので、未実装機能やない機能が色々あります！リクエストがあれば機能が増えるかも？

### ソング出力は手動

一応、書き出した楽譜ファイルを自動で読み込んでもらえるようにしました（CeVIO CS/AI）！

ですが、そこから先は手動です…！
CeVIOトークには外部連携インターフェイスが用意されていますが、ソングにはないので自動化が難しいです！

みんなで公式にリクエストを送ろう！

[https://cevio.jp/contact_soft/](https://cevio.jp/contact_soft/)

> [!TIP]
> ccstファイルに関連付けられたソフトが自動起動するので、CSとAI両方持っていると、
> CSの子にしゃべらせたいのにCeVIO AIが起動してしまったりします。
> 開きたいソフトで一度CCSTファイルを開いておく必要があります。
> →「[❔CeVIO CSでしゃべらせたいのに、CeVIO AIが開いてしまいます](#cevio_cs_and_ai_ccst_associate)」

### 「ん」・「が」の使い分け未対応

日本語は「ん」や「が」の発音を使い分けたりしますが、現在未対応です。

「音素表示機能」ではオプションで対応しています。それを参考にすることはできます！

> [!NOTE|label:「音素表示機能」の説明はこちら！|iconVisibility:hidden]
> __bi:arrow-up-circle-fill__ [音素を調べる](#how_to_check_phonemes)

### ~~CeVIO CSソング未対応~~

※[バージョン 0.2 で対応しました！](#dl)

### ~~セリフファイル出力未対応~~

※[バージョン 0.2 で対応しました！](#dl)

セリフはトラックファイル名になるため、そのまま書き出しすれば動画制作ツール（Aviutl+かんしくん/YMM4など）でセリフとして取り込めます。

が、長文など一部対応できない場合があります。
そこでセリフをテキストファイルに出力するように対応しました。

![セリフ保存オプション](./_media/screenshot/save_seriftext_option.png)

`オプション > 保存 > セリフをテキストファイルに保存`に✔をいれてね！

ccstファイルとは別の場所に保存できます。音声ファイルと同じところに置いておくと取り込みに便利です。

テキストファイル名はCeVIOと同じような名前がつけられます！「セリフ保存オプション」を開いて設定してください！
ボタンを押すとカーソル位置に「`$`」で囲まれた文字が入ります。

### CCSファイル出力未対応

まとめてccsファイルで出力する機能を検討しています。

### ~~セリフは最大30行~~

CeVIOは32トラックまでしか読み込めないため30行だけ用意しています。

※[バージョン 0.2 で対応しました！](#dl)

オプションで増やすことができます！（※再起動が必要です！）

### セリフごとのパラメータに未対応

現在はトークソフトの調声パラメータは全体で共通ですが、セリフごとに設定出来るようにする予定です。

### ~~CeVIOの感情合成に未対応~~

※先行公開版のver. 0.3.0 alpha-14から対応しました！

~~CeVIOトークの感情は現在プリセットと同等のもののみ対応です。~~UIつくるの面倒~~ 対応を検討しています!~~

### ~~VOICEVOXのパラメータに未対応~~

※[バージョン 0.2 で対応しました！](#dl)

### セリフやパラメータの保存に未対応

現在は保存する方法が現在ありません。
プロジェクトファイル形式をかんがえてます！

## __ic:baseline-tips-and-updates__ 調声のコツ :id=tips_for_voice_tune

> [!TIP]
> 出力したファイルはCeVIOのソングエディタ上で少し手をくわえるともっと自然になります。

### ブレスを抑える

歌唱の時と同じで、VOLを削ると抑えられます。

![ブレスをおさえる](./_media/screenshot/suppress_breath.png)

VOLモードにしたうえで、ノート（音符）の前や間の山を線でなぞって小さくする（黄色い線）にすると息継ぎは抑えられます。山の大きさでブレスの大きさは変わります。
（一番下で線を引けば音はなりません）。

> [!TIP]
> [先行公開版](https://github.com/InuInu2022/NodoAme.Home/releases/tag/v.0.3.0-alpha.11)で息継ぎブレス抑制機能を追加しています。

[YouTube video player](https://www.youtube.com/embed/kP6wqn2T6Vs ':include :type=iframe width=560px height=315px allowfullscreen')

### 母音無声化しきれない場所を修正

NodoAmeは無声化母音の場所のVOLを自動で削るのですが、たまに削りきれなくて変な音になることがあります。
VOLで削ってください。

### 音がおかしい場所のPITを滑らかにする

急激に変化すると音が機械音ぽくなったり、ノイズっぽくなったりします。その場合はPITの線をなだらかにしてみてください。

### 全体的に声が低くてガビガビ

怒ってる演技などを再現しようとすると、低すぎてガビガビな感じになることがあります。その場合は、PITの線全体を範囲選択して、上にずらしてみてください。

この辺はソングボイスの得意な音域によって変わります。

## __ic:outline-tips-and-updates__ 出力した音声のTIPS :id=tips_for_output_files

> [!TIP]
> 出力された音声はソング用のため、トーク作品で利用するにはひと工夫必要です

### 前後の音声の空白 :id=cut_nosound_space

出力した音声は1小節目から始まるため、前後に空白が開きます。
前は固定で1.3秒くらいの間なので機械的に削ってもいいかもしれません。

> [!TIP]
参考までにYMM4の場合、ボイスアイテムの「再生開始位置」に `00:00:01.3`をコピペでいれるといいです！

> [!NOTE]
将来的にNodoAmeで前後カットする機能を検討してます。その場合は保存先を変えること、セリフファイル出力先をカット後にすることや、`.lab`ファイルの書き換えなどをやる必要性がありそうです。

### エフェクト :id=effect_for_wav

音声は無加工で、通常のトークよりノイズが乗りやすいのでDAWなどで機械的に加工したほうがいいかもしれません！

> [!NOTE]
参考までに、いぬいぬはセリフ数が少ない場合は、
DAWで加工してます。
iZotopeのRXとNectar (dialogプリセット)をかけてます。

## __icons8:todo-list__ やりたいこと :id=i_want_to_do

- 入力
  - [x] CeVIOトークの感情合成対応
  - [x] [VOICEVOX](https://voicevox.hiroshiba.jp/)のパラメータ対応
  - [ ] [COEIROINK](https://coeiroink.com/)への対応
  - [ ] [A.I.VOICE](https://aivoice.jp/) への対応
  - [ ] セリフごとのパラメータに対応
  - [ ] 台本テキストの読み込み
- 出力
  - [x] 標準音声からの出力対応
  - [x] 母音無声化 出力対応
  - [x] カレーうどんをすする 出力対応
  - [x] CeVIO CSソング対応改善
  - [x] VoiSona（旧：CeVIO Pro（tssprj））出力対応
  - [ ] 「ん」の使い分け 出力対応
  - [ ] 「が」の使い分け 出力対応
  - [x] セリフファイル出力
  - [ ] まとめてccsファイル出力
  - [ ] 視聴した音声のファイル出力
  - [ ] 対象キャラに合わせたCeVIO AIとCSの自動起動に対応
  - [ ] CeVIOの読み込み時のダイアログ抑制
  - [ ] 出力音声の前後無音部分クリッピング
  - [x] ブレスOFF、ブレス抑制機能
  - [ ] [NEUTRINO](https://n3utrino.work/)への対応
- 保存
  - [x] オプションの設定保存に対応
  - [ ] セリフやパラメータの保存(プロジェクトファイル)に対応

## __wpf:faq__ よくある質問 :id=faq

### ❔CeVIO Creative Studioのソングはしゃべらせられますか？ :id=cevio_cs_song_support

※[バージョン 0.2 で対応しました！](#dl)

バージョン0.1と同じにしたい場合は、
「KANA」を「PHONEME」に、オプションの中の「MEDIAN」を「FIXED」に変換してください。

### ❔CeVIO CSでしゃべらせたいのに、CeVIO AIが開いてしまいます :id=cevio_cs_and_ai_ccst_associate

Windowsのファイルの「関連付け」で、ccstファイルがCeVIO AIに登録されているためです！
関連付けを変更にするには、ccstファイルを右クリックから「プログラムからひらく」＞「CeVIO Creative Studio」で開くを選んで、
いちどCSで開く必要があります！

> [!ATTENTION]
>アイコンがCSの方の選択肢を選んでください。CeVIO AIも同じ名前になっちゃうバグがあるみたいです。

こうすれば自動でCSで開くようになりますが、今度はAIでは開かなくなります。
（同じ操作をAIでやる必要があります）

めちゃくちゃ面倒なので何とかしたいのですが、仕組み上難しいです。
（専用の拡張子をつくって開くようにする（例：ccstcst ccstai)ならできるんですが…）

### ❔コメント読み上げとかに使えますか？ :id=can_i_use_comment_reading

使えません！

CeVIOソングは自動化できないので、ソング再生は手動になってます。

> [!NOTE]
ソングの出力も自動化できたら、NodoAme自体にもAPIをつけたいです！

CeVIOソングも外部インターフェイスがつくように、みんなで公式にリクエストを送ろう！
[https://cevio.jp/contact_soft/](https://cevio.jp/contact_soft/)

### ❔CeVIO AI以外のボーカルシンセサイザーには対応していますか？ :id=other_vocal_synth

今の仕組みはおそらくCeVIO CS/AI/Pro（仮）でしかつかえません。
トークロイドでよく使われる楽譜の使い方をしていない為、ccsファイルを変換してもおそらく発音できないと思います。

※Synthesizer Vはもしかしたら変換すれば動くかも？わかりません！

NEUTRINOはMusicXMLを経由しなければ意外と簡単にいけるかも？調査中です！

リクエストがあれば対応するかも？

### ❔演技指導のトークソフトはCeVIO以外に対応していますか？ :id=support_talksoft

NodoAmeは [SHABERU](http://akihiro0105.web.fc2.com/Downloads/Downloads-SHABERU.html)/[Open JTalk](https://open-jtalk.sp.nitech.ac.jp/)などで使われるボイス音源（`htsvoice`形式の音響モデル）に対応しています。標準男声はatr503_m001、標準女声はtohoku-f01です。利用する場合はキャラクターのボイス音源のライセンスを確認して下さい。

- 追加ボイス音源の入手先
  - [SHABERU 追加音響モデル](http://akihiro0105.web.fc2.com/Downloads/Downloads-htsvoice.html)
  - [Open JTalk の音響モデルを試す](https://petile.com/mahoroba/e1875.html)

NodoAmeは無料のトークソフト [VOICEVOX](https://voicevox.hiroshiba.jp/) にも対応しています。

- **VOICEVOX**
  - 利用の際はVOICEVOXを先に起動しておいてください

COEIROINKはもしAPIの一部機能が対応したら、対応します。

- **COEIROINK**
  - API側が対応され次第、対応予定です
    - ※音素表示と視聴は対応済。
  - 利用の際はCOEIROINKを先に起動しておいてください


---
まとめるとこんな感じです。

- 対応済みトーク音源
  - `htsvoice`形式の音響モデル
- 対応済みトークソフト
  - VOICEVOX
- 対応予定トークソフト
  - COEIROINK
- 検討中トークソフト
  - A.I.VOICE

#### それ以外のトークソフト対応について :id=other_talk_soft

CoeFontはAPIが公開されているのですが、利用したい情報がとれないっぽいです。
LMROIDはAPIがあるのですがCOEIROINKとおなじでタイミング情報がとれません。
A.I.VOICEはAPIが公開されたのですが、そのままではやはり利用したい情報がとれず、再考中です。ただし、labファイル出力に対応したのでやり方を検討注です。

考えてるアイディアがうまく行けば、VOICEROIDや生声音声もうまくいくかもしれません。ただし、精度は落ちるかもです…。

> [!NOTE]
> APIが公開されてるトークソフトだけ検討します。
> NodoAmeが利用するのは音素情報（発音情報）とタイミング情報です。
> 一応出力された音声から推定する方法もあることはあるんですが…

#### 生声を真似することはできる？ :id=human_voice

一応、仕組み的にはできそうです！
でも！精度は落ちそうです！
いぬいぬの実力では無理です…。

### ❔CeVIOがインストール済なのに「みつかりません」って出る :id=cevio_not_found_but_installed

> [!NOTE]
> 演技指導としてCeVIOトークを利用する場合です。演技指導をCeVIOトーク以外にする場合は関係ありません。

NodoAmeはCeVIOが普通にインストールされてる前提になってます。なので、**普通と違う場所にインストールしているとみつけられずに動きません**！

ただし、**ちょっと設定ファイルをかきかえると、うごくかも**しれません！

まず、NodoAmeが動いていたら、終了してください！

次に、NodoAme本体の`NodoAme.exe`があるところに`NodoAme.Settings.json` というファイルがあります！
このファイルをメモ帳なんかで開いて下の場所を探してください。

```json
			"id":"1",
			"name":"CeVIO AI",
			"hidden":false,
			"enabledPreview":true,
			"enabledExport":true,
			"interface":{
				"type":"API",
				"engine":"CeVIO",
				"dll":"CeVIO.Talk.RemoteService2.dll",
				"dll_dir":"/CeVIO/CeVIO AI/",
				"env_prog":"%ProgramW6432%",
				"service":"CeVIO.Talk.RemoteService2.ServiceControl2",
				"talker":"CeVIO.Talk.RemoteService2.Talker2",
				"agent":"CeVIO.Talk.RemoteService2.TalkerAgent2"
			},
```

ここの`"env_prog":"%ProgramW6432%",`（や、必要なときには`"dll_dir":"/CeVIO/CeVIO AI/"`）をかきかえると動くようになります。

たとえば、次のようになります。

- CeVIO AIが `D:/CeVIO/CeVIO AI/CeVIO AI.exe` にある場合
  - `"env_prog":"%ProgramW6432%",` → `"env_prog":"D:",` にかきかえる
- CeVIO AIが `C:/Program Files/MyCeVIO/CeVIO AI.exe` にある場合
  - `"dll_dir":"/CeVIO/CeVIO AI/",` → `"dll_dir":"/MyCeVIO/",` にかきかえる

かきかえたら保存して、NodoAmeをもう一度起動してみてください！
CeVIO CSもおんなじ感じでできます。

`NodoAme.Settings.json`が上書き禁止になっているときは、ファイルを選んで右クリック→プロパティから上書きOKに設定して下さい。

> [!ATTENTION]
ちなみに、今は上書きインストールすると消えちゃいます！
アップデートのときは上書きインストールしたあとにもう一度設定書き換えてください！

### ❔CeVIOがインストール済みなのに「CeVIOトークがみつかりません」と出る :id=ceviotalk_not_found

CeVIOトークを持っていないのに、**左上の**トークソフトプルダウンで「CeVIO」を選んでいるとこのエラーになります。
CeVIOトークはCeVIOソングとは別物で、トークエディタとトークボイスを別に購入する必要があります。

> [!ATTENTION]
> **左上の**プルダウンにはソングのキャラクター（可不など）はいません！
> **ソングのキャラクターは右上**のプルダウンから選んでください

単純にCeVIOソングをしゃべらせるだけなら、CeVIOトークは必要ありません。
左上のトークソフトのプルダウンで、内蔵の「標準トーク」を選んでください。※無料のVOICEVOXをインストールして利用する方法もあります。

>例：
>演技指導を「標準トーク」の「標準女声」、しゃべるボイスを「CeVIO AIソング」の「可不」にする場合
>
>![talk_soft_example](_media/screenshot/nodoame_tokksoft_example.png)
>- 左上のプルダウン：
>    -「標準トーク」「標準女声」「普通」
>- 右上のプルダウン：
>    -「CeVIO AI KAFU」「PHONEME」



### ❔VOICEVOXがインストール済なのに使えない :id=voicevox_not_launched

> [!NOTE]
> 演技指導としてVOICEVOXを利用する場合です。演技指導をVOICEVOX以外にする場合は関係ありません。

- **VOICEVOXはNodoAmeから利用する前に起動しておいてください！**
  - NodoAmeにはVOICEVOXを起動する機能はありません
- **起動しているのに通信できない**、と出る場合は
  - VOICEVOXを再起動してみてください
  - VOICEVOXのエンジンが
- ポート番号を変えている場合は**設定ファイルを書き換えると動くかも**しれません！

まず、NodoAmeが動いていたら、終了してください！

次に、NodoAme本体の`NodoAme.exe`があるところに`NodoAme.Settings.json` というファイルがあります！
このファイルをメモ帳なんかで開いて下の場所を探してください。

```json
			"id":"3",
			"name":"VOICEVOX",
			"hidden":false,
			"enabledPreview":true,
			"enabledExport":true,
			"interface":{
				"type":"REST",
				"engine":"VOICEVOX",
				"restHost":"http://localhost:50021/"
			},
```

ここの` "restHost": `のあとのURLの部分を書き換えると動くようになるかもしれません。
`50021`の数字を、変えたポート番号に書き換えてください！

### ❔「⚠」のついてる選択肢は何ですか？ :id=whats_attension_mark

対応がまだちゃんとしてない場合についてます！
一応選べることは選べるんですが…。

アプデをまっててね！

### ❔CeVIOのトークエディタで細かく調声したデータはマネさせられますか？ :id=detailedtune_on_cevioeditor

現在はできません！
むずかしいですけど、リクエストがあれば将来的な対応を考えるかも？

### ❔英語はしゃべらせられますか？ :id=english_speaking

先行公開版（ [v.0.3.0-alpha.16](https://github.com/InuInu2022/NodoAme.Home/releases/tag/v.0.3.0-alpha.16) ）で、英語のトーク音源（CeVIO AIトーク弦巻マキEnglish）に演技指導してもらうことで、
ウソ英語がしゃべれるようになりました。

[YouTube video player](https://www.youtube.com/embed/f2qonxX0YMs ':include :type=iframe width=560px height=315px allowfullscreen')

「EN_TO_JA」を選択してください。


英語トーク音源→英語ソング音源はうまくいきます（例：弦巻マキトークEnglish→IAソングEnglish）。この場合は「PHONEME」を選択してください。

[YouTube video player](https://www.youtube.com/embed/XknZFUlhMWE ':include :type=iframe width=560px height=315px allowfullscreen')

### ❔ラップやポエトリーリーディングに使えますか？ :id=rap_and_poetry

難しそうです…。

BPMが150固定とか、あとからの手直しにはあまり向いてない方法（PIT/TMG/VOLで再現）なので難しいです。

セリフ全体の長さは一応変更できますが、書き出してみないと長さがわからないですし（リクエストがあれば一応表示できます）、リズムに合わせるほど細かい調声はできません。

波形データに書き出して、DAW上で加工するならできるかも？

### ❔Macで動きますか？ :id=nodoame_on_mac

うごきません！

### ❔CeVIOトークを歌わせることはできますか？ :id=can_sing_cevio_talk

できません！

CeVIO Creative Studioなら[CevioTalkSync](https://www.nicovideo.jp/watch/sm37419010)というソフトがあります！

### ❔トークtoトークはできますか？ :id=can_convert_talk_to_talk

いまのところできません！

ソングに比べると、指定できるパラメータがすくなかったり、ざっくりだったりして、再現が難しそうです…。

## __tabler:license__ ライセンス :id=licenses

```txt
The MIT License
Copyright (c) 2022 InuInu
```

MIT Licenseです。

ニコニコ動画などでこのツールを使った動画を公開する場合は、以下のニコニコモンズをコンテンツツリーに登録して下さい！（義務ではありません）

[nc262424](https://commons.nicovideo.jp/material/nc262424)

全文や使用ライブラリなどのライセンスはNodoAmeのインストールされたとこの `Licenses` フォルダー以下をご覧くださーい！

## __fa-solid:history__ きろく :id=history

- ver. 0.3.0 alpha-25 : アイコン追加、POPY・ROSE対応
- ver. 0.3.0 alpha-23 : VoiSona対応
- ver. 0.3.0 alpha-20 : セリフ秒数表示機能追加
- ver. 0.3.0 alpha-16 : ウソ英語機能追加
- ver. 0.3.0 alpha-14 : CeVIOトーク 感情合成機能対応
- ver. 0.3.0 alpha-11 : 息継ぎブレス抑制機能追加 先行公開
- ver. 0.3.0 alpha-10 : VoiSona (旧:CeVIO Pro)tssprj対応 先行公開
- ver. 0.2.0 : バージョンアップ
  - いっぱい対応
  - CeVIO CSソング対応改善
  - VOICEVOXのパラメータに対応
  - CeVIO AI東北ずん子・東北イタコ サポート
  - セリフのテキスト出力機能追加
  - セリフのひらがな変換表示機能追加
  - セリフ行を増やすオプション追加
  - 公式サイトを開くボタン追加
  - あと、いろいろなバグをなおしたよ！
- ver. 0.1.4 : 標準女声のスタイルが記録されてなかったのを修正 [#3](https://github.com/InuInu2022/NodoAme.Home/issues/3)
- ver. 0.1.3-alpha.0.1 : 同梱マニュアル更新（公式サイトへ誘導）
- ver. 0.1.2 : COEIROINKを選択肢に表示しないように
- ver. 0.1.1 : 出力時にアプリがおちちゃう不具合修正 [#2](https://github.com/InuInu2022/NodoAme.Home/issues/2)
- ver. 0.1.0 : MATSURIに合わせてプロトタイプ版リリース

## __ant-design:star-filled__ スペシャルサンクス :id=speacialthanks

- たらそば さん [@tarasoba9672](https://twitter.com/tarasoba9672)
- かりんと さん

## 🐶つくった :id=developedby

- InuInu（いぬいぬ）
  - __fa-brands:youtube__ [YouTube](https://bit.ly/InuInuMusic)
  - __ant-design:twitter-circle-filled__ [@InuInuGames](https://twitter.com/InuInuGames)
  - __carbon:blog__ [note.com](https://note.com/inuinu_)

<iframe width="320" height="160" src="https://ext.nicovideo.jp/thumb_user/98013232" scrolling="no" style="border:solid 1px #CCC;" frameborder="0">いぬいぬGames</iframe>
