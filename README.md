# GoogleImageGetの使い方

## はじめに
このPythonバッチはGoogle画像検索を使用して1番初めにヒットした画像をExcelにリスト化します。

## 使い方
### 1.SearchList.xlsxのA列の2行目以降に検索したい単語を入れます
![image](https://user-images.githubusercontent.com/79146720/120647470-9b62cc00-c4b5-11eb-92d4-3b5846dbe265.png)

### 2.main.pyを実行します
![image](https://user-images.githubusercontent.com/79146720/120648140-43789500-c4b6-11eb-88c5-a5343c315050.png)

### 3.SearchList.xlsxに検索結果が反映されます
![image](https://user-images.githubusercontent.com/79146720/120648348-7d499b80-c4b6-11eb-9413-d721fdc35f05.png)

## 注意点
### 再実行するときは、取得画像をExcelから削除してください（削除しないと画像が残ります）
![image](https://user-images.githubusercontent.com/79146720/120651432-bc2d2080-c4b9-11eb-813f-0d4cc0806cb4.png)

### 検索した結果の画像はdownloadフォルダに溜まっていきます
![image](https://user-images.githubusercontent.com/79146720/120648568-beda4680-c4b6-11eb-9948-d66b7d7e9e31.png)

### Excelファイル名やパスを変更したい場合はmain.pyのexcel_pathを変更します
![image](https://user-images.githubusercontent.com/79146720/120648698-e7624080-c4b6-11eb-816f-024a671c7efa.png)

### Google画像検索に使用するSeleniumのドライバーを変更したい場合はexecutable_pathを変更します
![image](https://user-images.githubusercontent.com/79146720/120649631-f09fdd00-c4b7-11eb-847c-55c24a1b54af.png)

### Google画像検索の画像のダウンロード先を変更したい場合はfoldernameを変更します
![image](https://user-images.githubusercontent.com/79146720/120648901-1e385680-c4b7-11eb-8b3c-b28dc7920a4a.png)

### 検索したい単語のExcel列を変更したい場合はsearch_columnを変更します
![image](https://user-images.githubusercontent.com/79146720/120649155-6a839680-c4b7-11eb-94d1-63726d2ccfd8.png)

### 検索結果の画像のExcel列を変更したい場合はpaste_columnを変更します
![image](https://user-images.githubusercontent.com/79146720/120649422-b5051300-c4b7-11eb-8090-a2a8c9b1b373.png)

以上です。
