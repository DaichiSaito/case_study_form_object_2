# 複数モデル同時登録のユースケースのサンプル

## 要件
- 企業情報と同時にユーザー情報も登録するようなフォームを想定
- Company(name, address)
  - name: null禁止
  - address: null禁止
- User(name, email, password)
  - name: null禁止
  - email: null禁止, ユニーク


# 新規作成画面
[![Image from Gyazo](https://i.gyazo.com/b34ef19d719d45d951076bd9ef470f3c.png)](https://gyazo.com/b34ef19d719d45d951076bd9ef470f3c)
