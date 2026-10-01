# jotang-recruit-2026-git

这是我用于完成焦糖工作室 2026 招新 Git 入门题的仓库。

## Git 学习记录

### git clone

把远程仓库复制到本地：

```bash
git clone https://github.com/ressuir/jotang-recruit-2026-git.git
```

### git status

查看当前 Git 仓库的状态，例如有哪些文件被修改、哪些文件还没有加入暂存区：

```bash
git status
```

### git add

把文件的修改加入暂存区：

```bash
git add README.md
```

也可以使用：

```bash
git add .
```

把当前目录下的修改一起加入暂存区。

### git commit

把暂存区中的修改保存成一次提交：

```bash
git commit -m "add learning notes"
```

其中 `-m` 后面是本次提交的说明。

### git push

把本地的提交同步到 GitHub：

```bash
git push
```

### .gitignore

`.gitignore` 用来指定 Git 不需要跟踪的文件或目录。

这次我使用：

```gitignore
.idea/
```

来忽略 IntelliJ IDEA 自动生成的项目配置目录。

## 我的理解

Git 用来记录和管理文件版本，GitHub 用来托管 Git 仓库。

这次实际完成的一次修改流程是：

```text
修改 README.md
→ git status
→ git add README.md
→ git commit
→ git push
```

通过这次操作，我了解了本地修改、暂存区、提交和远程仓库同步之间的基本关系。