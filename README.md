# README

# このリポジトリの使い方
## docker編
1. docker-compose.ymlのportsを他のコンテナと被らないものにする(appのcommandにもportsがあるので注意！)
2. container_nameの名前を適当なものに変更

## git編
1. このリポジトリをcloneする
 `git clone git@github.com:dev-kozaka/rails_base.git`
2. 新しいリポジトリを作成
3. 新しいリポジトリに繋げる
 `git remote add 新しいリポジトリのssh`
4. `git remote -v`で新しいリポジトリに繋がっているか確認
5. 新しいリポジトリにpush
