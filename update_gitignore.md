# update .gitignore

#### **#git**

---

当项目已经被**git**托管后，需要调整忽略文件时，修改.gitignore文件, 调整要忽略的内容  
然后清空下之前的托管历史，再次提交即可

> git rm -r: Allow recursive removal when a leading directory name is given.  
>git rm --cached: Use this option to unstage and remove paths only from the index. Working tree files, whether modified or not, will be left along.

```shell
>$ git rm -r --cached .
>$ git add .
>$ git commit -m 'commit message'
```
