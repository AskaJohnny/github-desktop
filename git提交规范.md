# [git提交规范](http://wiki.ysten.com:8080/pages/viewpage.action?pageId=52927571)





### 1.提交模板

##### type: 

##### jira:

##### source-jira: 

##### subject:



type（必须） : commit 的类别，只允许使用下面几个标识：

- feat : 新功能
- fix : 修复bug
- conflict： 修复冲突
- docs : 文档改变
- style : 代码格式改变
- refactor : 某个已有功能重构
- perf : 性能优化
- test : 增加测试
- build : 改变了build工具 如 grunt换成了 npm
- revert : 撤销上一次的 commit
- chore : 构建过程或辅助工具的变动

jira（非必须）：jira号，一般以PRD开头【若无对应jira，可填none】

source-jira（非必须）：当type为fix类型时，如果修复的问题由一个feature所导致，需要将对应feature的jira号填写在这里【若无对应jira，可填none】

subject：提交描述，50字以内





### 2.Idea 插件(git 提交信息)

下载插件Commit Message Template

