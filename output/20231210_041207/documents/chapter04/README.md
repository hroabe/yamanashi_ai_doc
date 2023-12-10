# FastAPIでのWebAPI作成

## 教材概要
この教材では、Pythonの高速なAPIフレームワークFastAPIを用いて、WebAPIを作成します。FastAPIの基本的な使用方法から、APIのルーティング、リクエスト・レスポンスのハンドリングまでを学習します。

## 教材テキスト
1. FastAPIのインストール
FastAPIはpipを用いて簡単にインストールできます。
```
pip install fastapi
```

## サンプルコード
```python
from fastapi import FastAPI

## 作業手順
1. まずはFastAPIをインストールします。コマンドラインに以下のコマンドを入力してください。
```
pip install fastapi
```
2. 次に、FastAPIアプリケーションを作成します。Pythonファイル（例: main.py）を作成し、上記のサンプルコードをコピーペーストしてください。
3. 最後に、FastAPIアプリケーションを起動します。コマンドラインに以下のコマンドを入力してください。
```
uvicorn main:app --reload
```
4. ウェブブラウザを開き、`http://localhost:8000/`にアクセスして、`{"Hello": "World"}`が表示されることを確認してください。
5. FastAPIでのWebAPI作成の基本は以上です。公式ドキュメントを参照しながら、より複雑なAPIを作成してみてください。