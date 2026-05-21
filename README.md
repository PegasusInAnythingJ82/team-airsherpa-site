# Team-AIRSherpa 公式ウェブページ — Netlify公開用パッケージ

## 内容
- `index.html` … 公式ウェブページ本体（モバイル最適化済）
- `netlify.toml` … セキュリティヘッダ・キャッシュ制御設定
- `_redirects` … URLルーティング
- `robots.txt` … 検索エンジン制御

## デプロイ手順（手動／最短経路）
1. https://app.netlify.com/ にログイン（GitHub/Googleアカウント等で無償登録）
2. 上部 [Sites] → [Add new site] → [Deploy manually]
3. このZIPを解凍したフォルダごとブラウザにドラッグ＆ドロップ
4. 数十秒で `https://<自動生成名>.netlify.app` のURLが発行されます
5. [Site configuration] → [Change site name] でサイト名を **team-airsherpa** に変更
6. 確定URL: `https://team-airsherpa.netlify.app`

## 独自ドメイン接続手順（取得後）
1. [Domain management] → [Add a domain]
2. 取得したドメイン（例: team-airsherpa.jp）を入力
3. Netlifyが指示するDNSレコードをドメインレジストラ側で設定
4. Let's Encrypt SSL証明書が自動発行（数分で完了）

## サポート
本パッケージは Team-AIRSherpa プロジェクト事務局向けの正式公開用ファイルです。


## 今回の確定設定
- Netlifyサイト名: `team-airsherpa`
- 公開URL: `https://team-airsherpa.netlify.app`
- 運用方針: 完全無料（Netlify無料プラン）
- QRコード: 正式URL確定後に新規発行
