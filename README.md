# doc_genai_Prompt_template_collection_-Japanese-
プロンプトテンプレート集（日本語）
以下のように清書し、読みやすく整理しました：

# プロンプトテンプレート集 - GitHubリファレンス用

こちらは、作成者が実際に比較検証した、様々な目的に応じたプロンプトテンプレート集です。作成者の用途に応じて修正・最適化されているため、参考にお願いします。

## 利用度の表示について

各プロンプトの見出しには、利用しやすさを3色で示しています。

- 🔴 いまいち：基本的な結果は得られますが、改善の余地があります
- 🟡 まあまあ：概ね期待通りの結果が得られます
- 🟢 つかえる：高い確率で期待通りの結果が得られます

## プロンプトテンプレートの使い方について
 * 以下のプロンプトの例では「`」で囲った部分が個別の要件に合わせて修正する部分です。
   * 「`」で囲った部分以外の部分についても、「テンプレート説明」を基にユーザの用途に応じて修正・最適化してください。
 * なお、「`」自体はマークダウン形式の表現で目立つように表示しているだけです。
   * 生成AIの回答に影響が出ないと考えていますが、気になる場合は削除してご利用ください。

```markdown
`str = str & " , c02 "`

この `VBA` の続きを `c03` から `c10` まで真似して書いてください。
繰り返し構文を用いず 真似するだけでいいです。
```

## 注意事項

- 「いまいち」「まあまあ」「つかえる」の評価は目安として参考にしてください。
- プロンプトの内容は適宜修正・最適化してください。
  - プロンプトテンプレートの中でも、キーワードを説明しています。このキーワードを複数組み合わせて利用するのが実際の使い方となります。
  - このプロンプトテンプレート集では、そのキーワードをある程度まとめて１つのプロンプトテンプレートとして紹介しています。
- 生成AIに入力するプロンプトの種類は大きく分けて３つ存在します。
  - 当資料では一般的な生成AIチャットで汎用的に利用できるよう、「**ユーザプロンプト**」に焦点をあてています。
- 「生成結果」は実際に各種生成AIを用いて生成した結果を紹介している参考であり、「生成結果」自体を利用されることを想定していません。

## プロンプトの種類について（参考）

<details>
  <summary>システムプロンプト . . . 会話セッションの最初に指定します。</summary>

- 「You are helpful assistant.」「あなたは親切なアシスタントです。」などの役割が設定されます。
- 生成AIチャットによってはより具体的な役割を指示するような設定がされています。
- 生成AIチャットによっては、設定によりカスタマイズ可能となっています。

</details>

<details>
  <summary>ユーザプロンプト . . . ユーザが要求する内容を入力します。</summary>

- 当資料において、プロンプトテンプレートとして紹介しています。

</details>

<details>
  <summary>アシスタントプロンプト . . . ユーザの要求に対する生成AIチャットの回答の冒頭部分を強制します。</summary>

- 例として、「```javascript」のように回答する言語を指定することができます。
- 例として、「```json\n{"answer":"」のようにjson形式で指定し回答させることで、その回答を別のプログラムより参照することができます。
- 生成AIチャットによっては、設定によりカスタマイズ可能となっています。

</details>

---
<br/><br/> <br/><br/>



# カテゴリ

- [一般](#一般)
  - [タグ1](#タグ1)
  - [タグ2](#タグ2)
- [技術](#技術)
  - [プログラミング](#プログラミング)
  - [データサイエンス](#データサイエンス)
  - [ウェブ開発](#ウェブ開発)
- [創造的](#創造的)
  - [アート](#アート)
  - [ライティング](#ライティング)
  - [音楽](#音楽)
- [学術](#学術)
  - [研究](#研究)
  - [教育](#教育)
  - [統計](#統計)
- [その他](#その他)
  - [ビジネス](#ビジネス)
  - [マーケティング](#マーケティング)
  - [健康](#健康)

---
<br/><br/> <br/><br/>


# 一般
## タグ1



### 🟡 はじめに
#### プロンプトテンプレート
````markdown
あなたは何ができますか。１０個ほど答えてください。
````
````markdown
実際にそれぞれ具体的に例を考えてやってみてください。
````
<details>
  <summary>生成結果</summary>

````markdown


🌸😊You:
あなたは何ができますか。１０個ほど答えてください。



🚀🤖Copilot:
1. 情報検索: ユーザーが質問や情報を探しているときに、インターネットやデータベースから情報を提供します。
2. レコメンデーション: ミュージック、映画、本、レストランなど、ユーザーが楽しむためのリソースを提案します。
3. 翻訳: 多くの言語間での翻訳が可能です。
4. 天気予報: 現在の天気や、指定した場所の未来の天気情報を提供します。
5. カレンダー管理: イベントの追加、削除、変更、リマインダーを管理します。
6. 予算管理: 費用の追跡、予算の設定、節約のためのアドバイスを提供します。
7. ニュース更新: ニュース記事や最新のニュース情報を提供します。
8. 健康情報: 健康的なライフスタイルに関するアドバイスや、一般的な健康問題についての情報提供します。
9. エクササイズプラン: ヨガ、ウォーキング、プールジムなどのエクササイズのためのプランを提供します。
10. リラクゼーション: ストレスの軽減、リラクゼーションのためのアドバイスや、瞑想のためのガイドを提供します。



🌸😊You:
実際にそれぞれ具体的に例を考えてやってみてください。



🚀🤖Copilot:
1. 情報検索: ユーザーが「現在の天気」を尋ねると、現在の天気と、それに対する適切なアドバイス（例：傘を忘れずに带い、雨衣を準備）を提供します。
2. レコメンデーション: ユーザーが「新しい映画を観たい」を尋ねると、最近公開された人気映画や、新しい作品を提案します。
3. 翻訳: ユーザーが「こんにちは」を英語で翻訳すると、「hello」が返されます。
4. 天気予報: ユーザーが「東京の天気」を尋ねると、東京の現在の天気と、未来の天気予報を提供します。
5. カレンダー管理: ユーザーが「明日の会議を追加」と尋ねると、カレンダーに会議を追加し、確認メールを送ります。
6. 予算管理: ユーザーが「この月の予算は？」と尋ねると、その月の予算と、それに基づいての支出を追跡し、分析します。
7. ニュース更新: ユーザーが「最新のニュース」を尋ねると、最近のニュース記事や、最新のニュース情報を提供します。
8. 健康情報: ユーザーが「ストレス解消法」を尋ねると、ストレス解消のためのアドバイスや、瞑想やヨガなどの方法を提供します。
9. エクササイズプラン: ユーザーが「新しいヨガコース」を尋ねると、新しいヨガコースの詳細や、そのコースでのエクササイズの例を提供します。
10. リラクゼーション: ユーザーが「瞑想のためのガイド」を尋ねると、瞑想のためのガイドや、瞑想のためのリラクゼーションテクニックを提供します。



````
</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
--------------------------------------------------------------------------------------------------------------------
# 目的
  - このプロンプトテンプレート自体には、特に目的はありませんが、生成AIの可能性を感じるためのきっかけとして説明します。
    お読みいただけますと幸いです。
# 使用シーン
  - 初めてその生成AIを利用する際に、試してみるのも良いと思います。
# 期待される効果
  - その生成AIにどのような傾向があるか、把握できるかもしれません。
# キーワード
  - **１０個ほど** . . . 数を示すことで指定した回答数を期待。
  - **ください。** . . . 丁寧語を利用することで精度が上がるという研究あり。
  - **具体的に例を** . . . 具体的に例を示すことを要求。
# 詳細な説明
  - はじめに、生成AIにはできることとできないことが存在し、ユーザはそれを見極めるために色々と試す必要があります。
  - まずはこのプロンプトの様に、とにかく何でもよいから入力してみる、ということが大事と考えます。
# カスタマイズのポイント
  - 何でも入力してみてください。はじめは色々と入力してみて、どのような回答をするか試してみる良いです。
  - 色々と試していく中で、ユーザにとって意味のある使い方を見出すことができるかもしれません。
  - もし生成AIの可能性を感じたのであれば、次に行うこととして、様々なプロンプトを修正・最適化し、
    自分専用のプロンプトテンプレート集を作ってみるのが良い、と考えます。
# 注意事項
  - 生成AIによっては（特にクラウド型は）情報漏洩のリスクがありますので、適切に利用することが重要です。
  - 生成AIの回答によっては、実際にはできなくても「できる」かのように回答したり、正しくない情報をさも正しいかのように回答したりします。
  - 生成AIは、基本的にはAIチャット機能であり、その生成AIが学習した範囲でしか回答しません。
    - 中には実際に、現在の天気や時刻やニュースを調べる機能を有しているものもありますが、この資料の対象ではありません。
    - 中には実際に、アラームの設定やスケジュールの登録など、具体的なタスクを実行できるものもありますが、この資料の対象ではありません。
--------------------------------------------------------------------------------------------------------------------
````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>




### 🟡 生成AIの回答の精度やボリュームを高めたい
#### プロンプトテンプレート
````markdown
`powershell で fizzbuzz。`

フェーズ1から段階的に完成度を高めるものとします。
````
````markdown
続けてください。
````
<details>
  <summary>生成結果</summary>

````markdown


🌸😊You: 
`powershell で fizzbuzz。`

フェーズ1から段階的に完成度を高めるものとします。



🚀🤖Copilot: 
もちろんです！フェーズ1のFizzBuzzをPowerShellで作成します。

```powershell
for ($i = 1; $i -le 100; $i++) {
    if ($i % 3 -eq 0 -and $i % 5 -eq 0) {
        Write-Output "FizzBuzz"
    } elseif ($i % 3 -eq 0) {
        Write-Output "Fizz"
    } elseif ($i % 5 -eq 0) {
        Write-Output "Buzz"
    } else {
        Write-Output $i
    }
}
```

このスクリプトは1から100までの数を表示し、その数が3で割り切れる場合は "Fizz"、5で割り切れる場合は "Buzz"、両方で割り切れる場合は "FizzBuzz" を出力します。



🌸😊You: 
続けてください。



🚀🤖Copilot: 
フェーズ2では、FizzBuzzをユーザーが指定した範囲内に制限するようにしましょう。ユーザーからの入力を取得し、その範囲内でFizzBuzzを実行します。

```powershell
$from = Read-Host "開始番号を入力"
$to = Read-Host "終了番号を入力"

for ($i = $from; $i -le $to; $i++) {
    if ($i % 3 -eq 0 -and $i % 5 -eq 0) {
        Write-Output "FizzBuzz"
    } elseif ($i % 3 -eq 0) {
        Write-Output "Fizz"
    } elseif ($i % 5 -eq 0) {
        Write-Output "Buzz"
    } else {
        Write-Output $i
    }
}
```

このスクリプトでは、`Read-Host` コマンドを使用してユーザーからの入力を取得します。ユーザーが指定した範囲内でFizzBuzzを実行します。

注意：PowerShellは整数型に変換できない場合、エラーが発生しますので、整数型に変換できるようになっています。


````
</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
--------------------------------------------------------------------------------------------------------------------
# 目的
  - タイトルの通り
# 使用シーン
  - とりあえず生成AIで基本的なことから順に何かを出力したい、という時
  - この例では、コーディングタスクだが、ドキュメント生成タスクや、レビュー・分析タスクでも利用できる。
# 期待される効果
  - 基本的なことから順に内容を理解しやすい回答
# キーワード
  - **フェーズ1から段階的に完成度を高める** . . . １から順にどのように回答してほしいか要求。以下のような様々な言い回しが考えられる。
    - レベル１から累積的に内容を深く掘り下げる
    - ステップ１からステップアップするように初心者から上級者へ向けた内容とする
    - ナンバー１から様々なパターンで網羅性を重視する
 - **続けてください。** . . . 生成AIからの回答が途切れたら、これさえ入力すれば更に回答を要求することができる。
# 詳細な説明
  - ２つめの「続けて」を繰り返すことで、その生成AIのパフォーマンスを引き出せるかもしれない。
# カスタマイズのポイント
  - 「レベル１から順に詳細にしてください。」「ステップ１からステップバイステップで積み重ねてください。」など、言い回しを変えてみる。
# 注意事項
  - あえて方向性を示していないことで、多様な回答が得られるようになっている反面、期待した回答が得られにくいかもしれない。
--------------------------------------------------------------------------------------------------------------------
````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>






### 🟢 生成AIの回答の精度やボリュームを高めたい（詳細に指示、方向性を示す）
#### プロンプトテンプレート
````markdown
`powershellでfizzbuzz。`

レベル１を最低限要求を満たす内容とし、レベル８を、不特定多数の人間が利用しても問題が無く、
読みやすい、説明しやすい、汎用性の高い内容とします。

初めに、各レベル（レベル１、レベル２，レベル３，レベル４、レベル５、レベル６，レベル７，レベル８）
で目指す完成度の目標を日本語で説明してください。

その後、まずはレベル１の内容だけを示してください。
````
````markdown
レベル２
````
````markdown
レベル４，レベル５，レベル６，レベル７を統合
````
<details>
  <summary>生成結果</summary>

````markdown


🌸😊You: 
`powershellでfizzbuzz。`

レベル１を最低限要求を満たす内容とし、レベル８を、不特定多数の人間が利用しても問題が無く、
読みやすい、説明しやすい、汎用性の高い内容とします。

初めに、各レベル（レベル１、レベル２，レベル３，レベル４、レベル５、レベル６，レベル７，レベル８）
で目指す完成度の目標を日本語で説明してください。

その後、まずはレベル１の内容だけを示してください。



🚀🤖Copilot: 
### 各レベルの目標

1. **レベル1**: 基本的なFizzBuzzの機能を実装する。コードが動作し、正しく出力されるようにする。
2. **レベル2**: 基本的なFizzBuzzの機能を実装する。コードが動作し、正しく出力されるようにする。また、コードの可読性を高める。
3. **レベル3**: 基本的なFizzBuzzの機能を実装する。コードが動作し、正しく出力されるようにする。また、コードの可読性を高める。コードの効率性を追求。
4. **レベル4**: 基本的なFizzBuzzの機能を実装する。コードが動作し、正しく出力されるようにする。また、コードの可読性を高める。コードの効率性を追求。エラーハンドリングを実装。
5. **レベル5**: 基本的なFizzBuzzの機能を実装する。コードが動作し、正しく出力されるようにする。また、コードの可読性を高める。コードの効率性を追求。エラーハンドリングを実装。コードの拡張性を追求。
6. **レベル6**: 基本的なFizzBuzzの機能を実装する。コードが動作し、正しく出力されるようにする。また、コードの可読性を高める。コードの効率性を追求。エラーハンドリングを実装。コードの拡張性を追求。コードのテストを実装。
7. **レベル7**: 基本的なFizzBuzzの機能を実装する。コードが動作し、正しく出力されるようにする。また、コードの可読性を高める。コードの効率性を追求。エラーハンドリングを実装。コードの拡張性を追求。コードのテストを実装。コードのドキュメンテーションを追加。
8. **レベル8**: 基本的なFizzBuzzの機能を実装する。コードが動作し、正しく出力されるようにする。また、コードの可読性を高める。コードの効率性を追求。エラーハンドリングを実装。コードの拡張性を追求。コードのテストを実装。コードのドキュメンテーションを追加。コードが不特定多数の人間が利用しても問題が無く、読みやすい、説明しやすい、汎用性の高い。

### レベル1のFizzBuzz

```powershell
for ($i = 1; $i -le 100; $i++) {
    if ($i % 3 -eq 0 -and $i % 5 -eq 0) {
        Write-Output "FizzBuzz"
    } elseif ($i % 3 -eq 0) {
        Write-Output "Fizz"
    } elseif ($i % 5 -eq 0) {
        Write-Output "Buzz"
    } else {
        Write-Output $i
    }
}
```

このコードは基本的なFizzBuzzの機能を実装しています。1から100までの数を順番に出力し、3の倍数の場合は"Fizz"、5の倍数の場合は"Buzz"、両方の倍数の場合は"FizzBuzz"と出力します。



🌸😊You: 
レベル２



🚀🤖Copilot: 
### レベル2のFizzBuzz

```powershell
function Get-FizzBuzz([int]$start = 1, [int]$end = 100) {
    for ($i = $start; $i -le $end; $i++) {
        if ($i % 3 -eq 0 -and $i % 5 -eq 0) {
            Write-Output "FizzBuzz"
        } elseif ($i % 3 -eq 0) {
            Write-Output "Fizz"
        } elseif ($i % 5 -eq 0) {
            Write-Output "Buzz"
        } else {
            Write-Output $i
        }
    }
}

Get-FizzBuzz
```

このコードは、FizzBuzzの機能を関数として実装しています。`Get-FizzBuzz`関数は、2つの引数（開始数と終了数）を受け取り、その範囲内の数をFizzBuzzのルールに従って出力します。また、関数の呼び出しは省略できるよう、デフォルト値を設定しています。



🌸😊You: 
レベル４，レベル５，レベル６，レベル７を統合



🚀🤖Copilot: 
### レベル4, レベル5, レベル6, レベル7のFizzBuzz

```powershell
function Get-FizzBuzz([int]$start = 1, [int]$end = 100) {
    for ($i = $start; $i -le $end; $i++) {
        if ($i % 3 -eq 0 -and $i % 5 -eq 0) {
            Write-Output "FizzBuzz"
        } elseif ($i % 3 -eq 0) {
            Write-Output "Fizz"
        } elseif ($i % 5 -eq 0) {
            Write-Output "Buzz"
        } else {
            Write-Output $i
        }
    }
}

try {
    Get-FizzBuzz
} catch {
    Write-Error "Error: $_"
}

Get-FizzBuzz -start 101 -end 200
```

このコードは、FizzBuzzの機能を関数として実装しています。`Get-FizzBuzz`関数は、2つの引数（開始数と終了数）を受け取り、その範囲内の数をFizzBuzzのルールに従って出力します。また、関数の呼び出しは省略できるよう、デフォルト値を設定しています。
また、エラーハンドリングも実装しています。`try`ブロック内で`Get-FizzBuzz`関数を呼び出し、`catch`ブロック内でエラーが発生した場合にエラーメッセージを出力します。
さらに、関数の拡張性も追求しています。新しい範囲の数をFizzBuzzのルールに従って出力したい場合は、`-start`と`-end`パラメータを指定して関数を再度呼び出すことができます。

````

</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
--------------------------------------------------------------------------------------------------------------------
# 目的
  - タイトルの通り
# 使用シーン
  - とりあえず生成AIで基本的なことから順に何かを出力したいし、ある程度完成形の方向性を示したい、という時
  - この例では、コーディングタスクだが、ドキュメント生成タスクや、レビュー・分析タスクでも利用できる。
# 期待される効果
  - 基本的なことから順に内容を理解しやすい回答であり、方向性がある状態
# キーワード
  - **初めに**  **その後** . . . 回答内容の順序性について指示。
  -  **まずは**  **だけを**  . . . 回答内容を限定する指示。
    - このキーワードがない場合は、このプロンプトテンプレートの場合では大量の回答が回答されてしまう。
    - そのことにより、回答に時間がかかったり精度が低下したりする。
# 詳細な説明
  - 最初の文章で、何を要求しているのか生成AIへ伝えています。次の文章では、具体的にどのようにしてほしいかを伝えています。
  - 最初のレベルと最後のレベルの目標を示すだけで、その中間のレベルの目標は生成AIが調整する流れを期待している。
  - 「各レベル（レベル１、レベル２，」としているのは、こうしないと勝手に途中のレベルを省略されてしまうことがあるから明確にしている。
  - はじめに各レベルの目的を示すようにし、まずはレベル１の内容を示すようにすることで、どういった方向性の回答か先にチェックできる。
  - 後続のプロンプトの「レベル２」や、「○○を統合」により、各レベルの目標に該当する内容を取り出すイメージ。
# カスタマイズのポイント
  - 最初のレベルと最後のレベルだけではなく、全てのレベルの目標を明確に示してみるとか。
  - レベル４まで、などと短くしたり、逆にレベル１６まで、と長くしたりする。（長くしすぎると内容が薄くなる可能性もある）
  - 「レベル」を「フェーズ」「ステップ」など、言い回しを変えてみる。
# 注意事項
  - 方向性を示すことで期待した回答が得られやすい反面、かえって回答のバリエーションが減ってしまう可能性もある。
--------------------------------------------------------------------------------------------------------------------
````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>




### 🔴 ソースコード１行を真似してインクリメントして作りたい
#### プロンプトテンプレート
````markdown
`str = str & " , c02 "`

この `VBA` の続きを `c03` から `c10` まで真似して書いてください。
繰り返し構文を用いず 真似するだけでいいです。
````
<details>
  <summary>生成結果</summary>

````markdown

🌸😊You: 
`str = str & " , c02 "`

この `VBA` の続きを `c03` から `c10` まで真似して書いてください。
繰り返し構文を用いず 真似するだけでいいです。



🚀🤖Copilot: 
申し訳ありませんが、そのような繰り返し構文を使用せずに `c03` から `c10` まで `str` 変数に追加する方法は、直接書く必要があります。以下はその例です：

```vba
str = str & " , c03 "
str = str & " , c04 "
str = str & " , c05 "
str = str & " , c06 "
str = str & " , c07 "
str = str & " , c08 "
str = str & " , c09 "
str = str & " , c10 "
```

この方法は、各 `c` 値を一つずつ追加しています。ただし、大量の追加操作を行う場合は、性能に問題が生じる可能性があります。この場合、ループを使用した方が更に効率的になるかもしれません。

````
</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
--------------------------------------------------------------------------------------------------------------------
# 目的
  - タイトルの通り
# 使用シーン
  - コーディングしていて似たような行を複数行つくる必要があるとき
# 期待される効果
  - 表計算で関数で作成してもいいけどその関数を記述するよりも早いかもしれない
# キーワード
  - **から**  **まで** . . . 明確に言語、開始終了を示す。これがないと、本当に１行真似する回答だったりする。
  - **繰り返し構文を用いず** . . . 勝手に最適化しないようにしている。これがないと、For文で記述したりしようとする。
  - **真似するだけでいいです** . . . 例で示した文章を真似するように要求。念押しとして。
# 詳細な説明
  - 言語や開始終了を指定することで、明確な指示としている。
# カスタマイズのポイント
  - 言語や開始終了の部分
# 注意事項
  - 表計算で管理するほうが後々便利かもしれない。。。
--------------------------------------------------------------------------------------------------------------------
````
</details>

#### タグ
`#コーディング` `#ローカル` `#`

---
<br/><br/> <br/><br/>


---
<br/><br/> <br/><br/>





### 🟡 初心者でも理解できるよう、専門家として100倍詳しく、資料を作成してほしい
#### プロンプトテンプレート
````markdown
`sqlite_webのソースをgithubからzipでダウンロードし、Windowsのローカルへ解凍し、利用したいです。`
初心者でも理解できるよう、専門家として100倍詳しく、`資料を作成`していただくことは可能でしょうか？
````
<details>
  <summary>生成結果</summary>

````markdown
# SQLite_webのWindowsセットアップガイド

## 目次
1. 準備するもの
2. Pythonのインストール
3. SQLite_webのダウンロード
4. セットアップ手順
5. 動作確認
6. トラブルシューティング

## 1. 準備するもの
以下のものを準備します：
- インターネット接続
- Windowsパソコン（Windows 10/11推奨）
- 管理者権限を持つアカウント

## 2. Pythonのインストール
SQLite_webを使用するには、まずPythonをインストールする必要があります。

### 2.1 Pythonダウンロード
1. [Python公式サイト](https://www.python.org/downloads/)にアクセス
2. "Download Python 3.x.x"ボタンをクリック（最新版を選択）
3. ダウンロードしたインストーラーを実行

### 2.2 Pythonインストール手順
1. インストーラーを起動
2. 以下の2つのチェックボックスを必ず有効にする：
   - ☑ Add Python to PATH
   - ☑ Install launcher for all users
3. "Install Now"をクリック
4. インストール完了まで待機

### 2.3 インストール確認
1. Windowsキー + Rを押して「ファイル名を指定して実行」を開く
2. `cmd`と入力してEnterキーを押す
3. コマンドプロンプトで以下のコマンドを実行：
```
python --version
```
バージョン番号が表示されればインストール成功です。

## 3. SQLite_webのダウンロード

### 3.1 GitHubからダウンロード
1. [sqlite-web GitHub](https://github.com/coleifer/sqlite-web)にアクセス
2. 緑色の「Code」ボタンをクリック
3. 「Download ZIP」を選択
4. ダウンロードしたZIPファイルを任意の場所に保存

### 3.2 解凍手順
1. ダウンロードしたZIPファイルを右クリック
2. 「すべて展開」を選択
3. 展開先のフォルダを選択（例：`C:\sqlite-web`）
4. 「展開」ボタンをクリック

## 4. セットアップ手順

### 4.1 必要なパッケージのインストール
1. コマンドプロンプトを管理者権限で開く
2. 解凍したフォルダに移動：
```
cd C:\sqlite-web
```
3. 必要なパッケージをインストール：
```
pip install -r requirements.txt
pip install sqlite-web
```

## 5. 動作確認

### 5.1 サンプルデータベースの作成
1. コマンドプロンプトで以下を実行：
```
sqlite3 test.db
```
2. 以下のSQLコマンドを実行：
```sql
CREATE TABLE users (id INTEGER PRIMARY KEY, name TEXT, email TEXT);
INSERT INTO users (name, email) VALUES ('test user', 'test@example.com');
.quit
```

### 5.2 SQLite_webの起動
1. 以下のコマンドを実行：
```
sqlite_web test.db
```
2. ブラウザで `http://localhost:8080` にアクセス

## 6. トラブルシューティング

### 6.1 よくある問題と解決方法

#### Python PATHの問題
症状：'python'は内部コマンドまたは外部コマンドとして認識されていません
解決：
1. システム環境変数の編集を開く
2. PATHにPythonのインストールパスを追加

#### pip コマンドの問題
症状：'pip'は内部コマンドまたは外部コマンドとして認識されていません
解決：
```
python -m ensurepip --default-pip
```

#### ポート競合の問題
症状：アドレスが既に使用されています
解決：
```
sqlite_web test.db -p 8081
```
別のポート番号（8081など）を指定して起動

### 6.2 サポートリソース
- [SQLite_web GitHub Issues](https://github.com/coleifer/sqlite-web/issues)
- [Python公式ドキュメント](https://docs.python.org/ja/3/)
- [SQLite公式ドキュメント](https://www.sqlite.org/docs.html)

## 補足情報
- データベースのバックアップは定期的に行うことをお勧めします
- 本番環境での使用時はセキュリティ設定を必ず確認してください
- 大規模なデータベースを扱う場合は、パフォーマンスに注意してください
````
</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
--------------------------------------------------------------------------------------------------------------------
# 目的
  - タイトルの通り
# 使用シーン
  - 今から知りたい事があったとして、全体像を把握したいときなど。
# 期待される効果
  - 全体像を把握できる資料を作成することができる。
# キーワード
  - **初心者でも理解できるよう** . . . 分かりやすさを要求。どのようなユーザに対する回答を求めるか明確化。
  - **専門家として100倍詳しく** . . . より詳しく示すよう要求。生成AIに役割を持たせることで、生成AIの持つ情報を引き出すことを期待。
  - **していただくことは可能でしょうか？** . . . 丁寧語を利用することで精度が上がるという研究あり。
# 詳細な説明
  - 生成AIはプロンプトの内容により回答が変わる性質を持っていることから、プロンプトによって
# カスタマイズのポイント
  - 「フェーズ１から段階的に」等のキーワードと組み合わせることでより見やすい資料の生成が期待できます。
# 注意事項
  - 資料を作成するタスクの場合、インターネット検索が可能な生成AIチャットや、RAGを用いた生成AIチャットを用いることで精度が向上します。
--------------------------------------------------------------------------------------------------------------------
````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>












### 🟡 資料を簡単に把握する
#### プロンプトテンプレート
````markdown
簡潔に要約してください。
````
````markdown
もっと簡潔にお願いします。
````
````markdown
もう少し詳しくお願いします。
````
````markdown
他と比べてこの資料にはどのような特徴があるでしょうか。
````
<details>
  <summary>生成結果</summary>

````markdown


🌸😊You: 
簡潔に要約してください。

（`sqlite-web`のREADME）

🚀🤖Copilot: 
`sqlite-web`はPythonで書かれたSQLiteデータベースブラウザのWebアプリケーションです。主な特徴として、既存のSQLiteデータベースを操作でき、テーブル、列、インデックスの追加や削除、データのエクスポートとインポートなどがサポートされています。また、SQLクエリの実行も可能で、結果はJSONやCSV形式で取得できます。コマンドラインオプションでポート番号、ホストアドレス、デバッグモードなどを指定できます。Dockerを使用して簡単に実行することもできます。



🌸😊You: 
もっと簡潔にお願いします。



🚀🤖Copilot: 
`sqlite-web`はPythonで書かれたSQLiteデータベースブラウザのWebアプリです。主要な機能にはテーブルや列の管理、データのエクスポート・インポート、SQLクエリの実行などがあります。コマンドラインオプションで設定を変更でき、Dockerでも簡単に実行できます。



🌸😊You: 
もう少し詳しくお願いします。



🚀🤖Copilot: 
`sqlite-web`はPythonで作られたSQLiteデータベースブラウザのWebアプリケーションです。主な特徴として、SQLiteデータベースの管理が簡単にでき、テーブル、列、インデックスの追加や削除、データのエクスポートとインポートなどがサポートされています。また、SQLクエリの実行も可能で、結果はJSONやCSV形式で取得できます。コマンドラインオプションでポート番号、ホストアドレス、デバッグモードなどを指定できます。Dockerを使用して簡単に実行することもできます。



🌸😊You: 
他と比べてこの資料にはどのような特徴があるでしょうか。



🚀🤖Copilot: 
すみません、私はAIアシスタントなので、特定の資料と比較する能力はありません。しかし、一般的にSQLiteデータベースブラウザのWebアプリケーションは、SQLiteデータベースの管理、テーブルや列の追加・削除、データのエクスポート・インポート、SQLクエリの実行などがサポートされています。`sqlite-web`はPythonで書かれているため、その機能はPythonのライブラリを使用しています。また、Dockerを使用して簡単に実行できることも利点の一つです。



🌸😊You: 
簡潔に要約してください。

（`sqlite-web`のREADME）



🚀🤖Copilot: 
`sqlite-web`はPythonで書かれたSQLiteデータベースブラウザのWebアプリケーションです。主な特徴として、既存のSQLiteデータベースの管理、テーブルや列の追加・削除、データのエクスポート・インポート、SQLクエリの実行などがサポートされています。また、コマンドラインオプションで設定を変更でき、Dockerでも簡単に実行できます。



🌸😊You: 
もっと簡潔にお願いします。



🚀🤖Copilot: 
`sqlite-web`はPythonで作られたSQLiteデータベースブラウザのWebアプリケーションです。主要な機能は、データベースの管理やテーブル・列の操作、データのエクスポート・インポート、SQLクエリの実行などです。コマンドラインオプションで設定を変更でき、Dockerでも簡単に使用できます。



🌸😊You: 
他と比べてどのような特徴がありますか。



🚀🤖Copilot: 
すみません、私はAIアシスタントなので、特定の資料と比較する能力はありません。ただし、一般的にSQLiteデータベースブラウザのWebアプリケーションは、SQLiteデータベースの管理、テーブルや列の操作、データのエクスポート・インポート、SQLクエリの実行などがサポートされています。`sqlite-web`はPythonで書かれているため、その機能はPythonのライブラリを使用しています。また、Dockerを使用して簡単に実行できることも利点の一つです。



🌸😊You: 
もう少し詳しくお願いします。



🚀🤖Copilot: 
すみません、私はAIアシスタントなので、特定の資料と比較する能力はありません。しかし、一般的にSQLiteデータベースブラウザのWebアプリケーションは、SQLiteデータベースの管理、テーブルや列の操作、データのエクスポート・インポート、SQLクエリの実行などがサポートされています。`sqlite-web`はPythonで書かれているため、その機能はPythonのライブラリを使用しています。また、Dockerを使用して簡単に実行できることも利点の一つです。`sqlite-web`は、既存のSQLiteデータベースを操作でき、テーブル、列、インデックスの追加や削除、データのエクスポートとインポートなどがサポートされています。また、SQLクエリの実行も可能で、結果はJSONやCSV形式で取得できます。コマンドラインオプションでポート番号、ホストアドレス、デバッグモードなどを指定できます。Dockerを使用して簡単に実行することもできます。



````
</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
--------------------------------------------------------------------------------------------------------------------
# 目的
  - タイトルの通り
# 使用シーン
  - 資料の把握が必要となった際に、内容を簡潔に把握するために利用。
# 期待される効果
  - 要約し、特徴を掴むことを期待。
# キーワード
  - **簡潔に要約** . . . 資料の文章を要約することを期待。**シンプルに整理** など、別の言い回しでも可。
  - **もっと簡潔に** . . . より簡潔に要約することを期待。
  - **他と比べて** . . . 生成AIの持つ情報と比較することを期待。**一般的なものと比較して** など、別の言い回しでも可。
  - **どのような特徴が** . . . 資料の特徴を炙り出す。要約とは異なる観点の回答を期待。 
  - **もう少し詳しく** . . . 簡潔になりすぎた場合に説明を追加することを期待。**〇〇について具体的に** などキーワード指定も可。
# 詳細な説明
  - 生成AIチャットの利用方法としては、初歩的な内容となります。
  - 作成した資料のレビュー・補足説明追加・清書などの用途にも、用いることができます。
  - 上記のキーワード以外でも、下記のカスタマイズを通して情報を出力することができます。
  - 資料に対する多角的な情報を得ることで理解の促進を期待します。
# カスタマイズのポイント
  - **資料の各部分に対してどのような改善点が考えられますか。** . . . 資料の内容に改善点を見出し提案することを期待。
  - **上記の改善点を基に修正後の資料を下書きしていただけますか。** . . . 上記より、下書きを期待。
  - **資料の各部分に対して補足説明を加えてください。** . . . 補足説明を期待。
  - **資料の各部分に対して具体例を追加してください。** . . . 具体例を期待。
  - **資料の各部分で用いられている全てのキーワードをリスト化しキーワードを説明してください。** . . . キーワードの理解を促進。
  - **資料の各部分で用いられている全ての専門用語をリスト化し専門用語を詳細に補足説明してください。** . . . 専門用語の理解を促進。
  - **資料の各部分に対してテキストベースにより様々な関連図を作成してください。** . . . 関連図により理解促進を期待。
  - **資料の各部分に対してMermaid構文により様々な関連図を作成してください。** . . . 同上。
  - **資料の各部分で用いられている全てのキーワードを基にテキストベースにより様々なイメージ図を作成してください。** . . . 同上。
  - **資料の各部分で用いられている全てのキーワードを基にMermaid構文により様々なイメージ図を作成してください。** . . . 同上。
  - **下記の資料に対する解説書を作成してください。フェーズ１から段階的に完成度を高めるものとします。** . . . 全体の解釈を期待。
  - **下記の資料に対して想定され得る限りのFAQをリスト形式で作成してください。** . . . FAQ形式の理解促進を期待。
  - **下記の資料に対する応用例をいくつか検討してください。どのような場面で役に立ちますか。** . . . 利用イメージの明確化。
  - **下記の機能について改善すると良い機能や追加すると良い機能があれば教えていただけますでしょうか。** . . . 今後の期待を明確化。
# 注意事項
  - より詳細に把握するためには、このプロンプトだけでは不十分です。
  - このプロンプトは資料を把握する取っ掛かりとして利用し、その後は元の資料自体を詳しく把握する必要があります。
--------------------------------------------------------------------------------------------------------------------
````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>










### 🟡 資料を多角的な視点で再構成したい
#### プロンプトテンプレート
````markdown
今からあなたに、「資料の基本的な見出しリスト」をベースとし、各見出しに応じた内容を調査、資料を再構成していただきます。
資料は後でお見せしますので、まずは「資料の基本的な見出しリスト」を把握してください。
（資料の基本的な見出しリスト　参照）
````
````markdown
「資料の基本的な見出しリスト」の見出しで、下記の資料を再構成してください。
情報が不足している個所については、調査して補うか、仮で下書きとしてください。
まずは、再構成後の見出しと見出しに対する1行文の説明だけ下書きしてください。
# 資料
（資料　省略）
````
````markdown
それではこの内容で各見出しごとに、具体的な記述を加えて行ってください。
まずは、表紙からお願いいたします。
````
````markdown
続けてください。
````
<details>
  <summary>資料の基本的な見出しリスト</summary>

````markdown
## 資料の基本的な見出しリスト

1. 文書の基本構成
- 表紙
- 目次
- 概要/サマリー
- はじめに
- 用語定義
- 改訂履歴

2. 目的・背景
- 目的
- 背景/経緯
- 前提条件
- 適用範囲
- 関連文書

3. 現状と課題
- 現状分析
- 課題/問題点
- リスク
- 制約条件
- 要件定義

4. 検討・対応
- 検討内容
- 調査結果
- 代替案
- 比較検討
- 解決策
- 暫定対応
- 恒久対応

5. 実施計画
- スケジュール
- 作業項目
- 役割分担
- 予算
- マイルストーン

6. 設計・仕様
- 基本設計
- 詳細設計
- 機能仕様
- 外部仕様
- 内部仕様
- インターフェース仕様

7. システム構成
- ハードウェア構成
- ソフトウェア構成
- ネットワーク構成
- セキュリティ要件

8. 運用・管理
- 運用手順
- 管理体制
- 監視項目
- バックアップ
- 障害対応
- メンテナンス

9. プロセス
- 入力
- 処理
- 出力
- データフロー
- ワークフロー

10. 評価・検証
- テスト計画
- テスト項目
- 評価基準
- 品質指標
- 検証結果

11. 今後の展開
- 展望
- 中長期計画
- 課題と対策
- ロードマップ
- 推進体制

12. 付録
- 参考資料
- 用語集
- 補足説明
- 添付資料
- 索引

````
</details>
<details>
  <summary>生成結果</summary>

````markdown
（省略）
````
</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
--------------------------------------------------------------------------------------------------------------------
# 目的
  - タイトルの通り
# 使用シーン
  - 資料を作成する際に、ベースとなる資料を基に、多角的な視点で下書きをする。
# 期待される効果
  - 多角的な視点で下書きすることで、プロジェクト全体を俯瞰することを期待。
# キーワード
  - **今からあなたに** **していただきます。** . . . これから要求する内容を予告し、今回の会話では事前準備であることを伝達。
  - **ベースとし** . . . ベースとなる資料を示す。ここには、定義やルールを示すものを入れる前提。
  - **資料は後でお見せしますので** **まずは** **してください** . . . 今回の会話では事前準備であることを念押し。
  - **の見出しで** . . . ベースとなる資料の、具体的にどのルールかを明確にする。
  - **情報が不足している個所については、調査して補うか、仮で下書きとしてください。** . . . 抜けや漏れが生じないよう出力を要求。
# 詳細な説明
  - プロジェクト全体を俯瞰することで、今後発生が想定される課題などを洗い出し、タスクとして進める材料にします。
  - 下書きから、その時点で作成が必要な範囲で資料を再構成することで、第三者が理解しやすい内容にすることができます。
# カスタマイズのポイント
  - **この資料で記載されている機能をカスタマイズする方向で資料を構成してください。** などのように、資料の方向性を指示することも可能。
# 注意事項
  - 誤った情報や無関係の情報が多く混在します。ここからさらに情報を整理する必要があります。
  - 利用する生成AIによっては多大な文章量になるため、かえって精査に時間がかかり効率がダウンする危険性もあります。
--------------------------------------------------------------------------------------------------------------------
````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>





### 🟡 資料より多角的な視点で図表を作成したい
#### プロンプトテンプレート
````markdown
今からあなたに、「資料の基本的な図表リスト」をベースとし、各見出しに応じた内容を調査、図表をMermaid形式で作成していただきます。
資料は後でお見せしますので、まずは「資料の基本的な図表リスト」を把握してください。
（資料の基本的な図表リスト　参照）
````
````markdown
「資料の基本的な図表リスト」の図表で、下記の資料を再構成してください。
情報が不足している個所については、調査して補うか、仮で下書きとしてください。
（資料　省略）
````
<details>
  <summary>資料の基本的な図表リスト</summary>

````markdown
## 資料の基本的な図表リスト

1. 概念図・全体像
- システム概念図
- 全体構成図
- アーキテクチャ図
- ビジネスモデル図
- エコシステム図
- 適用範囲概念図

2. 関係・構造図
- 組織関連図
- 利害関係者マップ
- システム関連図
- 機能関連図
- 階層構造図
- マインドマップ
- 相関図
- 因果関係図

3. プロセス・フロー図
- 業務フロー図
- システムフロー図
- データフロー図
- ユースケース図
- シーケンス図
- 状態遷移図
- アクティビティ図
- 作業工程図

4. レイアウト・配置図
- 画面レイアウト図
- サイトマップ
- ネットワーク構成図
- システム配置図
- 設備配置図
- インフラ構成図

5. データ構造図
- ER図（実体関連図）
- クラス図
- データモデル図
- テーブル関連図
- データマッピング図

6. 分析・評価図
- SWOT分析図
- 比較分析図
- リスクマップ
- マトリクス図
- パレート図
- 特性要因図（フィッシュボーン）
- ガントチャート
- バリューチェーン図

7. パフォーマンス・メトリクス
- グラフ・チャート
- KPI dashboard
- メトリクス可視化
- トレンド分析図
- 分布図
- ヒートマップ

8. UI/UX関連
- ワイヤーフレーム
- モックアップ
- プロトタイプ
- ユーザージャーニーマップ
- カスタマーエクスペリエンスマップ

9. イメージ・イラスト
- コンセプトイメージ
- 完成イメージ
- 操作イメージ
- 説明用イラスト
- インフォグラフィックス

10. 比較・対照図
- 現状vs将来像
- Before/After図
- 比較表
- ギャップ分析図
- 優先度マトリクス

11. 計画・ロードマップ
- プロジェクトタイムライン
- マイルストーン図
- ロードマップ
- 展開計画図
- 段階的導入図

12. セキュリティ関連
- セキュリティ境界図
- ネットワークセグメント図
- アクセス制御図
- 脅威分析図

13. 運用保守関連
- 監視項目マップ
- 障害対応フロー図
- バックアップ構成図
- 運用体制図

これらの図表は、文書の内容や目的に応じて適切に選択し、必要に応じて組み合わせることで、より効果的な情報伝達が可能になります。また、各図表には以下のような補足情報を付けることで、より理解を深めることができます：

- 図表番号
- タイトル
- 凡例
- 注釈・補足説明
- 参照元
- 更新履歴
- バージョン情報

````
</details>
<details>
  <summary>生成結果</summary>

````markdown
（省略）
````
</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
--------------------------------------------------------------------------------------------------------------------
# 目的
  - タイトルの通り
# 使用シーン
  - 資料を作成する際に、ベースとなる資料を基に、多角的な視点で図表を作成する。
# 期待される効果
  - 多角的な視点で図表を作成することで、プロジェクト全体の理解促進を理解しやすくする。
# キーワード
  - **今からあなたに** **していただきます。** . . . これから要求する内容を予告し、今回の会話では事前準備であることを伝達。
  - **ベースとし** . . . ベースとなる資料を示す。ここには、定義やルールを示すものを入れる前提。
  - **資料は後でお見せしますので** **まずは** **してください** . . . 今回の会話では事前準備であることを念押し。
  - **の図表で** . . . ベースとなる資料の、具体的にどのルールかを明確にする。
  - **情報が不足している個所については、調査して補うか、仮で下書きとしてください。** . . . 抜けや漏れが生じないよう出力を要求。
# 詳細な説明
  - プロジェクト全体を理解しやすくするすることで、第三者が理解しやすい内容にすることができます。
# カスタマイズのポイント
  - **この資料で記載されている機能をカスタマイズする方向で資料を構成してください。** などのように、資料の方向性を指示することも可能。
  - **見た目をよくするために、できるだけ多種多様な図表で示してください。** などのように、資料の方向性を指示することも可能。
# 注意事項
  - 誤った情報や無関係の情報が多く混在します。ここからさらに情報を整理する必要があります。
--------------------------------------------------------------------------------------------------------------------
````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>






### 🔴🟡🟢 
#### プロンプトテンプレート
````markdown

````
<details>
  <summary>生成結果</summary>

````markdown

````
</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
--------------------------------------------------------------------------------------------------------------------
# 目的
  - タイトルの通り
# 使用シーン
  - 
# 期待される効果
  - 
# キーワード
  - **** . . . 
# 詳細な説明
  - 
# カスタマイズのポイント
  - 
# 注意事項
  - 
--------------------------------------------------------------------------------------------------------------------
````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>





## タグ2
# 技術
## プログラミング
## データサイエンス
## ウェブ開発
# 創造的
## アート
## ライティング
## 音楽
# 学術
## 研究
## 教育
## 統計
# その他
## ビジネス
## マーケティング
## 健康

