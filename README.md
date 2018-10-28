1. Markdown Preview Plus等でpreviewを確認
2. `npm run pdf -- raw/hoge.md`にてpdfを作成。 rawディレクトリ以下に作成される
3. 暗号化に用いるパスワードを`.pass`に書いておく
4. `npm run zip`にてrawディレクトリ以下を暗号化。`result.zip`がトップディレクトリに作成される。`npm run unzip`にて複合化可能
