# github-practice-for-kadasapo120

##change directory
ターミナルでusers/kawahatasakurakoにいるときに cd workspace と打つとworkspaceに移動できる。

## clone
git cloneは　users/kawahatasakurako/workspace
に入って、そこでgit clone　する。

git clone　の後は、
1, githubの ＜＞code を押す（緑色の）
2, そこのSSHを押す。
3, 出てきた git@... をコピーボタンでコピーする。
4, それをgit cloneの後に貼り付ける。

ex) git clone git@github.com:Ryuichi-Takeda/github-practice-for-kadasapo1203.git

## brach
mainブランチからからdevelop/'名前'ブランチを切る。
1, リポジトリの画面の左に側にある main を押して Find or create brach の欄にbranch名（develop/'名前'）を入力し create branch: develop/'名前' from 'main' を押す。
2, vscodeでcloneしてきたファイルを開きそこのターミナルで git fetch と打つ。
3, ターミナルで git checkout develop/'名前' と打って、developにチェックアウトし、そこで作業する。

## commit
作業のキリのいいところでcommitする
1, ターミナルで git add . と打つ。
2, ターミナルで git commit -m '作業でしたこと' と打つ。

## push
pushしてgithub上に提出する。
1, commit した後ターミナル上で git push origin develop/'名前' と打つ。
2, github上でdevelop branchの作業内容が反映されていることを確認する。
