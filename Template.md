# shao-deng/GKD

GKD 第三方订阅规则，由 [@shao-deng](https://github.com/shao-deng) 接管维护。

## 安全接管说明

- 本仓库基于 [AIsouler/GKD_subscription](https://github.com/AIsouler/GKD_subscription) 的历史规则延续维护。
- 保留了原有规则、快照、示例链接及历史 Issue 引用，便于追溯规则背景。
- 已移除定时发布、自动提交/推送、npm 发布和自动关闭 Issue 等会修改仓库或 Issue 的自动化。
- GitHub Actions 仅执行只读的类型检查、订阅校验、格式检查和 lint，权限为 `contents: read`。

## 订阅

复制下面的链接到 GKD：

```text
https://raw.githubusercontent.com/shao-deng/GKD/main/dist/shao-deng_gkd.json5
```

- 订阅 ID：`161324821`
- 作者：`shao-deng`
- 当前版本：v--VERSION--
- 已适配 886 个应用，共有 2076 个应用规则组和 3 个全局规则组
- [查看适配 APP 列表](./dist/README.md)
- [反馈问题](https://github.com/shao-deng/GKD/issues/new/choose)

> 更换了原订阅 ID，因此不会覆盖原作者的 ID `666`。已添加旧订阅的用户需要使用上述新链接重新添加。

## 使用与贡献

- 仅默认启用“开屏广告”类规则；其他规则请按需启用。
- 贡献规则前请阅读 [贡献指南](./CONTRIBUTING.md) 和 [GKD API 文档](https://gkd.li/api/)。
- 规则编写可参考 [通用规则及适用场景](./Selectors.md)。
- 历史不予适配情况见[原项目 Issue #480](https://github.com/AIsouler/GKD_subscription/issues/480)。

## 相关项目

- [GKD](https://github.com/gkd-kit/gkd)
- [GKD 订阅模板](https://github.com/gkd-kit/subscription-template)
- [GKD 文档](https://gkd.li/guide/)
- [gkd-kit/subscription](https://github.com/gkd-kit/subscription)

## 致谢

感谢 AIsouler 与所有历史贡献者建立并维护这些规则。接管后的修改不改变历史贡献的归属。

![Contributors](https://contrib.rocks/image?repo=AIsouler/GKD_subscription&_v=--VERSION--)
