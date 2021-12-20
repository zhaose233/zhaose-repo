# 朝色のリポジトリ zhaose-repo
朝色的个人源 zhaose-repo

使い方：
```/etc/pacman.conf``` に以下の内容を追加してください

```bash
[zhaose-repo]
SigLevel = Never
Server = https://github.com/weiliang1503/zhaose-repo/releases/download/x86_64
Server = https://hub.fastgit.org/weiliang1503/zhaose-repo/releases/download/x86_64
```

後は DB を更新してください

```bash
sudo pacman -Syy
```
