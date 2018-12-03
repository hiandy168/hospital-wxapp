# 微信小程序-前端 [开发版]
> `文档更新： 2018-12-2`
> `体验版本： v0.5.9 [Alpha]`
### 内部原创组件说明
>`Toast` 组件: [查看 说明/源码](https://gitee.com/slm47888/wechat_applet__component_toast)
### 进度浏览：
`删除线代表未完成`
>##### `页面/布局:`
>>- 首页
>>- 我的账号
>>- 绑定小程序
>>- 注册账号[用户]
>>- 注册账号[医生]
>>- 科室搜索
>>- 我的家庭
>>- 短信验证
>>- ~~身份证上传~~
>>- ~~短信验证[注册页]~~
>>- ~~我的药店~~
>>- ~~医生信息页~~
>>- ~~发消息页面~~
>>- ~~我的药店~~
>##### `搜索机制:`
>>- 子部门搜索
>>- 姓名搜索
>>- 筛选搜索 
>>- 搜索节流
>>- 搜索绑定
>>- ~~专家搜索~~
>>- ~~快速搜索~~
>##### `账号机制:`
>>- openId登录
>>- openId注册
>>- openId绑定 
>>- ~~主账号注册[医生]~~ 90% _接口出现问题_
>>- ~~主账号注册[用户]~~ 90% _接口出现问题_
>>- ~~身份证识别~~

### 本地存储调用说明：
##### `主要起到提高体验度、减轻服务器压力`
| 数据 | 调用页 | 函数名 | 存储条件 | 有效时间 |
| :--------| :-------- | :-------- | :--------| :------: |
| 用户数据[账号/token/主账号] | account | settingAccount | 无数据/数据过期 | 3天 |
| 部门信息[主部门/子部门/科室] | app | onLaunch | 无数据/数据过期 | 1小时 |
