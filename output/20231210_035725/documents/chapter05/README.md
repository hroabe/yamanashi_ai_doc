
## 作業手順教材タイトル
1. FastAPIとPyTorchをインストールします。
2. 上記のサンプルコードを実行します。
3. Postmanやcurlなどを使って、APIにデータを送信し、予測結果を確認します。
"AIを用いた山梨の収穫時期判定システムの完成"

## 教材概要
この教材では、AIを用いて山梨の収穫時期を判定するシステムの完成を目指します。具体的には、PyTorchを用いて山梨の写真から特徴を抽出し、その特徴が収穫時期を示すものであるかを判定します。そして、その結果をFastAPIを用いてWebアプリケーション上に表示します。最終的には、このシステムを用いて山梨の最適な収穫時期をAIが判定することを目指します。

## 教材テキスト
1. まずは、PyTorchを用いて山梨の画像から特徴を抽出します。これにはConvolutional Neural Network(CNN)を用いて、画像から特徴を抽出することを学びます。
2. 次に、抽出した特徴が山梨の収穫時期を示すものであるかを判定します。この判定には、抽出した特徴を入力とするニューラルネットワークを設計します。
3. 最後に、FastAPIを用いてWebアプリケーションを開発します。このWebアプリケーションでは、山梨の写真をアップロードし、その写真からAIが収穫時期を判定し、結果を表示する機能を実装します。

## サンプルコード
```
# PyTorchでの特徴抽出と判定
import torch
from torchvision import models, transforms
from PIL import Image