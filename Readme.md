# 基于车牌识别的车辆进出管理系统

车牌识别采用的 `Hyper LPR` ，自定义训练集~

管理系统采用 `python && Django` 来进行开发~

目前已完成 `v1.0`，正在开发`v2.0`.

`v1.0` 基本功能已经实现~
- 车辆管理
- 收费管理
- 信息查询
- 用户管理
- 操作日志
- 收费标准设置
- 图像识别

`v1.0` 目录描述：
- doc ： 放置一些文档，供开发人员参考。
- sql ： MySQL数据库文件，创建好数据库，导入即可
- car ： 自定义app，主要功能代码
- handler ： 主要用来实现操作日志
- hdcarsystem ： 项目的基本配置文件
- static ： 静态文件
- templates ： 模板文件
- ennv ： 项目运行所以来的环境
- requirements.txt ： 项目运行所需要的依赖包

`v2.0` 主要对 `v1.0` 进行优化，主要从以下几个方面进行:
- 代码执行效率
- 代码健壮性
- 界面美观性，增强用户体验
- 系统安全性

`v2.0` 目录描述：


后期项目会放在服务器上进行测试~，如果比较喜欢，自行Fork and Star.

`v2.0` 着手准备开发，前端采用 `Vue+Vuex+Vue-router` 开发，管理系统后台准备采用 `SpringBoot + MyBatis + Shiro + Redis` 开发，数据库采用 `MySQL` 开发，预计7月末开发完毕，如有需要请关注

如有问题可以联系我

```
Email:zhangzhibo1014@163.com
Wechat:zzbwoaini1014
QQ:553340463
```