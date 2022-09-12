# github-ci-first

通过`github actions`,自动将`python`代码, 打包`windows` 或 `linux`可执行文件

## 常用命令

测试`github ci`的时候用

``` bash
git tag -d v1
git push origin :refs/tags/v1

git add .
git commit --amend --no-edit
git push origin main -f

git tag v1
git push origin v1


```