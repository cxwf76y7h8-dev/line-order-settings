# LINE注文 接続設定

公式LINEから入力した注文をAIで仕分けし、Googleスプレッドシートへ転記するシステムのWindows配布版です。

[Windowsセットアップをダウンロード（EXE・約93MB）](https://github.com/cxwf76y7h8-dev/line-order-settings/releases/download/2026.10.08.8/line-order-settings-setup.exe)

[最新版の配布ページ](https://github.com/cxwf76y7h8-dev/line-order-settings/releases/latest)

## 導入方法

1. `line-order-settings-setup.exe` をダウンロードし、ダブルクリックします。
2. 自動で展開・インストールされ、デスクトップに「LINE注文 接続設定」アイコンが作成されます。インストール後は設定画面が開きます。
3. 次回からはデスクトップのアイコンをダブルクリックして開けます。
4. 初回は自分のCloudflareアカウントで導入し、LINE・OpenAI・Googleスプレッドシートの接続情報を設定します。

ZIPの手動展開やNode.jsの別途インストール、管理者権限は不要です。セットアップEXEは未署名です。

配布ファイルに個人のAPIキー、接続情報、注文データは含まれていません。接続先サービスは利用者自身のアカウントで設定します。

## 注文入力

- 同じメッセージに複数得意先・複数納品日の注文を入力できます。
- 得意先と納品日の組み合わせごとに分けて転記します。
- 一度に10注文、合計40品目まで対応します。
- 不足項目への追記、一括確定、途中保存からの再試行に対応しています。
- 音声入力はスマホで文字に変換して送信します。

GitHubへのログインなしでダウンロードできます。
