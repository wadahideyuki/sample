# カフェ こもれび（AI更新サンプルサイト）

AI（Claude Code）に話しかけるだけでホームページを更新し、GitHub Pages で公開するデモ用サンプルです。

## 更新の流れ

```
お客さん「お知らせに○○を追加して」
   ↓
AI が index.html を編集
   ↓
AI「この内容で公開してよろしいですか？」→ お客さん「OK」
   ↓
AI が git commit & git push
   ↓
GitHub Pages が自動で公開（1〜2分）
```

AI への指示ルールは [CLAUDE.md](CLAUDE.md) に書いてあります。

## 手元で確認する

```bash
python -m http.server 8000
```

ブラウザで http://localhost:8000 を開きます。
