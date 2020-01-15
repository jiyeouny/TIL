# How to Start git

## Git configuration

```shell
$ git config --global user.name "username"
$ git config --global user.email "user email addr"
$ git config --global core.editor "vim"
$ git config --global core.pager "user email cat"
```
## `git init`으로 프로젝트 시작하기

```shell
$ git remote add origin https://github.com/"username"/"repository name".git
$ git get-remote url origin
$ touch README.md
$ vi README.md -> i -> esc -> :wq/ :q!/ :w
$ git status
$ git add README.md
$ git status
$ git push origin master
```

## `git clone`으로 프로젝트 시작하기

```shell
$ get clone "paste url"
$ touch README.md
$ git commit -m "commit message"
$ git status
$ git add README.md
$ git status
$ git push origin master

```

## 우리가 마크다운을 쓰는 이유

`<h1></h1>` ->`#`



