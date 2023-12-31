# 未来図の可視化と共有

## 教材概要
この教材では、PythonのライブラリであるMatplotlibを使用して、山梨県の未来図を可視化し、FastAPIを用いてWebAPIを作成し、未来図を共有する方法を学びます。具体的には、OpenCVで解析した画像データを基に、山梨県の未来図を作り、それをMatplotlibでグラフ化します。その後、FastAPIでWebAPIを作成し、作成した未来図をWeb上で共有できるようにします。

## 教材テキスト
1. Matplotlibの基本的な使い方を学びます。具体的には、データを基にしてグラフを作成し、グラフの見た目を調整する方法を学びます。
2. OpenCVで解析した画像データを基に、山梨県の未来図を作成します。この時点ではPythonのスクリプトとして実行することを目指します。
3. FastAPIを用いてWebAPIを作成します。このAPIは、未来図を取得するためのエンドポイントを持つようにします。
4. FastAPIで作成したWebAPIを使って、未来図をWeb上で共有できるようにします。具体的には、APIのエンドポイントを叩いて未来図を取得し、ブラウザで表示する方法を学びます。

## サンプルコード
```python
# 1. Matplotlibの基本的な使い方
import matplotlib.pyplot as plt

## 作業手順
1. Matplotlibの基本的な使い方を学び、サンプルコードを実行してみましょう。理解したら、自分のデータでグラフを作成してみましょう。
2. OpenCVで解析した画像データを基に、山梨県の未来図を作成するコードを実装します。この時、Matplotlibでグラフを作成できるデータ形式になるように注意しましょう。
3. FastAPIを用いてWebAPIを作成します。"/future_map"のエンドポイントで未来図を返すようにコードを実装します。
4. FastAPIで作成したWebAPIを使って、未来図をWeb上で共有できるようにします。ブラウザでAPIのエンドポイントを叩いて未来図が表示されることを確認しましょう。