---
title: "人机验证2.0"
---

# 人机验证

自从雷池社区版发布以来，我们一直密切关注用户对于爬虫和扫描器的反馈和防护需求。 因此，在 2.0 版本中，我们致力于探索与此相关的功能，以满足用户的期望和保护网站的安全。

![challenge.png](/images/docs/challenge.png)

### 加入人机验证之后的请求处理流程

![flow.png](/images/docs/flow.svg)

### 人机验证如何配置

首先，点击位于左边栏的人机验证。之后，点击 **添加人机验证**。
![add_challenge.png](/images/docs/add_challenge.png)
在这里我们可以配置是否开启交互式校验以及规则的名称以及规则的触发条件。

### 人机验证触发规则

1. 规则内的条件之间是并且的关系，即需要全部命中，才会触发
2. 规则与规则之间是或的关系，则有一个命中，便会触发

### 交互与非交互的区别

如果选择开启交互，那么用户需要点击页面中间的勾选框开始验证，如果选择非交互，那么将自动开始验证。
![manual.png](/images/docs/manual.png)
