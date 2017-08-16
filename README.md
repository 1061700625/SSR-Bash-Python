# SSR多用户管理脚本（基于官方mujson版本）
[![Build Status](https://travis-ci.org/Readour/AR-B-P-B.svg?branch=master)](https://travis-ci.org/Readour/AR-B-P-B)
## 介绍 ##

一个Shell脚本，集成SSR多用户管理，流量限制，加密更改等基本操作。是一个基于ShadowsocksR官方的mujson的辅助脚本。方便用户操作，并且支持快速构建SSR服务环境。

- 请谨慎使用，出问题概不负责！！！！
- 如果发现脚本bug，请及时发issues，非常感谢

## 系统支持 ##
* Ubuntu 14
* Ubuntu 16
* Debian 7
* Debian 8
* CentOS 6
* CentOS 7

## 功能 ##
- 全自动无人值守安装，服务端部署只需一条命令，您和SSR都是如此的优雅：）
- 一键开启、关闭SSR服务
- 添加、删除、修改用户端口、密码和连接数限制
- 支持傻瓜式用户添加,小白也可以用
- 自由限制用户端口流量使用及端口网速
- 自动修改防火墙规则
- 自助修改SSR加密方式、协议、混淆等参数
- 自动统计，方便查询每个用户端口的流量使用情况
- 自动安装Libsodium库以支持Chacha20等加密方式
- 支持一键构建ss-panel（有风险，仅开发版可用）
- 傻瓜式的BBR一键构建（仅Debian/Ubuntu支持，有风险，仅开发版可用）

## 缺点 ##
- 未设置开机启动

## 安装或更新到最新开发版(支持新特性，不推荐小白使用) ##
    wget -N --no-check-certificate https://raw.githubusercontent.com/Readour/AR-B-P-B/master/install.sh && bash install.sh develop

## 安装&更新 ##
    wget -N --no-check-certificate https://raw.githubusercontent.com/Readour/AR-B-P-B/master/install.sh && bash install.sh

## 自检（没有卵用😝） ##
    wget -N --no-check-certificate https://raw.githubusercontent.com/Readour/AR-B-P-B/master/self-check.sh && bash self-check.sh
