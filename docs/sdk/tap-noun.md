---
id: tap-noun
title: TapSDK 名词解释
sidebar_label: 名词解释
---

## client_id
是一个游戏实体包在 TapTap 开发者中心的唯一身份标识，TapTap 通过 client_id 来鉴别游戏包的身份  
client_id获取位置如[图示](http://qnblog.ijemy.com/tap_clientid.png)  
## token
每次登录后，都会在[LoginSuccess](/sdk/tap-unity#8-注册回调)回调里面返回token及相关信息，token是用户本次授权的唯一标识。  
每次登录返回token会不一样，logout后自动清理

## 玩家
对应一个玩家账户，需要一个唯一的标识符。玩家是统计系统的数据统计基本单位
## 设备
安装了对应游戏的设备
## 付费
玩家使用真实货币换取游戏虚拟币或游戏道具
## 分包渠道
标识游戏安装包渠道来源，需要在代码中设置

## app id
游戏在 TapTap 商店的唯一身份标识  
例如：https://www.taptap.com/app/187168 ，其中"187168"是 app id

## tap user id
taptap主站的数字id，用户在 TapTap 社区的唯一身份标识（开发者不可获取，需用户主动提供）  
tap user id获取位置如[图示](http://qnblog.ijemy.com/tap_tapid.png)