# 第一章 测试

test git push

```
$ git push -u origin mainit push -u ogigin main
error: src refspec mainit does not match any
error: src refspec push does not match any
error: src refspec ogigin does not match any
```
这种情况一般两种情况导致：

1.分支不存在

使用checkout创建对应分支
```
git checkout -b master
```
2.没有使用git add和git commit将文件添加至缓存

```
git add .
git commit -m "更新说明"
```
3.没有README文件
```
touch README
```
添加完README文件后还需要重新git add . 和git commit
