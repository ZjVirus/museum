


# 发布博物馆系统(1.0) 需要修改的页面 如下：

> 登录页面修改
## 图片地址
##  国博隐藏验证码  、 用户名和密码 默认 admin
## 国博、南博、深博  二维码显示, 其他隐藏

> home 页面
## 博物馆的logo（css前几行就是）
## 国博、南博、深博  二维码显示, 其他隐藏

> 数据分析页面
## 国博显示 选择参考设备按钮。其他隐藏

> 概览页面
## 博物馆有官网的，就显示，没有官网的 HTML 第九行隐藏

## 国博、南博、深博 （quanguanInfo 设为 true）, 其他 false

> index.html 
## 修改 对应的 title

> routes.js  (路由修改)
> 隐藏页面如下

## 陇西县博物馆：
# 空调调控、备忘录、热量场、展陈文物、隐藏仪器、上传文物图片和信息（数据分析页面：选择参考设备 按钮隐藏）

## 深博
# 历史数据、预警统计（两个）、热量场、展陈文物、上传文物信息和图片

## 国博
# 空调调控、热量场、预警统计（两个）、展陈文物、、上传文物信息和图片