限界散歩 - 高専祭のQR体験展示
公開日: 2026-10-22（日本時間）

公開サイト: https://harr-m.github.io/kosen-qr-walk/
ソース: https://github.com/harr-m/kosen-qr-walk

読むだけの4カ所向け展示（2026-10-23追加）
一覧: https://harr-m.github.io/kosen-qr-walk/notice/
単位が落ちています。: https://harr-m.github.io/kosen-qr-walk/notice/credit.html
端末の更新が必要です。: https://harr-m.github.io/kosen-qr-walk/notice/update.html
高速Wi-Fi、無料開放中。: https://harr-m.github.io/kosen-qr-walk/notice/wifi.html
見出しなしのQR: https://harr-m.github.io/kosen-qr-walk/notice/mystery.html
一般来場者向けの言葉遣いで、読むだけで完結します。ゲーム、クイズ、点数、カメラ、入力欄はありません。
OSだけ30秒のカウントダウンがありますが、期限後も何も実行せず、更新・ダウンロードはしません。
JavaScript無効でも全ての文章が読めます（カウントダウンだけ動きません）。
更新はnotice/内の各HTMLを編集してmainへコミットしてください。公開パスを変えなければQRを再印刷せずに更新できます。
update.htmlのJavaScriptを変える場合は、冒頭CSPのscript-srcのSHA-256ハッシュも更新してください。本文だけの編集では不要です。
notice-print/には4種類のPNG/SVGと、A4縦2枚ずつ・全2ページの印刷用PDFを配置します。
4枚目は見出しを付けず、学生制作の表記とURLを下部に小さく載せています。
以前のwarning.htmlも穏やかな文章に更新しました。既存のindex.htmlと6体験のQRの行き先は変更していません。

学生制作の架空体験です。学校の手続き案内や学校公認を示すものではありません。
来場者のログイン・アプリ導入は不要です。HTML/CSS/JavaScriptだけで動きます。
GitHub Pagesの無料github.io URLを使用し、サーバー、DB、独自ドメインはありません。

6つの入口
無料単位配布センター: https://harr-m.github.io/kosen-qr-walk/#credit
正気OSの緊急更新: https://harr-m.github.io/kosen-qr-walk/#update
最強無料Wi-Fi: https://harr-m.github.io/kosen-qr-walk/#wifi
このQR、二枚あります: https://harr-m.github.io/kosen-qr-walk/#sticker
空中の単位をつかまえる: https://harr-m.github.io/kosen-qr-walk/#unit
ここに理性ねむる: https://harr-m.github.io/kosen-qr-walk/#reason

ファイル
index.html: 6体験の文章、HTML、CSS、JavaScript。通常の更新はこの1ファイルを編集します。
.nojekyll: 空ファイルのまま残してください。
print/qr/: 確定した公開URLを符号化したPNG/SVG各6種類。
print/kosen-qr-掲示用.pdf: A4縦、1ページ2枚、計3ページ。白黒印刷で使用できます。
print/公開URL一覧.txt: QR、印字URL、PDFリンクと共通のURL一覧。

更新方法
1. GitHubのこのリポジトリで、読むだけの展示はnotice/内の各HTML、元の6体験はindex.htmlを開き、鉛筆ボタンから編集します。
2. mainブランチへコミットします。ローカル編集なら同じmainへgit pushします。
3. Actionsの「pages build and deployment」が成功し、サイトに反映されたことを確認します。
公開元はmainブランチのルートです。HTTPSを有効にしています。
アカウント名、リポジトリ名、Pages公開設定、6つの#名を変えなければ印刷済みQRを継続利用できます。
index.htmlの名前をfield.htmlへ変えないでください。

情報の扱い
本物のパスワード、学生情報、カード情報を入力・収集する機能はありません。
実際の支払い、Wi-Fi設定変更、アプリ導入、強制ダウンロードはありません。
カメラは「カメラを使う」を押した場合だけ背面カメラを要求します。マイクは取得しません。
映像は端末内の画面に重ねるだけで、録画、写真保存、アップロードは実装していません。
停止、一覧に戻る、再開始、タブ非表示、ページ離脱でカメラを解放します。
許可拒否、カメラなし、非対応でもデモ背景で最後まで遊べます。
CSPで不要な通信・フォーム送信を制限し、外部リンクには参照元URLを送りません。
任意の参考資料リンクを押すとIPA/FTCのサイトに移動します。
公開HTML/ソースコードは誰でも閲覧できます。個人情報や秘密の鍵を追加しないでください。
GitHub Pages自体はセキュリティ目的のアクセスログ（IPアドレス等）を保持します。
これは体験が情報を収集する機能とは別で、ブラウザやOSまで含めた絶対的な安全保証ではありません。

当日までの実機確認
iPhone SafariとAndroid Chromeで、印刷したQR全6枚の読み取りと各体験の完走を確認してください。
背面カメラの許可・拒否・停止・タブ切替後の停止、会場の通信状況も確認してください。
物理端末の実カメラ、印刷紙、会場ネットワークの検証は制作環境では未確認です。
印刷はA4、100%（実際のサイズ）推奨。QR外周の白い余白を切り落とさないでください。

GitHub公式資料
無料公開・静的配信: https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
公開設定・更新: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
