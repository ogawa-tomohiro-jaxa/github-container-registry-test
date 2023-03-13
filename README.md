# github-container-registry-test
GitHub ActionsでDockerイメージをGitHub Container Registryにpushする
参考：https://yoshinorin.net/articles/2021/02/23/ghaction-ghcr/

## 手順
1. アクセストークンを発行（管理者のみ）
2. secretの設定
3. dockerをbuildしてpushするGitHub Actionsのyamlを作成
4. tagを指定してpush

