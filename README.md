# doc_genai_Prompt_template_collection_-Japanese-
プロンプトテンプレート集（日本語）

# プロンプトテンプレート集 - GitHubリファレンス用

こちらは、作成者が実際に比較検証し作成した、様々な目的に応じたプロンプトテンプレート集です。作成者の用途に応じて修正・最適化されているため、参考にお願いします。

## 利用度の表示について
各プロンプトの見出しには、利用しやすさを3色で示しています。
- 🔴 いまいち：基本的な結果は得られますが、改善の余地があります
- 🟡 まあまあ：概ね期待通りの結果が得られます
- 🟢 つかえる：高い確率で期待通りの結果が得られます

## 注意事項
- 「いまいち」「まあまあ」「つかえる」の評価は目安として参考にしてください。
- プロンプトの内容は適宜修正・最適化してください。

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


You: あなたは何ができますか。１０個ほど答えてください。



Copilot: 1. 情報検索: ユーザーが質問や情報を探しているときに、インターネットやデータベースから情報を提供します。
2. レコメンデーション: ミュージック、映画、本、レストランなど、ユーザーが楽しむためのリソースを提案します。
3. 翻訳: 多くの言語間での翻訳が可能です。
4. 天気予報: 現在の天気や、指定した場所の未来の天気情報を提供します。
5. カレンダー管理: イベントの追加、削除、変更、リマインダーを管理します。
6. 予算管理: 費用の追跡、予算の設定、節約のためのアドバイスを提供します。
7. ニュース更新: ニュース記事や最新のニュース情報を提供します。
8. 健康情報: 健康的なライフスタイルに関するアドバイスや、一般的な健康問題についての情報提供します。
9. エクササイズプラン: ヨガ、ウォーキング、プールジムなどのエクササイズのためのプランを提供します。
10. リラクゼーション: ストレスの軽減、リラクゼーションのためのアドバイスや、瞑想のためのガイドを提供します。



You: 実際にそれぞれ具体的に例を考えてやってみてください。



Copilot: 1. 情報検索: ユーザーが「現在の天気」を尋ねると、現在の天気と、それに対する適切なアドバイス（例：傘を忘れずに带い、雨衣を準備）を提供します。
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
# 目的
  - このプロンプトテンプレート自体には、特に目的はありませんが、生成AIの可能性を感じるためのきっかけとして説明します。お読みいただけますと幸いです。
# 使用シーン
  - 初めてその生成AIを利用する際に、試してみるのも良いと思います。
# 期待される効果
  - その生成AIにどのような傾向があるか、把握できるかもしれません。
# 詳細な説明
  - はじめに、生成AIにはできることとできないことが存在し、ユーザはそれを見極めるために色々と試す必要があります。
  - まずはこのプロンプトの様に、とにかく何でもよいから入力してみる、ということが大事と考えます。
# カスタマイズのポイント
  - 何でも入力してみてください。はじめは色々と入力してみて、どのような回答をするか試してみる良いです。
  - 色々と試していく中で、ユーザにとって意味のある使い方を見出すことができるかもしれません。
  - もし生成AIの可能性を感じたのであれば、次に行うべきこととして、様々なプロンプトを修正・最適化して自分専用のプロンプトテンプレート集を作ってみるのが良い、と考えます。
# 注意事項
  - 生成AIによっては（特にクラウド型は）情報漏洩のリスクがありますので、適切に利用することが重要です。
  - 生成AIの回答によっては、実際にはできなくても「できる」かのように回答したり、正しくない情報をさも正しいかのように回答したりします。
  - 生成AIは、基本的にはAIチャット機能であり、その生成AIが学習した範囲でしか回答しません。
    - 中には実際に、現在の天気や時刻やニュースを調べる機能を有しているものもありますが、この資料の対象ではありません。
    - 中には実際に、アラームの設定やスケジュールの登録など、具体的なタスクを実行できるものもありますが、この資料の対象ではありません。

````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>




### 🟡 生成AIの回答の精度やボリュームを高めたい
#### プロンプトテンプレート
````markdown
powershell で fizzbuzz。

フェーズ1から段階的に完成度を高めるものとします。
````
````markdown
続けてください。
````
<details>
  <summary>生成結果</summary>

````markdown


You: 
powershell で fizzbuzz。

フェーズ1から段階的に完成度を高めるものとします。



Copilot: もちろんです。PowerShellでFizzBuzzを実装する方法について、フェーズ1から段階的に説明します。

フェーズ1: 基本的なFizzBuzzを実装

```
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

フェーズ2: 関数を使ってFizzBuzzを実装

```
function FizzBuzz {
    param (
        [int]$start,
        [int]$end
    )
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

FizzBuzz -start 1 -end 100
```

フェーズ3: 関数をより効率的に行う

```
function FizzBuzz {
    param (
        [int]$start,
        [int]$end
    )
    for ($i = $start; $i -le $end; $i++) {
        $output = ""
        if ($i % 3 -eq 0) {
            $output += "Fizz"
        }
        if ($i % 5 -eq 0) {
            $output += "Buzz"
        }
        if ($output -eq "") {
            $output = $i
        }
        Write-Output $output
    }
}

FizzBuzz -start 1 -end 100
```

フェーズ4: ハッシュテーブルを使用してFizzBuzzを実装

```
function FizzBuzz {
    param (
        [int]$start,
        [int]$end
    )
    $hash = @{
        3 = "Fizz"
        5 = "Buzz"
    }
    for ($i = $start; $i -le $end; $i++) {
        $output = ""
        foreach ($key in $hash.Keys) {
            if ($i % $key -eq 0) {
                $output += $hash[$key]
            }
        }
        if ($output -eq "") {
            $output = $i
        }
        Write-Output $output
    }
}

FizzBuzz -start 1 -end 100
```

以上がフェーズ1からフェーズ4までのFizzBuzzの実装方法です。それぞれのフェーズでは、コードの効率性や可読性を改善していきます。



You: 続けてください。



Copilot: フェーズ5: オプション引数を使用してFizzBuzzを実装

```
function FizzBuzz {
    param (
        [int]$start,
        [int]$end,
        [string]$fizz = "Fizz",
        [string]$buzz = "Buzz"
    )
    for ($i = $start; $i -le $end; $i++) {
        $output = ""
        foreach ($key in $hash.Keys) {
            if ($i % $key -eq 0) {
                $output += $hash[$key]
            }
        }
        if ($output -eq "") {
            $output = $i
        }
        Write-Output $output
    }
}

FizzBuzz -start 1 -end 100 -fizz "FOO" -buzz "BAR"
```

フェーズ6: 構文解析を使用してFizzBuzzを実装

```
function FizzBuzz {
    param (
        [string]$expression,
        [int]$start,
        [int]$end
    )
    for ($i = $start; $i -le $end; $i++) {
        $output = Invoke-Expression "$expression"
        Write-Output $output
    }
}

FizzBuzz -expression "if ($i % 3 -eq 0 -and $i % 5 -eq 0) { 'FizzBuzz' } elseif ($i % 3 -eq 0) { 'Fizz' } elseif ($i % 5 -eq 0) { 'Buzz' } else { $i }" -start 1 -end 100
```

以上がフェーズ5からフェーズ6までのFizzBuzzの実装方法です。それぞれのフェーズでは、コードの柔軟性や機能性を改善していきます。


````
</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
# 目的
  - タイトルの通り
# 使用シーン
  - とりあえず生成AIで基本的なことから順に何かを出力したい、という時
  - この例では、コーディングタスクだが、ドキュメント生成タスクや、レビュー・分析タスクでも利用できる。
# 期待される効果
  - 基本的なことから順に内容を理解しやすい回答
# 詳細な説明
  - ２つめの「続けて」を繰り返すことで、その生成AIのパフォーマンスを引き出せるかもしれない。
# カスタマイズのポイント
  - 「レベル１から順により詳細にしてください。」「ステップ１からステップバイステップで積み重ねていってください。」など、言い回しを変えてみる。
# 注意事項
  - あえて方向性を示していないことで、多様な回答が得られるようになっている反面、期待した回答が得られにくいかもしれない。
````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>






### 🟢 生成AIの回答の精度やボリュームを高めたい（詳細に指示、方向性を示す）
#### プロンプトテンプレート
````markdown
powershellでfizzbuzz。

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


You: 
powershellでfizzbuzz。

レベル１を最低限要求を満たす内容とし、レベル８を、不特定多数の人間が利用しても問題が無く、
読みやすい、説明しやすい、汎用性の高い内容とします。

初めに、各レベル（レベル１、レベル２，レベル３，レベル４、レベル５、レベル６，レベル７，レベル８）
で目指す完成度の目標を日本語で説明してください。

その後、まずはレベル１の内容だけを示してください。



Copilot: ### レベルごとの目標説明

1. **レベル１**：基本的なFizzBuzz実装
   - 簡単なFizzBuzzプログラムを作成します。
   - 基本的な条件分岐とループを使用します。
   - 無論の問題なく実行できる程度のコードです。
   
2. **レベル２**：関数化
   - FizzBuzz関数を作成し、再利用性を高めます。
   - パラメータを渡して実行できるようにします。
   
3. **レベル３**：拡張性
   - フizzとbuzzの文字列を変更できるようにする機能を追加します。
   
4. **レベル４**：入力チェック
   - 入力値の検証を追加し、不適切な入力に対してエラーメッセージを表示します。
   
5. **レベル５**：拡張機能：FizBuzの数字変更
   - FizzBuzzの数字（3と5）を変更できるようにする機能を追加します。
   
6. **レベル６**：拡張機能：出力形式の変更
   - FizzBuzzの出力形式（コンソールに表示する）を変更できるようにする機能を追加します。
   
7. **レベル７**：拡張機能：複数のFizzBuzzを実行
   - 複数のFizzBuzzルールを同時に実行できるようにする機能を追加します。
   
8. **レベル８**：拡張機能：GUI化
   - FizzBuzzアプリケーションをGUIで実装し、不特定多数の人間が利用しても問題が無く、読みやすい、説明しやすい、汎用性の高い内容とします。

### レベル１の内容

以下は、最適化版のFizzBuzzのPowerShellコードです。

```powershell
for ($i = 1; $i -le 100; $i++) {
    if ($i % 15 -eq 0) { "FizzBuzz" }
    elseif ($i % 3 -eq 0) { "Fizz" }
    elseif ($i % 5 -eq 0) { "Buzz" }
    else { $i }
}
```

このコードは、1から100までの数をループし、各数を3で割った余りが0なら"Fizz"、5で割った余りが0なら"Buzz"、両方で割った余りが0なら"FizzBuzz"、それ以外ならその数値を表示します。



You: レベル２



Copilot: レベル２では、FizzBuzz関数を作成し、再利用性を高めます。以下は、PowerShellでFizzBuzz関数を作成した例です。

```powershell
function FizzBuzz($n) {
    for ($i = 1; $i -le $n; $i++) {
        if ($i % 15 -eq 0) { "FizzBuzz" }
        elseif ($i % 3 -eq 0) { "Fizz" }
        elseif ($i % 5 -eq 0) { "Buzz" }
        else { $i }
    }
}

# 1から100までのFizzBuzzを実行
FizzBuzz 100
```

この関数は、FizzBuzzのルールをカプセル化しています。任意の整数$nを引数に取り、その整数までのFizzBuzzを出力します。この関数は、任意の場面で呼び出せます。



You: レベル４，レベル５，レベル６，レベル７を統合



Copilot: 以下に、FizzBuzzのPowerShellスクリプトをレベル4からレベル7まで統合したものです。このスクリプトでは、入力値を検証し、FizzとBuzzの文字列を変更できるようにし、FizzBuzzの数字も変更できます。また、出力形式を変更できるようにし、複数のFizzBuzzルールを同時に実行できるようにします。

```powershell
function FizzBuzz($n, $fizz = "Fizz", $buzz = "Buzz", $fizzNum = 3, $buzzNum = 5) {
    if ($n -lt 1) {
        Write-Host "エラー: nは正の整数である必要があります。"
        return
    }

    for ($i = 1; $i -le $n; $i++) {
        $result = ""
        if ($i % $fizzNum -eq 0) { $result += $fizz }
        if ($i % $buzzNum -eq 0) { $result += $buzz }

        if ($result -eq "") { $i }
        else { $result }
    }
}

# 1から100までのFizzBuzzを実行
FizzBuzz 100
```

このスクリプトでは、FizzBuzz関数の引数を追加し、それぞれの引数にデフォルト値を設定しています。また、入力値を検証する条件分岐も追加しています。これにより、不適切な入力に対してエラーメッセージを表示できるようになりました。

また、FizzとBuzzの文字列を変更できるようにし、FizzBuzzの数字も変更できるようにしました。これにより、FizzBuzzのルールをカスタマイズできます。

出力形式も変更できるようにし、複数のFizzBuzzルールを同時に実行できるようにしました。これにより、FizzBuzzの複数の条件をカプセル化できます。

````

</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
# 目的
  - タイトルの通り
# 使用シーン
  - とりあえず生成AIで基本的なことから順に何かを出力したいし、ある程度完成形の方向性を示したい、という時
  - この例では、コーディングタスクだが、ドキュメント生成タスクや、レビュー・分析タスクでも利用できる。
# 期待される効果
  - 基本的なことから順に内容を理解しやすい回答であり、方向性がある状態
# 詳細な説明
  - 最初のレベルと最後のレベルの目標を示すだけで、その中間のレベルの目標は生成AIが調整する流れを期待している。
  - 「各レベル（レベル１、レベル２，。。。」としているのは、こうしないと勝手に途中のレベルを省略されてしまうことがあるから明確にしている。
  - はじめに各レベルの目的を示すようにし、まずはレベル１の内容を示すようにすることで、どういった方向性の回答か先にチェックできる。
  - 後続のプロンプトの「レベル２」や、「○○を統合」により、各レベルの目標に該当する内容を取り出すイメージ。
# カスタマイズのポイント
  - 最初のレベルと最後のレベルだけではなく、全てのレベルの目標を明確に示してみるとか。
  - レベル４まで、などと短くしたり、逆にレベル１６まで、と長くしたりする。（長くしすぎると内容が薄くなる可能性もある）
  - 「レベル」を「フェーズ」「ステップ」など、言い回しを変えてみる。
# 注意事項
  - 方向性を示すことで期待した回答が得られやすい反面、かえって回答のバリエーションが減ってしまう可能性もある。
````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>




## タグ2
# 技術
## プログラミング



### 🔴 ソースコード１行を真似してインクリメントして作りたい
#### プロンプトテンプレート
````markdown
*str = str & " , c02 "*

この *VBA* の続きを *c03* から *c10* まで真似して書いてください。
繰り返し構文を用いず 真似するだけでいいです。
````
<details>
  <summary>生成結果</summary>

````markdown
str = str & " , c03 "
str = str & " , c04 "
str = str & " , c05 "
str = str & " , c06 "
str = str & " , c07 "
str = str & " , c08 "
str = str & " , c09 "
str = str & " , c10 "
````
</details>
<details>
  <summary>テンプレート説明</summary>

````markdown
# 目的
  - タイトルの通り
# 使用シーン
  - コーディングしていて似たような行を複数行つくる必要があるとき
# 期待される効果
  - 表計算で関数で作成してもいいけどその関数を記述するよりも早いかもしれない
# 詳細な説明
  - 明確に言語、開始終了を示す
  - 「繰り返し構文を用いず」とすることで、勝手に最適化しないようにしている。これがないと、For文で記述したりしようとする。
# カスタマイズのポイント
  - 言語や開始終了の部分
# 注意事項
  - 表計算で管理するほうが後々便利かもしれない。。。
````
</details>

#### タグ
`#コーディング` `#ローカル` `#`

---
<br/><br/> <br/><br/>


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
# 目的
  - タイトルの通り
# 使用シーン
  - 
# 期待される効果
  - 
# 詳細な説明
  - 
# カスタマイズのポイント
  - 
# 注意事項
  - 
````
</details>

#### タグ
`#` `#` `#`

---
<br/><br/> <br/><br/>


