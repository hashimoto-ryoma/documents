# git-manual
Git Manual for team16 members

## はじめに
/team16/hogehogeに開発物があり、リポジトリ名はhogehogeと想定する。
自分の名前は Aizu Taro、メールアドレスはaizutaro@u-aizu.ac.jpと想定する。

## 下準備
1. 下のリンクからGitをダウンロード&インストール(オプションは変更しなくてよい)<br>[Git](https://git-scm.com/)
2. 名前とメールアドレスを設定する。<br>`git config --global user.name "Aizu Taro"`<br>`git config --global user.email "aizutaro@u-aizu.ac.jp"`

## 最初にすべきこと
1. 開発物のあるディレクトリに移動する。<br>`cd /team16/hogehoge/`
2. ディレクトリをGitで扱えるように設定する。<br>`git init`
3. GitHubにてhogehogeという名前で空のリポジトリを作成する。*Ownerはaizuhack-team16にする事!!*
4. 3.で作成したリモートリポジトリとローカルリポジトリを紐づける。<br>`git remote add origin https://github.com/aizuhack-team16/hogehoge.git`

## コミット&プッシュの仕方
1. 変更したファイルをコミット対象に追加する。<br>`git add *`
2. コミットメッセージを添えてコミットする。<br>`git commit -m "コミットメッセージ"`
3. (初回のみ)おまじない<br>git push --set-upstream origin master
4. リモートリポジトリに転送する。<br>`git push`
