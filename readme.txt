rebase是啥玩意·
又一个小伙伴修改并推送至远程

一个小伙伴修改并推送至远程仓库
在dev-fix-bug分支修改bug，后master将修改的内容“复制”过去(因为分支一般都是从master复制的，所以master有bug,那么分支应该也有bug，所以在分支修改且提交后，master分支git cherry-pick <commitid>将此次修改拷贝过去。或者从master上另起一个bug分支，修改完，master分支merge,再删除bug分支，现有分支再git cherry-pick <commitid>)
fast forward
no fast forward
master
dev
测试merge
Git is a version control system.oooooooooooxxxxxxxxxxxxo
Git is free software.
qwuioewodjodijowkopedskpwekopdkopqwkopdkopqwkopdkopqwdskopqwdskop
1234
