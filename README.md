# klarstudio.dev

Klar Studio のサイト。Cloudflare Workers(静的アセット)で `https://klarstudio.dev` に公開する。

| URL | ファイル |
|---|---|
| `/` | `index.html` |
| `/civiclens/` (App Store のサポート URL) | `bureaucracy/index.html` |
| `/civiclens/privacy/` (App Store のプライバシーポリシー URL) | `bureaucracy/privacy/index.html` |

外部のフォントやスクリプトは読み込まない(第三者へのリクエストを発生させないため)。
