# 3. FastAPIを用いたWebAPIの作成

## 教材概要
このモジュールでは、PythonのFastAPIフレームワークを用いてWebAPIを作成します。APIはウェブカメラから取得した果物のデータを受け取り、そのデータをデータベースに保存する機能を持ちます。

## 教材テキスト
1. FastAPIの導入：FastAPIはPythonで書かれた、非常に高速なWebフレームワークです。FastAPIを使用するためには、まずFastAPIをインストールする必要があります。`pip install fastapi`と`pip install uvicorn`を実行してFastAPIとuvicornをインストールします。

## サンプルコード
```python
from fastapi import FastAPI
from pydantic import BaseModel
from sqlalchemy import create_engine

## 作業手順
1. 上記のサンプルコードを`main.py`という名前のファイルに保存します。
2. コマンドプロンプトから`uvicorn main:app --reload`を実行します。これにより、FastAPIアプリケーションが起動します。
3. ブラウザから`http://localhost:8000/docs`にアクセスします。FastAPIにより自動生成されるドキュメンテーションが表示されます。
4. ドキュメンテーションからPOSTリクエストを送信し、APIが正常に動作することを確認します。