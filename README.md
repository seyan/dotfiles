# dotfiles

1. git-prompt.shとgit-completion.bashの存在確認

gitの補完を有効にするためにはgit-prompt.shとgit-completion.bashを有効にする必要がある。
```
$ ls /usr/local/etc/bash_completion.d/
git-completion.bash git-prompt.sh
```
存在しない場合は、Homebrewでgitをインストールすれば`/usr/local/etc/bash_completion.d/`
の中にシンボリックリンクがおかれる
```
brew install git
```

2. このリポジトリのdotfilesをカレントディレクトリに配置

3. .bash_profileを実行
```
source ~/.bash_profile
```
