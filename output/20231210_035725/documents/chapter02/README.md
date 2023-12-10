# PyTorchを活用した画像解析基礎

## 教材概要
この教材では、PyTorchを活用した画像解析の基礎を学びます。具体的には、Pretrained Modelを用いた特徴抽出と、その特徴を用いた分類方法について学びます。

## 教材テキスト
1. PyTorchの基本的な使い方
2. PyTorchでの画像読み込み方法
3. Pretrained Modelの使い方
4. 特徴抽出と分類方法

## サンプルコード
```
import torch
from torchvision import models, transforms
from PIL import Image

## 作業手順
1. 上記のサンプルコードをPythonファイルに保存します。
2. 任意の画像（ここでは'apple.jpg'）を同じディレクトリに保存します。
3. Pythonファイルを実行します。その際、出力されたトップ5のクラスを確認します。