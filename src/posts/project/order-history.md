---
title: 实现过的功能（三）：购买历史
date: 2017-12-21
tags: 功能,前端,JavaScript
description: 购买历史
sort: 5
---

后端查询对应用户在对应店铺购买的最后十份（这个随意）商品，前端展示出来，方便用户再次购买。

## 仅获取商品标识

后端查询的信息只是单纯的包含了，需要的商品标识。具体的商品信息需要对比查询到的店铺商品。

## 对比店铺商品

原因是，不知道用户购买过的商品是否还存在，或者下架。