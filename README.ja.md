# claude-code-hardening-cheatsheet

**[English version](README.md)**

[Claude Code](https://code.claude.com/) の `~/.claude/settings.json` に適用するセキュリティ強化チートシートです。

Claude Code はシェルコマンドの実行、ファイルの読み取り、外部サービスとの連携が可能です。これらの設定は、Claude Code に**やらせるべきでないこと**を明確に制限し、安心して**やらせたいこと**に集中できるようにします。

## チートシート

各ルールの詳しい解説はチートシート本体を参照：

- [Claude Code Hardening Cheatsheet (English)](Claude_Code_Hardening_Cheat_Sheet.md)
- [Claude Code Hardening Cheatsheet (日本語)](Claude_Code_Hardening_Cheat_Sheet.ja.md)

## ファイル構成

| ファイル | 説明 |
|---------|------|
| [`Claude_Code_Hardening_Cheat_Sheet.md`](Claude_Code_Hardening_Cheat_Sheet.md) | チートシート本体 — deny/allow/ask ルールの解説と根拠 |
| [`settings_example.jsonc`](settings_example.jsonc) | `settings.json` のサンプル — 全ルールと allow/ask の例をコメントアウトで収録 |

## 作者

Riotaro OKADA ([okdt](https://github.com/okdt))

## ライセンス

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ja) — 帰属表示をすれば、自由に利用・改変・再配布できます。改変物は同じライセンスで公開してください。
