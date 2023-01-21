## Reset回滚
使用--hard回滚远程分支（注意：使用--hard参数会丢失当前工作区的所有修改）  
> git reset --hard <HEAD>

## Fetch和Merge使用
使用Fetch拉取远程分支到本地  
> git fetch origin main  

使用log查看本地分支与远程分支差异  
> git log -p dev..origin/main  

合并远程分支到本地分支  
> git merge origin/main  