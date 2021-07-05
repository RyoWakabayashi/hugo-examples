# Hugo examples

Hugo の使用例

## 実行環境

Hugo 0.84.4

## 実行方法

### ローカル環境での起動

```bash
hugo server -D
```

## 編集環境

- Node.js 16.4.1
- Python 3.9.6
- Yarn 1.22.10

asdf がある場合、以下のコマンドでインストール可能

```bash
asdf plugin-add nodejs \
    ; asdf plugin-add python \
    ; asdf plugin-add yarn \
    && asdf install
```

依存パッケージをインストールする

```bash
yarn \
    && pip install --requirement requirements.txt
```

## 編集方法

静的解析の自動実行を設定する

```bash
pre-commit install
```

feature ブランチを切り、コミット、プッシュ、プルリクエストを行う
