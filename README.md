# doc_genai_Prompt_template_collection_-Japanese-
プロンプトテンプレート集（日本語）

# プロンプトテンプレート集

## 🟡 文章を要約したい

タグ: #要約 #テキスト処理 #効率化

### プロンプトテンプレート

```
以下の文章を3行で要約してください：

[ここに要約したい文章を入れる]
```

<details>
<summary>結果例（クリックで展開）</summary>

```
1. [要約の1行目]
2. [要約の2行目]
3. [要約の3行目]
```

</details>

<details>
<summary>説明（クリックで展開）</summary>

このプロンプトテンプレートは、長い文章を簡潔に要約するのに役立ちます。3行という制限を設けることで、AIに最も重要な情報を抽出させることができます。

</details>

## 🟢 アイデアを出したい

タグ: #ブレインストーミング #創造性 #アイデア生成

### プロンプトテンプレート

```
[トピック]に関する斬新なアイデアを5つ挙げてください。各アイデアには簡単な説明を付けてください。
```

<details>
<summary>結果例（クリックで展開）</summary>

```
1. [アイデア1]: [説明]
2. [アイデア2]: [説明]
3. [アイデア3]: [説明]
4. [アイデア4]: [説明]
5. [アイデア5]: [説明]
```

</details>

<details>
<summary>説明（クリックで展開）</summary>

このテンプレートは、特定のトピックに関する新しいアイデアを生成するのに適しています。AIに複数のアイデアと簡単な説明を求めることで、ブレインストーミングセッションの出発点として活用できます。

</details>

## 🔴 コードをデバッグしたい

タグ: #プログラミング #デバッグ #問題解決

### プロンプトテンプレート

```
以下のコードにエラーがあります。エラーの原因を特定し、修正案を提示してください：

[ここにエラーのあるコードを貼り付ける]
```

<details>
<summary>結果例（クリックで展開）</summary>

```
エラーの原因：
[エラーの説明]

修正案：
[修正されたコード]

説明：
[修正内容の詳細な説明]
```

</details>

<details>
<summary>説明（クリックで展開）</summary>

このプロンプトテンプレートは、プログラミングのデバッグ作業を支援します。AIにエラーの原因を特定させ、具体的な修正案を提示させることで、効率的にバグを修正できます。

</details>
```

この下書きでは、3つのプロンプトテンプレートを例として含めています。各セクションには、要求された要素（タグ、プロンプトテンプレート、結果例、説明）が含まれており、結果例と説明は折りたたみ表示になっています。

また、見出しの横に色付きの絵文字（🟡🟢🔴）を使用して、利用性の表示を行っています。

この基本的な構造をベースに、さらにテンプレートを追加したり、デザインを改善したりすることで、完成度を高めていくことができます。









# Felo





# Claude




# ChatGPT

Here's a draft layout for the README.md that aligns with your specifications:

```markdown
# プロンプトテンプレート集 - GitHubリファレンス用

こちらは、様々な目的に応じたプロンプトテンプレート集です。各プロンプトの見出しには、利用しやすさを3色で示し、「いまいち」「まあまあ」「つかえる」といった表現で評価しています。

---

## 🟥🔶🔵 ○○したい

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

## 🟥🔶🔵 △△を実行したい

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
