# Awesome Tsukuba

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Lint](
  https://github.com/Make-IT-TSUKUBA/awesome-tsukuba/actions/workflows/lint.yml/badge.svg
)](
  https://github.com/Make-IT-TSUKUBA/awesome-tsukuba/actions/workflows/lint.yml
) [![pages-build-deployment](
  https://github.com/Make-IT-TSUKUBA/awesome-tsukuba/actions/workflows/pages/pages-build-deployment/badge.svg
)](
  https://github.com/Make-IT-TSUKUBA/awesome-tsukuba/actions/workflows/pages/pages-build-deployment
)

筑波大学に関連する便利なツール・サイト・スマホアプリなどをまとめています。
プルリクエストは歓迎です。自分のプロジェクトを掲載されたくない、消して欲しいなどの要望があればすぐに対応します。

## 目次

- 公式サービス
  - Webサービス・Webサイト
  - クラウドサービス
  - ネットワーク
  - ライセンス付与・割引
- 公式サービス関連ツール（非公式）
  - KdB
  - manaba
  - PaperCutMF
  - Tulips
- シチュエーション別ツール
  - 履修スケジュール確認
  - 卒業要件、移行要件確認
  - 交通機関
  - その他
- ライブラリ・モジュール・パッケージ
- イベント
  - アドベントカレンダー
  - トークイベント・LT会
- 情報収集
  - フィード・RSS
  - Twitter Bot
- 学生団体
- 講義

## 公式サービス

### Webサービス・Webサイト

- [Tulips](https://www.tulips.tsukuba.ac.jp/lib/) - 附属図書館のサイト。蔵書の検索や、自分が借りている書籍一覧、貸出延長などがWeb上で行える。
- [生涯メールアドレス](https://futureship.sec.tsukuba.ac.jp/alumni/mail/) - 筑波大学を卒業しても一生使えるGsuiteアカウントが作成できる。
- [筑波大学カード](https://futureship.sec.tsukuba.ac.jp/tsukubacard/) - 年会費無料のクレジットカードで、大学付近店舗で優待がある。
- [つくばリポジトリ](https://tsukuba.repo.nii.ac.jp) - 筑波大学で生み出された研究・教育成果を永続的に蓄積・保存し、インターネットを通してどなたでも無料にアクセスできるように公開する学術コンテンツデータベース。

### クラウドサービス

- [sメール](https://cloudmail.u.tsukuba.ac.jp/) - 大学で利用できるメールアドレス。
- [ホーム使用量確認・増量](https://www.u.tsukuba.ac.jp/disk/) - ホームディレクトリの容量を増量申請できる。
- [OneDrive for Business](https://onedrive.live.com/about/ja-jp/signin/) - 1TBまでOnedriveが利用できる。
- [リモートアクセス](https://www.u.tsukuba.ac.jp/remote/) - 大学の共用パソコンにVNCやブラウザからリモートデスクトップが行える。

### ネットワーク

- [VPNサービス](https://www.cc.tsukuba.ac.jp/wp/service/vpn/) - 大学学内からのみアクセスできるページに大学学外からアクセスできる。
- [Wi-Fi](https://www.cc.tsukuba.ac.jp/wp/service/wireless/) - 学内のWi-Fiアクセスポイント。802.1x接続も可能。
- [eduroam](https://www.cc.tsukuba.ac.jp/wp/service/eduroam/) - eduroamに加盟している他の大学に行った時、その大学でWi-Fiを利用できる。

### ライセンス付与・割引

- [SPSS サイトライセンス](https://www.cc.tsukuba.ac.jp/wp/service/sl/spss/) - 統計解析ソフトウェアの有償ライセンスが無料で利用できる。
- [Mathematica サイトライセンス](https://www.cc.tsukuba.ac.jp/wp/service/sl/mathematica/) - Mathematica for Studentsが無料で利用できる。
- [Microsoft 製品 (EES 特典：個人使用)](https://www.cc.tsukuba.ac.jp/wp/service/sl/ees/tokuten/) - Microsoft Officeが無料でインストールできる。
- [MS Surface](https://www.cc.tsukuba.ac.jp/wp/service/surface/) - Surfaceを割引価格で購入できる。
- [Apple On Campus (AOC)](https://www.cc.tsukuba.ac.jp/wp/service/apple-on-campus/) - Apple製品を割引価格で購入できる。

## 公式サービス関連

### KdB

#### CLI

- [kdb-parse](https://github.com/Mimori256/kdb-parse) - kdbのデータをjsonにする。

#### Webサービス・Webサイト

- [KDBもどき](https://make-it-tsukuba.github.io/alternative-tsukuba-kdb/) - KDBの代替サービス。フロントエンドのみで動作する。KDBより検索が高速。
- [sylms Explorer](https://sylms-explorer.open.coins.tsukuba.ac.jp/) - KDBの代替サービス。独自のデータベースとAPIを持っている。KDBより検索が高速。
- [KDBシラバスミラー](https://github.com/Make-IT-TSUKUBA/alternative-tsukuba-syllabus/) - KDBが保存しているシラバスページをミラーするサイト。KDBもどきから表示できる。

### manaba

#### CLI

- [manaba-attend](https://github.com/shuuji3/manaba-attend) - Manabaの出席カード(respon)の提出を自動化するプログラム。
- ~[atmnb (終了)](https://github.com/qqpann/atmnb)~ manaba出席のコマンドラインツール、Node.js版。

#### GUIアプリケーション

- [Manaba Scoring](https://github.com/a3suger/manaba_scoring) - manabaのレポート採点業務を支援するアプリケーション。

#### ブラウザ拡張

- [manaba Enhanced (Chrome)](https://chrome.google.com/webstore/detail/manaba-enhanced-for-tsuku/fldngcbchlbfgbccilklplmhljilhfch) - manabaの課題を色分けしたり、外部リンクのポップアップを消したり、コースのフィルタリングが行える。
- [Manaba Report Integration by Twin:te (Chrome)](https://chrome.google.com/webstore/detail/manaba-report-integration/gbcijpgbppbphpikpdohpgmpcgdemnai?hl=ja) - manabaの課題をGoogle TasksやTrelloと同期できる。
- [manaba2kdb (Chrome)](https://chrome.google.com/webstore/detail/manaba2kdb/ladninjcfokoplngpcmlfkijickcoanc) - manabaの科目番号をシラバス（KDB）へのリンクにする。
- [Tsukuba-syllabus (Chrome)](https://chrome.google.com/webstore/detail/tsukuba-syllabus/jplphmfnjbhjiibolbkbadnnjmoipjeb) - manabaのコースページにシラバス（KDB）へのリンクを追加する。
- [modern-manaba (Chrome)](https://chrome.google.com/webstore/detail/modern-manaba/oimcohooopcpjnmdgijjicdhkifopbli) - manabaのUIを変更し、使いやすさを向上させる。
- [Hide unsubmitted reports on Manaba (Chrome)](https://chrome.google.com/webstore/detail/hide-unsubmitted-reports/mgacphidgkikglalmfcfhebhppokoeim) - manaba上の'未提出課題'から任意の課題を隠す拡張機能。
- [self-esteem (Chrome)](https://github.com/yudukikun5120/self-esteem) - manabaの成績ページで相対位置をパーセントで表示する。- [Manaba Local Time (Userscript)](https://github.com/onokatio/manaba-local-time) - manabaにJSTと共にブラウザの現地時刻を併記します。

### PaperCut MF

#### CLI

- ~[Papercut-Submit (終了)](https://github.com/kajyuuen/Papercut-Submit)~ - 全学計算機のプリンタにファイルをアップロードするスクリプト。
- ~[utprint (終了)](https://github.com/qqpann/utprint)~ - 全学計算機PaperCut Printのコマンドラインツール、Node.js版。
- ~[tsukuba-me](https://github.com/qqpann/tsukuba-me)~ Univ. of Tsukuba utils: Manama attend, and Zengaku Printer Upload (PaperCut). [npm](https://www.npmjs.com/package/tsukuba-me)

### TWINS

#### CLI

- ~[twins (長期間未更新)](https://github.com/coins13/twins)~ -  Command-line interface to TWINS。

#### Webサービス・Webサイト

- [twins-notification](https://github.com/shuuji3/twins-notification) - 筑波大学のTwinsの掲示板のお知らせを通知してくれるプログラム。

#### ブラウザ拡張

- [Put kdb link to twins subjects (Chrome)](https://chrome.google.com/webstore/detail/put-kdb-link-to-twins-sub/ddamljpbkecmjljapdkpepibancdiljd) - twinsの科目番号をシラバス（KDB）へのリンクにする。
- [TWINS Enhanced (Userscript)](https://github.com/mkobayashime/twins-enhanced) - しばらく操作しないときにtwinsから自動ログインされるのを防ぐ。
- [userscript-twins-insert-article-url-button (Userscript)](https://github.com/shuuji3/userscript-twins-insert-article-url-button) - 筑波大学のtwinsに「個別のお知らせページを開くボタン」と「他人と共有できるURLをコピーするボタン」を追加するスクリプト。

### Tulips

#### ブラウザ拡張

- [tulips2calil](https://github.com/eniehack/tulips2calil) - 大学附属図書館の蔵書検索ページにcalilへのリンクを追加する。

## シチュエーション別

### 履修スケジュール確認

#### アプリ

- [Twin:te (iOS, Android)](https://www.twinte.net/) - 筑波大生専用時間割アプリ。PCからログインも行える。

#### Webサービス・Webサイト

- [Twinkle](https://app.twinkle.nandenjin.com/) - 履修している授業を登録すると、Googleカレンダーと連携し授業の予定を自動登録してくれる。
- [TwinCal](https://cal.tsukuba.io/) - 履修している授業を登録すると、カレンダーファイル（.ics）を出力でき、GoogleカレンダーやAppleカレンダーなどにインポートできる。
- [TwinC](https://mimori256.github.io/twinc/#/) - 履修している授業を登録すると、カレンダーファイル（.ics）を出力でき、GoogleカレンダーやAppleカレンダーなどにインポートできる。

### 卒業要件、移行要件確認

#### Webサービス・Webサイト

- [筑波大学 総合学域群 移行要件チェックツール](https://boke.itsu.dev/scs-migration-checker/) - 総合学域群から他学科への移行要件をチェックできるツール。
- [そつぎょうできるかな](https://oshamashama.github.io/g-checker-for-itf/) - twinsからエクスポートしたcsvを読み込み、卒業や進級の履修要件に沿って単位修得ができているか確認できるツール。

#### アプリ

- ~[EscapeGoat(終了)](https://github.com/makky3939/EscapeGoat)~ - 知識情報・図書館学類生向けの卒業判定アプリ。

#### CLI

- [klis-unicalc](https://github.com/Gild-shogi/klis-unicalc) - Klis用の他主専攻科目の残り単位数を計算するプログラム。

### 学内地図、交通

#### Webサービス・Webサイト

- [筑波大学 自販機 Map](https://itf-vendingmachine.vercel.app/) - 筑波大学構内の自動販売機の場所を一覧できるサイト。
- [BusVis](https://busvis.herokuapp.com/) - 大学循環バスの現在位置や時刻表がわかるサイト。

#### アプリ

- [えりたんBot (iOS, Android)](https://eritanbot.net/) - キャンパスマップや循環バスの時刻表や授業の教室検索が行えるアプリ。
- [筑波大学 面積比較アプリ (Android)](https://play.google.com/store/apps/details?id=info.nakajimadevnakajima.tsukubaunivcompare) - 筑波大学の面積をGoogle Map上で体感できるアプリ。
- ~[つくばモデルアプリ(終了)](https://www.newforestar.com/tsukubamodelapp/)~ - 大学循環バスの現在位置や時刻表がわかるアプリ。
- ~[iTsukuba(終了)](https://app-liv.jp/1399122/)~ - 時間割の管理やバスの時刻表がわかるアプリ。
- ~[つくポン(終了)](https://iphone.308413110.com/ranking/detail/828517891/)~ - 大学の時刻表や当日の天気、授業開始時刻のカウントダウンができるアプリ。

### その他

#### Webサービス・Webサイト

- [A+つくば](https://www.aplus-tsukuba.net/) - 講義に関するわからない点を匿名で質問でき、他の学生に回答してもらえるサービス。
- [Klis Statistics](https://argonism.github.io/KlisStatistics/) - klisの成績分布・授業評価がグラフィカルに表示できるサイト。
- ~[Welcoins (長期間未更新)](https://github.com/coins13/welcoins)~ - 新歓合宿および懇親会の出欠確認、出欠統計が行える簡易登録フォーム。
- [self-esteem Grade Millefeuille](https://yudukikun5120.github.io/self-esteem-millefeuille/) - twins からエクスポートした CSV を読み込み、自分の成績分布を視覚化する。
- [筑波大学新歓Web](https://www.stb.tsukuba.ac.jp/~shinkan-web/) -  筑波大学のサークル等の団体の情報をまとめたポータルサイト。 [ソース](https://github.com/tsukuba-shinkan)
- ~[桐の葉(終了)](https://github.com/himkt/kirinoha)~ - 科目検索サービス。

#### アプリケーション

- ~[Tsukuba mate(終了)](https://github.com/MuShare/Tsukuba-iOS)~ - 筑波大生向けのフリマアプリ。

## ライブラリ・モジュール・パッケージ

### KdB

- [twinte-parser (npm)](https://www.npmjs.com/package/twinte-parser) - Twinte内部で利用するために開発された KdB のパーサー。
- [twinkle-parser (npm)](https://www.npmjs.com/package/twinkle-parser) - Parse CSV from `https://kdb.tsukuba.ac.jp` to structured JSON.

### その他

- [ITF-Dic](https://github.com/nandenjin/itfdic) - MeCabで利用できる、筑波大学の独自語を自然言語解析辞書にまとめたもの。
- ~[twins-core (npm, 終了)](https://www.npmjs.com/package/twins-core)~ - Wrapper API Client of TWINS.

## イベント

### アドベントカレンダー

#### 2021

- [筑波大学 Advent Calendar 2021](https://adventar.org/calendars/6472)
- [mast Advent Calendar 2021](https://adventar.org/calendars/6614)
- [klis Advent Calendar 2021](https://adventar.org/calendars/6617)

#### 2020

- [coins20 Advent Calendar 2020](https://adventar.org/calendars/6010)

### トークイベント・LT会

#### mastLT

- [mastLT #2](https://togetter.com/li/296599)
- [mastLT #5](https://ko31.github.io/atnd-archive/event/49644.html)
- [mastLT #6](https://togetter.com/li/818833)
- [mastLT #7](https://twipla.jp/events/211202)

#### coinsLT

- [coinsLT 0](https://atnd.org/events/51236)
- [coinsLT 1](https://connpass.com/event/10073/)
- [coinsLT 10](https://connpass.com/event/10782/)
- [coinsLT 11](https://coinslt.connpass.com/event/17415/)
- [coinsLT 110](https://connpass.com/event/152289/)
- [coinsLT 111](https://connpass.com/event/173974/)

#### esysLT

- [esysLT #1](https://togetter.com/li/661516)
- [esysLT #2](https://togetter.com/li/730719)
- [esysLT #3](https://togetter.com/li/822356)

#### ITF.競プロCTF勉強会

- [第二回](https://atnd.org/events/73804)

#### その他

- [情つくば](https://twitter.com/inftsukuba) [Youtube](https://www.youtube.com/channel/UCgNjwsxZCf4EInQuu06ZuUA)
- [春日LT](https://ko31.github.io/atnd-archive/event/87734.html) [Youtube](https://www.youtube.com/watch?v=oF6cuDEdlPY)

## 情報収集

### Twitter Bot

- [えりたんBOT @eritanbot](https://twitter.com/eritanbot) - 循環バスの時刻表や授業の教室検索が行えるbotアカウント。スマホアプリも存在する。
- [筑波大学 学生お役立ち情報(自動向け投稿アカウント) @Utsukuba_auto](https://twitter.com/Utsukuba_auto) - 学内のセンターやサイトの新着情報を自動投稿する。
- [筑波大学附属図書館 / 新着資料非公式Bot @tulipsnewbooks](https://twitter.com/tulipsnewbooks) - 図書館の新着資料を自動投稿する。[ソース](https://github.com/eggplants/nowlibcraw)
- ~[ITF.授業通知bot @itf_notify (更新停止)](https://github.com/himkt/bulletin_bot)~ - 筑波大学・大学院の授業に関する掲示をTwitterでお知らせするBot。[ソース](https://github.com/himkt/bulletin_bot)

### フィード・RSS

#### 全学生向け

- [Twins掲示板 在学生へのお知らせ](https://mkobayashime.github.io/twins-announcements/twins-announcements-atom1.xml)
- [筑波大学 公式サイト ニュース](https://www.tsukuba.ac.jp/news/rss)
- [筑波大学 情報環境機構 学術情報メディアセンター](https://www.cc.tsukuba.ac.jp/wp/feed/)
- [筑波大学保健管理センター](https://www.hokekan.tsukuba.ac.jp/feed)
- [筑波大学厚生会 福利厚生施設案内](https://kosei.sec.tsukuba.ac.jp/feed/)
- [筑波大学体育センター](https://www.sapec.tsukuba.ac.jp/?feed=rss2)
- [全学計算機システム](https://www.u.tsukuba.ac.jp/feed/)

#### イベント

- [筑波大学 スポーツデー](https://www.spoday.info/feed/)
- [中央アジア・日本人材育成プロジェクト](https://centralasia.jinsha.tsukuba.ac.jp/feed)
- [筑波大学スチューデントサポートセンター](https://ssc.sec.tsukuba.ac.jp/feed)

#### その他

- [筑波大学基金](https://futureship.sec.tsukuba.ac.jp/news/rss)
- [筑波大学学生相談室](https://soudan.sec.tsukuba.ac.jp/feed)
- [筑波大学　オープンファシリティー推進機構](https://openfacility.sec.tsukuba.ac.jp/public/feed/)
- [筑波大学 春日地区クラス代表者会議](https://www.stb.tsukuba.ac.jp/~kasuga-campus/feed)

## 学生団体・サークル・有志など

大学内に存在するソフトウェア開発を行う団体や、プログラマーっぽい人が集まる団体、授業などについて。

- [筑波大学を便利にする会](https://mit.tsukuba.me/)
- [open-coins](https://www.open.coins.tsukuba.ac.jp/) - 学類の使わなくなった古い計算資源を用いてサービスを提供する団体。学類共同マシンの起動中OSをオンラインで確認できるサービスなどがある。
- [全代会 総務委員会 情報部門](https://www.stb.tsukuba.ac.jp/~zdk/home/committee_gen)
- [筑波大学学園祭実行委員会 情報メディアシステム局](https://sohosai.com/committee)
- [筑波大学情報科学類誌 WORD編集部](https://www.word-ac.net/)
- [情つくば](https://twitter.com/inftsukuba)
- [OpenEsys](https://ayu.open.esys.tsukuba.ac.jp/)
- [AC部屋](http://www.ac-room.org/)
- ~[COINS Project(終了)](https://web.archive.org/web/http://coins-p.cs.tsukuba.ac.jp/)~ - coins学生によるサービス開発グループのサイト。

## 講義

- [情報特別演習I](https://kdb.tsukuba.ac.jp/syllabi/2022/GB13312/jpn/0/)
- [情報特別演習II](https://kdb.tsukuba.ac.jp/syllabi/2022/GB13322/jpn/0/)
- [情報科学特別演習](https://kdb.tsukuba.ac.jp/syllabi/2022/GB13332/jpn/0/)
- [COJT](http://www.cojt.or.jp/tkb/)
- [enPiT](https://enpit.coins.tsukuba.ac.jp/about/)
