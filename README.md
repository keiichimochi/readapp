# Mac Accessibility Text Reader

Streamlitを使用したMac用テキストリーダーアプリケーション。macOSのアクセシビリティAPIを使用して、画面上のテキストを正確に取得します。

## 機能

- アクティブウィンドウの情報取得
- フォーカスされているテキストの取得
- テキスト履歴管理
- クリップボードへのコピー機能

## インストール

```bash
# 必要なライブラリのインストール
pip install -r requirements.txt
```

## 使用方法

```bash
# アプリケーションの起動
streamlit run app.py
```

## アクセシビリティ権限の設定

1. System Preferences > Security & Privacy > Privacy > Accessibility を開く
2. ロックアイコンをクリックして変更を許可
3. このアプリケーションをリストに追加して有効化

## ライセンス

MIT
