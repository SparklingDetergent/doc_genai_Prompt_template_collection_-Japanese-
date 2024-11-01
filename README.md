# doc_genai_Prompt_template_collection_-Japanese-
プロンプトテンプレート集（日本語）

# プロンプトテンプレート集 - GitHubリファレンス用

こちらは、様々な目的に応じたプロンプトテンプレート集です。各プロンプトの見出しには、利用しやすさを3色で示し、「いまいち」「まあまあ」「つかえる」といった表現で評価しています。

---

## 🟥🔶🟩 ○○したい

### タグ
`#カテゴリ1` `#カテゴリ2` `#カテゴリ3`

### プロンプトテンプレート

```markdown
ここにプロンプト内容
```

<div style="text-align: right;">
<button onclick="copyToClipboard('ここにプロンプト内容')">📋 コピー</button>
</div>

<details>
  <summary>生成結果</summary>

```markdown
ここに生成された結果
```

<div style="text-align: right;">
<button onclick="copyToClipboard('ここに生成された結果')">📋 コピー</button>
</div>

</details>

<details>
  <summary>テンプレート説明</summary>
  このプロンプトは〇〇を目的としています。使用時の注意点や工夫すべきポイントなどを説明します。
</details>

---

## 🟥🔶🟩 △△を実行したい

### タグ
`#カテゴリA` `#カテゴリB` `#カテゴリC`

### プロンプトテンプレート

```markdown
ここに別のプロンプト内容
```

<div style="text-align: right;">
<button onclick="copyToClipboard('ここに別のプロンプト内容')">📋 コピー</button>
</div>

<details>
  <summary>生成結果</summary>

```markdown
ここに生成された別の結果
```

<div style="text-align: right;">
<button onclick="copyToClipboard('ここに生成された別の結果')">📋 コピー</button>
</div>

</details>

<details>
  <summary>テンプレート説明</summary>
  このプロンプトは△△を目的としています。使用するシーンや活用事例についても説明しています。
</details>

---

### コピー機能

コピー機能は以下のJavaScriptを活用します：

```html
<script>
function copyToClipboard(text) {
  navigator.clipboard.writeText(text).then(function() {
    alert('コピーしました: ' + text);
  }, function(err) {
    alert('コピーに失敗しました');
  });
}
</script>
```

---

## 注意事項
- 「いまいち」「まあまあ」「つかえる」の評価は目安として参考にしてください。
- プロンプトの内容は適宜修正・最適化してください。
