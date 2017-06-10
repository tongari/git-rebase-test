# リベースの主要コマンド（たぶん）

- {取り入れたいブランチ名}を{現在いるブランチ}に取り込む
 ```bash 
 git rebase {取り入れたいブランチ名}
 ```

- rebaseした際コンフリクトが起こり、手動で解決した後に叩くコマンド
 ```bash
 git rebase --continue
 ```

- rebaseのキャンセル
 ```bash 
 git rebase --abort
 ```

# 参考サイト

http://www.backlog.jp/git-guide/stepup/stepup1_4.html

http://www.backlog.jp/git-guide/stepup/stepup2_8.html


# その他gitコマンド

- ブランチ切り替え
 ```bash
 git checkout {ブランチ名}
 ```

- 現在地から{新しいブランチ}を作成しその{新しいブランチ}に切り替える
 ```bash
 git checkout -b {新しいブランチ名}
 ```

- ローカルブランチを削除
 ```bash
 git branch -d {ブランチ名}
 ```

- リモートブランチを削除
 ```bash
 git push -d origin {ブランチ名}
 ```

- カレントのブランチに別ブランチをマージする
 ```bash
 git merge {取り込みたいブランチ名}
 ```
