# Final_report_shioya
深層学習の授業の最終課題レポートの使用したプログラムと、一部のデータです。

### final_report.ipynb
は、メインのファイルです。Google Colabを前提に作成したファイルであるため、他の環境で動かす場合は都度コードを変更してください。

### data/dataset.csv
は、スクレイピングによって取得した歌詞データを格納しています。このファイルの作成に最も時間がかかるため、このファイルだけはあらかじめアップロードしておきました。このファイルをアップロードしておけば、final_report.ipynbにおける ## 歌詞データの収集 のブロックはスキップ可能です。

上記２つのファイルに加えて、final_report.ipynbと同じフォオルダ上に、checkpointsとimagesという空のフォルダを作成することで、モデルの各エポックでの保存と画像ファイルの出力が行なえます。
