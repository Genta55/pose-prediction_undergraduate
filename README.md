# pose-prediction_undergraduate
学部時代におこなったOpenPoseとLSTMによる骨格座標の時系列予測に関する研究をまとめた。

## 内容
- `lstm_aikido.ipynb`:OpenPoseで取得した骨格座標データ（CSV形式）を入力として、LSTMモデルによる時系列予測を実施。
- `sample1.png`:取得データの可視化。matplotlibで各関節の動きの推移をグラフ表示。
- `sample2.mp4`:動画データ上にOpenPoseの骨格検出結果とグラフを重ね合わせた映像のデモ。

## 使用技術
- OpenPose
- TensorFlow / LSTM
- OpenCV / pandas / numpy / matplotlib

## 実行環境
- Python 3.10
- Anaconda / Jupyter Notebook

## 動画データに関する注意事項
- 本プロジェクトに含まれる動画および骨格表示映像には、合気道の演武者が登場します。  
- 当該人物には、GitHub上での公開に関して事前に文書、および口頭の両方で同意を得ています。  
- 肖像権やプライバシーの保護に最大限配慮しておりますが、問題があれば即時削除対応をいたします。
