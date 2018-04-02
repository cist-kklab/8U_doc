## テストの結果登録

実施したテストの結果を登録します。

### 操作方法

#### 1. テストの結果登録と個票の作成 機能へ移動

メニュー画面の `テストの結果登録と個票の作成` をクリックすると、テストの種別の一覧が表示されます。テスト結果を登録したいテスト種別を選択します。

:warning: テスト結果を登録したいテスト種別が一覧にない場合は 期間を `期間外` に設定してください。

![テスト種別の選択](https://raw.githubusercontent.com/cist-kklab/8U_doc/master/img/SubmitTestAnswer001.png)

#### 2. テスト種別の選択

テストの結果登録画面が表示されます。テスト結果を登録したい科目の横の `結果登録` ボタンを選んでクリックしてください。

![科目選択](https://raw.githubusercontent.com/cist-kklab/8U_doc/master/img/SubmitTestAnswer002.png)

#### 3. テスト結果の登録

選んだ科目の結果登録画面が表示されます。**結果登録用シート**を `ダウンロードボタン` で入手してください。

:warning: 結果登録用シートの内容は、科目ごとに異なります。

![結果登録シートの入手と更新](https://raw.githubusercontent.com/cist-kklab/8U_doc/master/img/SubmitTestAnswer003.png)

#### 4. 結果登録シートの編集

結果登録用シートを Microsoft Excel で開き、学生のテスト結果（学籍番号、回答結果）を貼り付けて保存してください。

:exclamation: **数学科目は計算シートの結果を貼り付けます**。詳しくは下の [数学科目の登録](#数学科目の登録)をご覧ください。

![結果登録シートの編集](https://raw.githubusercontent.com/cist-kklab/8U_doc/master/img/SubmitTestAnswer004.png)

#### 5. 結果登録シートの送信と確認

シートをダウンロードした画面から、 `ファイルを選択` で編集した結果登録用シートを選択し、 `確認ページへ` をクリックしてください。

確認ページでは、データを登録する学生の一覧が表示されます。学生の一覧に抜けがなければ、画面下の `登録する` ボタンをクリックしてください。

![結果登録の確認](https://raw.githubusercontent.com/cist-kklab/8U_doc/master/img/SubmitTestAnswer005.png)

#### 6. テスト結果の登録の完了

テスト結果がシステムに登録されます。**登録するテスト結果の量により、待ち時間が異なります。画面を閉じずにお待ち下さい**。

`テスト結果の登録が完了しました!` という枠が表示されたら、`登録を終了する` ボタンをクリックして下さい。

![結果登録の完了](https://raw.githubusercontent.com/cist-kklab/8U_doc/master/img/SubmitTestAnswer006.png)

### 諸注意

:pushpin: テスト結果は**上書き・追加登録**されます。テスト結果に**訂正がある場合は、訂正した結果登録シートをそのまま再登録**してください。

:pushpin: すべての科目のテスト結果を登録していなくても、その時点の個票を作成できます。作成は [個票の作成](DownloadSheet.md) の手順を参考にしてください。

:pushpin: テストの種類が複数ある数学・英語・日本語では、どれか一つの種類のテスト結果のみ登録できます。

:pushpin: 誤って登録したテスト結果をシステムから削除したい場合は、解答結果の削除機能をお使いください。

:pushpin: **英語科目のテスト結果はa〜d**（もしくはA〜D）で入力してください。数字で入力された場合は、正しく結果が計算されません。


### 数学科目の登録

数学科目（数的指向、理系1・2、微積1・2）の場合は、テスト結果を下の計算シートで計算し、その結果を結果登録用シートに貼り付けて登録する必要があります。年度ごとにシートは変更されますので、ご注意ください。

|年度|プレイスメントテスト用|到達度テスト用|
|:---|:---|:---|
|2018| [計算シート：共通](https://github.com/cist-kklab/8U_doc/raw/master/mathSheet/math_placement.xlsx)|[計算シートD](https://github.com/cist-kklab/8U_doc/raw/master/mathSheet/matn_achievement_D.xlsx)|
|2017| [計算シート：共通](https://github.com/cist-kklab/8U_doc/raw/master/mathSheet/math_placement.xlsx)|[計算シートC](https://github.com/cist-kklab/8U_doc/raw/master/mathSheet/matn_achievement_C.xlsx)|
|2016| [計算シート：共通](https://github.com/cist-kklab/8U_doc/raw/master/mathSheet/math_placement.xlsx)|[計算シートD](https://github.com/cist-kklab/8U_doc/raw/master/mathSheet/matn_achievement_B.xlsx)|



下図の様に、黄色のセル部分に計算された内容を、テスト結果の登録用シートに**値をペースト**で貼り付けてください。

![数学計算シート](https://raw.githubusercontent.com/cist-kklab/8U_doc/master/img/SubmitTestAnswer007.png)

---

[戻る](../README.md)
