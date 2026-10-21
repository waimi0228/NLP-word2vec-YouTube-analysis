# YouTube データ収集と Word2Vec（CBOW）の実装

## 内容
- **YouTube.py**：YouTube Data API v3 で指定チャンネルの動画一覧を取得し、
  再生数・高評価数・コメント数・コメント本文を収集して表形式で保存
- **CBOW.py**：jieba で中国語テキストを形態素分割し、
  Keras で CBOW（Continuous Bag-of-Words）モデルを一から実装して単語ベクトルを学習

## 使用技術
Python / YouTube Data API v3 / pandas / jieba / TensorFlow (Keras)

## 実行方法
```bash
pip install -r requirements.txt
# YouTube.py の API_KEY に自分の API キーを設定してから実行
python YouTube.py
python CBOW.py
```
