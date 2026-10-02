# jotang-recruit-2026-git

这个仓库是焦糖工作室 Git 入门题。

## Git 学习记录

### git clone

把远程仓库复制到本地

```bash
git clone https://github.com/ressuir/jotang-recruit-2026-git.git
```

### git status

看现在有哪些文件被修改了，有哪些还没加入暂存区

```bash
git status
```

### git add

把这次准备提交的修改放进暂存区

```bash
git add README.md
```

如果想把当前目录里的修改都加进去

```bash
git add .
```

### git commit

把暂存区里的内容保存成一次提交

```bash
git commit -m "add learning notes"
```

`-m` 后面就是这次提交的说明

### git push

把本地已经 commit 的内容同步到 GitHub

```bash
git push
```

### .gitignore

用来让 Git 忽略一些我不想跟踪的文件

这次用了

```gitignore
.idea/
```

主要是不把 IDEA 自动生成的配置文件放进仓库

## 我的理解

Git 主要是在本地记录文件版本，GitHub 是把 Git 仓库放到远程。

我这次实际走的流程基本就是

```text
改文件
→ git status
→ git add
→ git commit
→ git push
```

`git add` 不是上传，`git commit` 也还只是在本地，真正同步到 GitHub 是 `git push`
