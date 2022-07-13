# exercise-git
练习git使用

- 新建分支
`git checkout -b [branch-name]`

- 新建分支后push到远程
`git push --set-upstream origin branch-one`

- 删除本地分支，不可在要删除的分支上删除自己
`git branch -D [branch-name]`

- 删除远程分支
`git push origin --delete [branch-name]`

- merge 合并分支
`git merge [branch-name]`

- 撤回上一次提交到本地缓存中，撤回版本之后重新提交
`git reset --soft HEAD^`

- 提交本地撤回到远程
`git push origin +HEAD`
