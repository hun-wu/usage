## 远程clone到本地

1. 首先需要做的事情是先在Github=>personal=>setting=>SSH and GPG keys 添加这个电脑。
2. 然后再使用ssh clone你的电脑：

```
git remote set-url origin git@github.com:hun-wu/ToDo.git
```

3. 使用`git remote -v` 检查一下，如果显示如下内容，则成功。

```
origin	git@github.com:hun-wu/usage.git (fetch)
origin	git@github.com:hun-wu/usage.git (push)
```

4. 如果显示的是https开头的，则用的https进行clone的。这一种会比较麻烦，需要输入账号和密码(token)，适用于参与一些项目，而在个人项目不实用。


## git commit
- git commit -m '标题' 
- git commit -m '标题' -m '描述内容'
- 直接git commit ，会弹出vim文本框，输入内容。


## Merge
（待完成）