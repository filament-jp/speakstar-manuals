# SpeakStar マニュアル（パブリックリポジトリ）

このリポジトリは、SpeakStarアプリケーションのマニュアルをエンドユーザーに公開するためのパブリックリポジトリです。

## リポジトリの目的

- エンドユーザー向けのマニュアル公開
- GitHub Pagesでの公開サイト運用

## 対象アプリケーション

- **SSManagerClient** - 管理者向けクライアントアプリケーション
- **SUAppClient** - 学生向けクライアントアプリケーション

## ディレクトリ構成

```
manual/
├── index.md                    # トップページ
├── _config.yml                 # Jekyll設定ファイル
├── ssmanager-client/           # SSManagerClientのマニュアル
│   └── (マニュアルファイル)
└── suapp-client/               # SUAppClientのマニュアル
    └── (マニュアルファイル)
```

## 運用フロー

1. プライベートリポジトリ（`filament-jp/speakstar-manuals-private`）でマニュアルを編集・レビュー
2. 完成したら、このリポジトリにコピー
3. このリポジトリにプッシュすると、自動的にGitHub Pagesに公開されます

## 公開URL

GitHub Pagesの設定後、以下のURLで公開されます：

```
https://filament-jp.github.io/speakstar-manuals/
```

## 注意事項

- **このリポジトリはパブリックです**
- エンドユーザーに公開される内容のみを含めてください
- 機密情報や個人情報を含む内容は記載しないでください
- 編集・レビューはプライベートリポジトリで行い、完成したものだけをここにコピーしてください

## GitHub Pagesの設定

1. Settings → Pages に移動
2. Source で「GitHub Actions」を選択
3. 設定を保存

## 関連リポジトリ

- プライベートリポジトリ: `filament-jp/speakstar-manuals-private`
- SSManagerClient: `filament-jp/SSManagerClient`
- SUAppClient: `filament-jp/SUApp_client`

