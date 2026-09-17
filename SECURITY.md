# セキュリティについて

## サポート対象のバージョン

修正の対象は原則として [最新版](https://github.com/wheatandcat/cacika-release-app/releases/latest) のみです。報告の前に最新版で再現するか確認してください。

## 脆弱性の報告

**公開の Issue には書かないでください。**

このリポジトリの [Security タブ](https://github.com/wheatandcat/cacika-release-app/security/advisories/new) から、非公開で報告できます（Report a vulnerability）。

報告には次の内容を含めてください。

- 影響の概要（何ができてしまうか）
- 再現手順
- cacika のバージョンと macOS のバージョン

個人で開発・運用しているため、一次返信までに数日いただくことがあります。内容を確認し、修正が必要な場合はリリースで対応したうえで報告者に連絡します。

## 報告に含めないでください

- GitHub の Personal Access Token、ライセンスキーなどの実際の秘密情報
- 業務上公開できないリポジトリ名・メンバー名

## cacika のデータの扱い

- 収集した PR・コミットのデータは Mac のローカル（SQLite）にのみ保存され、開発者を含む外部には送信されません
- GitHub の Personal Access Token は暗号化してローカルに保存されます
- アプリが外部と通信するのは、GitHub API・ライセンス認証（Polar.sh）・アップデート確認のときだけです
