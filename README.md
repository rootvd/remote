# 清空所有的commit记录
```
git checkout --orphan new_branch
git add -A
git commit -am "Update"
git branch -D master
git branch -m master
git push -f origin master
```

