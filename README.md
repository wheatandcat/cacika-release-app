# cacika

<p align="center">
  <img src="https://www.cacika.net/images/logo.png" alt="cacika" width="96">
</p>

<p align="center">
  GitHub の PR とコミットの数を、とりあえず数える macOS アプリ
</p>

<p align="center">
  <a href="https://www.cacika.net">公式サイト</a> ・
  <a href="https://www.cacika.net/docs/">ドキュメント</a> ・
  <a href="https://github.com/wheatandcat/cacika-release-app/releases/latest">最新版をダウンロード</a>
</p>

---

> [!IMPORTANT]
> このリポジトリは **cacika の配布と、バグ報告・要望の受付窓口** です。
> アプリのソースコードは含まれていません。不具合の報告や機能の要望は [Issues](https://github.com/wheatandcat/cacika-release-app/issues) からお願いします。

## cacika について

cacika は macOS で動く GitHub の集計ツールです。指定したリポジトリの PR 数・コミット数・インシデント率を時系列で数え、そのまま配れるスタンドアローンの HTML レポートとして出力します。

データの取得も保存もレポート作成もアプリの中で完結します。収集したデータは Mac のローカル（SQLite）にのみ保存され、外部のサーバーには送信されません。

なお、ここで数えられるのはアウトプットの量だけで、その成果や生産性を測るものではありません。詳しくは公式サイトの [注意書き](https://www.cacika.net/#honesty) を読んでください。


## ダウンロード

[Releases](https://github.com/wheatandcat/cacika-release-app/releases/latest) から最新版の `cacika.zip` をダウンロードし、解凍した `cacika.app` を `アプリケーション` フォルダへ移動してください。

| | |
| --- | --- |
| 動作環境 | macOS 15.5 以降 |
| 必要なもの | GitHub の Personal Access Token、ライセンスキー |
| 自動更新 | アプリメニューの「アップデートを確認…」から確認できます |

セットアップ手順は [ドキュメント](https://www.cacika.net/docs/) にまとまっています。

## バグ報告・フィードバック

| 内容 | リンク |
| --- | --- |
| 不具合の報告 | [バグを報告する](https://github.com/wheatandcat/cacika-release-app/issues/new?template=bug_report.yml) |
| 機能の要望・感想 | [フィードバックを送る](https://github.com/wheatandcat/cacika-release-app/issues/new?template=feature_request.yml) |
| これまでの報告 | [Issues 一覧](https://github.com/wheatandcat/cacika-release-app/issues) |

報告の前に、次の 2 点を確認してもらえると助かります。

- 最新版で再現するか（古いバージョンでは修正済みの場合があります）
- 同じ内容の Issue がすでにないか（[検索](https://github.com/wheatandcat/cacika-release-app/issues?q=is%3Aissue)）

> [!WARNING]
> このリポジトリは公開されています。Issue には次の情報を **書かないでください**。
>
> - GitHub の Personal Access Token、ライセンスキーなどの秘密情報
> - 社外に出せないリポジトリ名・チーム名・メンバー名（`repo-a` `team-b` のように置き換えてください）
>
> 誤って投稿してしまった場合は、Issue を編集して削除したうえで、**そのトークンを GitHub 側で失効させてください**。

セキュリティ上の問題を見つけた場合は、公開の Issue ではなく [SECURITY.md](SECURITY.md) の手順で連絡してください。

## 購入・ライセンスについて

ライセンスの購入は [公式サイト](https://www.cacika.net) から行えます。

支払い内容の確認、領収書の発行、認証したデバイスの解除は [こちら](https://polar.sh/unicorn-llc/portal) から購入時のメールアドレスでログインして操作してください。これらは Issue では対応できません。

## サポートについて

- 個人で開発・運用しているため、返信までに数日いただくことがあります
- 修正の対象は原則として最新版のみです
- アプリのソースは非公開のため、Pull Request は受け付けていません
