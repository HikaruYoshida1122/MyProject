# Black Hole Telescope Array Visualization

電波望遠鏡の配置と観測線を地図上に可視化するPythonスクリプトです。

## 内容物

- `Northern_Array_Mapping .ipynb`：北半球の観測局と視線ベクトルを可視化するNotebook  
- `Southern Array Mapping.ipynb`：南半球の観測局と視線ベクトルを可視化するNotebook  
- `dummy_Northern_station.csv`：北半球の観測局のダミーデータ  
- `dummy_Southern_station.csv`：南半球の観測局のダミーデータ  

※ 本リポジトリのCSVファイルはすべてダミーデータを元に構成されています。

## 動作環境

- Python 3.8以上
- pandas
- matplotlib
- cartopy

## 使い方

1. Jupyter Notebook環境を準備してください（Anacondaやpipでjupyterをインストール）。

2. リポジトリをクローンして、フォルダに移動します。

```bash
git clone https://github.com/HikaruYoshida1122/MyProject.git
cd MyProject
``` 

3. ターミナルでJupyter Notebookを起動します。
```bash
jupyter notebook
``` 
4. ブラウザで開いたNotebookのファイルを選び、セルを順に実行してください。
