# タイタニックデータセットの配置方法

このフォルダにKaggleのタイタニックデータセットのCSVファイルを配置してください。

## 必要なファイル

1. `titanic_train.csv` - 訓練データ（Survived列を含む）
2. `titanic_test.csv` - テストデータ（Survived列は含まない、オプション）

## ファイルの取得方法

1. [Kaggleのタイタニックコンペティション](https://www.kaggle.com/c/titanic)にアクセス
2. データセットをダウンロード
3. `train.csv`を`titanic_train.csv`にリネーム
4. `test.csv`を`titanic_test.csv`にリネーム（オプション）
5. このフォルダ（`public/`）に配置

## ファイルが存在しない場合

CSVファイルが存在しない場合、アプリケーションは自動的にサンプルデータを使用します。
実際のKaggleデータを使用するには、上記のファイルを配置してください。

## ファイル形式

CSVファイルは以下の列を含む必要があります：
- PassengerId
- Survived (train.csvのみ)
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked











