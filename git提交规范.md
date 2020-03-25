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







### 3. 转测规范



#### 3.1【Requirement】 xxx系统转测 (如：用户中心转测)

```java
【提测原由】版本转测
【平台名称】CMS 系统
【版本号】CMS_V2R3D0325
【省份】全网推送
【更新war包】 
    backend.jar
    inject.jar
【更新说明】
    CMS二期新需求
    
【压测接口】
    无
【接口文档】
    无
【SVN目录】
    http://192.168.1.10:81/svn/yst_platform/Project_Archive/OCEAN/CMS/CMS_V2R3D0325
```

#### 3.2【Bugs】xx系统bug修复(如用户中心bug修复)

```java
【提测原由】缺陷修复

【平台名称】xxx系统

【版本号】版本号（如:用户中心 UC_V4.9.10.9）

【省份】全国

【更新war包】

​    yst-uic-facade.war

​    yst-uic-base.war

【更新说明】：

\1. 修复数据同步问题（JIRA单号）

\2. 修复XXXX问题（JIRA单号）

【压测接口】

​    1.xxxxx

【接口文档】

http://192.168.48.18:8080/ysten-api/

【SVN目录】

http://192.168.1.10:81/svn/yst_platform/Project_Archive/LBSS/07 安徽移动/02 BSS_S/ORD_AH_Vxxx/
```

#### 3.3【CR】xx系统需求变更(如用户中心需求变更)

```java


【提测原由】 需求变更

【平台名称】平台名称

【版本号】版本号（如:用户中心 UC_V4.9.10.9）

【省份】全国

【更新war包】

​    yst-uic-facade.war

​    yst-uic-base.war

【更新说明】：

 \1. 临时增加需求XXXX（JIRA单号）

\2. 功能又原来的XXX改为XXX（JIRA单号）

【压测接口】

​    1.xxxxx

【接口文档】

http://192.168.48.18:8080/ysten-api/

http://192.168.1.10:81/svn/yst_platform/Doc/LBSS/XXXX

【SVN目录】

http://192.168.1.10:81/svn/yst_platform/Project_Archive/LBSS/07 安徽移动/02 BSS_S/ORD_AH_Vxxx/
```



