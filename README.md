# 計測自動制御東北支部研究会用テンプレート

## 参考
[typst-jp-conf-template (Shunsuke KIMURA/kimushun1101)](https://github.com/kimushun1101/typst-jp-conf-template)  

使用方法や推奨環境についても参考元を参考にしていただきたい．

## 使い方

clone後，ローカルのtypst環境にてコンパイル可能．   
VScodeでの使用を想定している．

## ディレクトリ構成

.  
┣ figs  
┃ ┗ fig1.svg  
┣ libs  
┃ ┣ refs.yml  
┃ ┣ sice.csl  
┃ ┣ template.pdf  
┃ ┗ template.typ  
┣ main.pdf  
┣ main.typ  
┗ README.md  

## 各種ファイル形式の説明

基本はyml，csl，typの3種類のみでよい．  
| ディレクトリ | 含まれるファイルの種類          |
| ------------- | --------------------------- |
|**yml**| 可読性の高いデータ記述言語のファイル形式．参考文献の一覧を格納している．  |
|**csl**| 引用形式を整えるためのファイル形式．参考元の形式を参考に一部研究会用に体裁を変更している．  |
|**typ**| typstの本文や各種関数を格納したファイル．  |


