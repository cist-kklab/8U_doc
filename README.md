個票Webシステム 利用方法
====

## システムの利用開始

[https://ltvs.uela.cloud/8u/](https://ltvs.uela.cloud/8u/) にアクセスしてください。

事務局から配布された各大学担当者のアカウントIDとパスワードで、ログインしてください。

ログインに成功すると、大学担当者のメールアドレスにワンタイムパスワードが送信されます。このワンタイムパスワードを入力することで、操作が可能となります。

:warning: ワンタイムパスワードは `8u@ltvs.uela.cloud` から送信されます。このアドレスからのメールが正しく受信されるよう、迷惑メールフィルタなどを設定してください。

## アカウント編集

ログインしている大学担当者の情報を変更できます。

担当者が変更になった場合は、速やかに情報の反映をお願い致します。

また、パスワードは英数大文字・小文字や記号を用いた強固なものを設定してください。

## テストの結果登録

学生のテスト結果を登録します。

### 通常の登録方法

1. `テストの結果登録と個票の作成` をクリックします。
2. テストの種別の一覧が表示されます。テスト結果を登録したいテスト種別を選択します。
  - テスト結果を登録したいテスト種別が一覧にない場合は 期間を `期間外` に設定してください。
3. テストの結果登録画面が表示されます。テスト結果を登録したい科目の横の `結果登録` ボタンを選んでクリックしてください。 
4. 選んだ科目の結果登録画面が表示されます。**結果登録用シートを `ダウンロードボタン` で入手**してください。
  - :warning: **結果登録用シートの内容は、テスト種別や科目ごとに異なります。他の科目の登録用に使い回さないでください**。
5. 結果登録用シートを Microsoft Excel で開き、学生のテスト結果を貼り付けて保存してください。
  - :warning: **数学の場合のみ、計算シートの結果を貼り付けます**。詳しくは下の「数学の結果登録の手順」をご覧ください。
6. `ファイルを選択` で編集した結果登録用シートを選択し、 `確認ページへ` をクリックしてください。
7. 確認ページでは、データを登録する学生の一覧が表示されます。学生の一覧に抜けがなければ、画面下の `登録する` ボタンをクリックしてください。
8. テスト結果がシステムに登録されます。**登録するテスト結果の量により、待ち時間が異なります。画面を閉じずにお待ち下さい**。
9. `テスト結果の登録が完了しました!` という枠が表示されたら、`登録を終了する` ボタンをクリックして下さい。

:warning: すべての科目を登録しなくても、その時点の個票を作成することができます。その場合は 個票のダウンロード の手順を参考にしてください。

:warning: 科目が同じテスト（たとえば、英語のリスニングありとなし、数学の数的指向、理系1、理系2）などは、どれか一方にのみテスト結果を登録できま
す。

:warning: 誤って登録したデータをシステムから削除したい場合は、問い合わせ先までご連絡ください。なお、今後、各大学の担当者が削除できる機能を提供する予定です。


### 数学の結果登録の手順

数学（数的指向、理系1・理系2・微積1・2）の場合は、テスト結果を下のエクセルシートで計算し、その計算結果を貼り付ける必要があります。

- 2016年度
 - [プレイスメントテスト用計算シート](raw/master/mathSheet/math_placement_2016.xlsx)
 - [到達度テスト用計算シート](raw/master/mathSheet/matn_achievement_B_2016.xlsx)
 - 黄色のシート部分に計算された内容を、テスト結果の登録用シートに**値をペースト**で貼り付けてください。

### 学生の結果登録

## 個票のダウンロード

登録したテスト結果をもとに個票を作成し、ダウンロードできます。

### 個票の作成

1. `テストの結果登録と個票の作成` をクリックします。
2. テストの種別の一覧が表示されます。個票を作成したいテスト種別を選択します。
  - 個票を作成したいテスト種別が一覧にない場合は 期間を `期間外` に設定してください。
3. テストの結果登録画面が表示されます。画面下部の `個票のダウンロード` ボタンをクリックします。
4. 個票が作成されます。**登録されているテスト結果の量により、待ち時間が異なります。画面を閉じずにお待ち下さい**。
5. `個票の作成が完了しました` という枠が表示されたら、下のどちらかのボタンをクリックして個票をダウンロードしてください。
 - 印刷マクロつきシート：プリンタでの印刷やpdfへの出力が可能なExcelシートをダウンロードできます。
 - 印刷マクロなしシート：個票の表示用データのみ記載されたExcelシートをダウンロードできます。

### 個票の印刷

1. 上記の手順で作成された 印刷マクロつきシート を Windows の Microsoft Excel で開きます。
2. `大学データ` セルを表示します。
3. 印刷方式にあわせて、表示されているボタンのいづれかをクリックします。
    - **個別で個票を発行する：** 一人分の個票を印刷（もしくはpdf化）します。`個人データ` セルの F列（ID） の値を指定してください。
    - **範囲を指定して個票を発行する：** 複数人分の個票を印刷（もしくはpdf化）します。 `個人データ` セルの F列（ID） の値を指定してください。
    - **すべての学生の個票を発行する：** `個人データ` セルの全員分の個票を印刷（もしくはpdf化）します。



## 問い合わせ先

以下のメールアドレスにご連絡ください。

8大学連携事務局 個票Webシステム担当：`8u@ltvs.uela.cloud`

 