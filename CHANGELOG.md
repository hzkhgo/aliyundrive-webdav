# Changelog

All notable changes to this project will be documented in this file.

## 0.5.1

* 修复 OpenWrt Luci 界面语言翻译问题

## 0.5.0

* 增加实验性[阿里云相册与网盘服务（PDS）](https://www.aliyun.com/product/storage/pds)支持，阿里云网站开通 PDS 服务后可通过传入 `domain_id` 和对应用户的 `refresh_token`（可通过访问 BasicUI 获取） 使用企业。

## 0.4.8

* 支持通过环境变量 `HOST` 和 `PORT` 配置监听地址和端口

## 0.4.7

* 发布 musllinux wheel 二进制包至 PyPI

## 0.4.6

* 自动尝试刷新过期的上传地址
* GitHub Release 产物文件名增加版本号

## 0.4.5

* 兼容 macOS Finder chunked encoding 上传 `X-Expected-Entity-Length` HTTP header

## 0.4.4

* 新增目录缓存过期时间参数配置
