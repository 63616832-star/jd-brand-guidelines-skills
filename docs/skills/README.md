# 京东品牌规范 Skills 使用总览

这份目录用于给同事说明当前哪些 Skill 可以稳定使用，哪些还在打磨中，以及哪些只是历史归档。

## 推荐安装

稳定可发版本只需要安装两个 Skill：

```text
jd-agency-workflow
jd-copywriting-guidelines
```

- `jd-agency-workflow`：流程总控。负责 brief intake、规则路由、合规门禁、生动表达层和 QA。
- `jd-copywriting-guidelines`：京东 16.0 文案规范。负责 UX 文案、品牌营销文案、低价/权益/服务表达、商品卖点和风险门禁。

这两个组合已经可以覆盖京东文案、营销会场文案、运营位文案、小红书封面化表达、基础电商合规自检。

## 可选 WIP 扩展

以下 Skill 还在优化中，不建议作为稳定包默认发给同事：

```text
jd-joy-ip-guidelines
jd-app-store-marketing-guidelines
jd-startup-icon-guidelines
```

如果要测试视觉规范，可以单独安装，但需要在输出里标注“基于 WIP 规则，结论需复核”。

## 不要安装旧版归档

不要安装：

```text
jd-copy-guidelines/_archive/monolith-20260616
```

这个目录是旧版大一统 Skill 的历史归档，包含文案、JOY、App 商店图、启动图标等规则。现在这些能力已经拆成多个独立 Skill。继续安装旧版 monolith 会导致触发范围过大、规则重复和判断混乱。

## 推荐使用方式

### 做京东营销文案

```text
使用 $jd-agency-workflow 写一组京东 618 会场头图文案。

触点：会场头图
核心利益点：百亿补贴、券后价
要求：文案更生动，但不要夸大价格和优惠
```

### 做小红书封面化表达

```text
使用 $jd-agency-workflow 写一个小红书爆款封面文案。

产品：京东AI购 APP
场景：春节推广
要求：有点击感，但保持京东可信、克制
```

### 单独处理京东文案

```text
使用 $jd-copywriting-guidelines 优化这个报错提示：

触点类型：UX 交互文案 / 报错提示
场景判断：用户搜索订单但没有找到相关结果
原文：您还没有相关订单
```

## 分发清单

给同事发稳定包时，建议只包含：

```text
jd-agency-workflow/
jd-copywriting-guidelines/
docs/skills/
```

如果同事需要视觉规范测试，再按需补充 WIP 扩展。

