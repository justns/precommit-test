# precommit-test
git提交代码注释规范测试

# 栗子
git commit的消息这样组成：
其中header是必须有的，body，footer可选。
`header 
--空一行
body
--空一行
footer`

## header的规则
Commit message格式，注意冒号后面有空格
<type>: <subject>
type
用于说明 commit 的类别，只允许使用下面7个标识，也可以自己在配置文件中更改或者扩展。
标准类型如下：
feat：新功能（feature）
fix：修补bug
docs：文档（documentation）
style： 格式方面的优化
refactor：重构
test：测试
chore：构建过程或辅助工具的变动

subject
subject是 commit 的简短描述，不能超过50个字符，且结尾不加英文句号。

example：git commit -m 'docs: 补充readme文档说明git代码注释规范操作'

## 包含全部的栗子
example：git commit -m 'docs: 补充readme文档说明git代码注释规范操作

这是注释body

这是注释footer'