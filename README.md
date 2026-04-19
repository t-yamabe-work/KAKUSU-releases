# KAKUSU-releases

このリポジトリは **KAKUSU アプリの配信専用**です。

- ソースコードは private リポジトリ [t-yamabe-work/KAKUSU](https://github.com/t-yamabe-work/KAKUSU) で管理しています
- 本 repo は **Sparkle 自動更新フィード（appcast.xml）と Release assets（.zip バイナリ）** のみを配置します

## Sparkle 自動更新フィード

アプリ内蔵の Sparkle Updater は以下の URL を参照します:

```
https://raw.githubusercontent.com/t-yamabe-work/KAKUSU-releases/main/appcast.xml
```

## 最新リリース

最新版は [Releases](https://github.com/t-yamabe-work/KAKUSU-releases/releases) から取得できます。

- `KAKUSU-x.y.z.zip` — メインアプリ（Sparkle 自動更新対象）
- `KAKUSURestore-x.y.z.zip` — 復元専用アプリ（スタンドアロン配布、Sparkle 非対象）

## ライセンス

本 repo のメタデータ（appcast.xml / README / LICENSE）は [MIT License](LICENSE) です。
配布バイナリ自体のライセンスは private リポジトリ側で規定します。
