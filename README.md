# Memos をワンクリックでクラウドにデプロイ 🚀

**自分だけのメモ帳を、たった1クリックでクラウドに。**

[![Deploy on Railway](https://railway.com/button.svg)](https://railway.com/template/{{TEMPLATE_ID}}?referralCode={{REFERRAL_CODE}})

> Railway アカウントだけで OK。フリートライアルですぐ試せます。

---

[Memos](https://github.com/usememos/memos) は、58,000+ ⭐ のオープンソース・セルフホスト型メモツールです。Markdown 対応、軽量、データは完全に自分のもの。

![Memos デモ画面](https://raw.githubusercontent.com/usememos/.github/refs/heads/main/assets/demo.png)

## ✅ こんな人におすすめ

- Notion / Google Keep の代わりに、**自分でデータを管理したい**
- ふと思いついたことを **すぐメモして、あとから検索したい**
- サーバー管理は面倒だけど、**セルフホストの安心感がほしい**

### デプロイ手順

1. 上の **「Deploy on Railway」** ボタンをクリック
2. GitHub アカウントで Railway にログイン
3. **「Deploy」** を押す — 約 2 分で完了 🎉
4. 表示された URL にアクセスし、管理者アカウントを作成

以上。これだけです。

## 💡 Memos の主な特徴

| 特徴 | 説明 |
|------|------|
| ⚡ 即メモ | 開いて、書いて、終わり。フォルダ整理は不要 |
| 🔒 完全なデータ所有権 | データは自分のインフラに。テレメトリなし |
| 🪶 超軽量 | Go 製シングルバイナリ、Docker イメージ約 20MB |
| 🔓 オープンソース | MIT ライセンス、REST / gRPC API 完備 |

## ❓ よくある質問

<details>
<summary>料金はどのくらいかかりますか？</summary>

Memos は Go 製で非常に軽量なため、月の利用料は $1 以下に収まります。Railway は従量課金制で、使った分だけ請求されます。
</details>

<details>
<summary>データはどこに保存されますか？</summary>

Railway 上のあなた専用のコンテナ内に SQLite で保存されます。Railway の Volume バックアップ機能でデータを保護でき、CLI 経由でエクスポートも可能です。
</details>

<details>
<summary>Docker で自分のサーバーにデプロイしたい場合は？</summary>

[Memos 公式デプロイガイド](https://usememos.com/docs/deploy) をご覧ください。
</details>

## 📎 関連リンク

- [Memos 公式サイト](https://usememos.com)
- [Memos GitHub リポジトリ](https://github.com/usememos/memos)
- [ライブデモ](https://demo.usememos.com/)
- [Memos を Railway にデプロイする手順（詳細記事）]({{ZENN_OR_QIITA_ARTICLE_URL}})

---

<p align="center">
  <a href="https://railway.com/template/{{TEMPLATE_ID}}?referralCode={{REFERRAL_CODE}}">
    <img src="https://railway.com/button.svg" alt="Deploy on Railway" />
  </a>
  <br/>
  <sub>👆 迷ったら、まずデプロイしてみてください。2 分で終わります。</sub>
</p>
