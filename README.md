# Rukio LAN Messenger

Rukio LAN Messengerのバイナリ配布用リポジトリです。

[最新版をダウンロード](https://github.com/kidatti/RukioLANMessanger/releases/latest)

v1.4.0からアプリ内で更新確認・ダウンロード・更新して再起動を行えます。既存版からは、更新機能を搭載した版を一度手動で導入してください。

- macOS: `macos-app.zip` を展開し、`.app` を書き込み可能なフォルダに配置します。
- Windows: アプリ内更新にはNSISセットアップEXE版を使用します。単体EXE版は手動更新です。従来のMSI版からは一度アンインストールしてNSIS版を導入してください。
- Linux: AppImage版がアプリ内更新に対応します。deb/rpm版はパッケージ管理で更新します。

アプリ内更新では `latest.json` と署名付き更新ファイルを使用します。ダウンロードした更新の署名を検証し、利用者の確認後に適用します。転送・送信・速度測定中は適用できません。
