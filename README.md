# 吴钩骨科机器人 Skill

中文 | [English](README.en.md)

把吴钩产品资料安装到自己的 AI 助手，用于产品问答、销售介绍和医生产品培训内容整理，支持中文和英文。

## 安装

**用 Codex 安装：打开电脑上的 Codex，新建一个对话，把下面整段复制并发送。**

```text
$skill-installer 请从 https://github.com/simpledavid/wugou-robot-product 安装吴钩产品 Skill。
SKILL.md 在仓库根目录，安装名称为 wugou-robot-product。
```

**等助手确认安装完成，再发送第一次提问：**

```text
$wugou-robot-product 用一分钟给医生介绍吴钩。
```

如果安装后没有识别到技能，重启 Codex 再试。[Codex 官方安装说明](https://learn.chatgpt.com/docs/build-skills#install-curated-skills-for-local-use)

手机扫码打开的是本仓库的安装说明；可以把上面的指令复制或发送到电脑，再在 Codex 中完成安装和提问。

<details>
<summary>其他支持 Skill 的 AI 助手，或手动安装</summary>

如果你的 AI 助手支持从仓库下载并安装 Skill，可以发送：

```text
安装 https://github.com/simpledavid/wugou-robot-product
```

也可以[下载 ZIP](https://github.com/simpledavid/wugou-robot-product/archive/refs/heads/main.zip)，解压后将包含 `SKILL.md` 的完整文件夹，按所用平台的技能导入或安装方式添加。助手需要能读取包内 Markdown 和 PDF 资料。

不同软件的安装入口可能不同。普通聊天窗口只粘贴链接，不代表已经完成 Skill 安装。安装后可问：“用一分钟给医生介绍吴钩。”

</details>

[查看可提问内容](#这个-skill-能做什么) · [获取二维码](#宣传册二维码) · [查看原宣传册](assets/三折页411.pdf)

## 关于吴钩

**English description:** An AI skill for Wugou orthopaedic robot product questions, sales introductions and physician product training materials, based on bundled sources. Model and TKA, THA and UKA scope are checked separately.

| 项目 | 内容 |
| --- | --- |
| 公司 | 北京威高智慧科技有限公司 |
| 产品 | 吴钩；型号规格 WeiZ-01，见公司补充截图 |
| 公司提供的产品覆盖 | 全膝 TKA、全髋 THA、单髁 UKA；具体型号与各术式注册范围分别核对 |
| 服务人群 | 销售、临床支持、医生及客户 |
| 已接入资料 | 全膝宣传册、型号规格截图、公司产品信息、已核验公开来源 |
| 联系方式 | 宣传册载电话 (010) 6280-0509、邮箱 weiztechnology@weiz.cn |

详细资料与出处见 [产品问答索引](references/product-facts.md)。

## 这个 Skill 能做什么

| 能力 | 你可以问 |
| --- | --- |
| 产品介绍 | “吴钩是什么产品？”“用一分钟给医生介绍吴钩。” |
| 系统组成 | “系统有哪些主要部分？” |
| 产品特点 | “怎么规划？”“动态追踪有什么作用？” |
| 全膝流程概览 | “全膝手术的五步流程是什么？” |
| 参数解释 | “±0.5 mm 具体指什么？” |
| 术式咨询 | “全膝、全髋和单髁分别有哪些资料？” |
| 销售与医生产品培训 | “写一段 30 秒的销售介绍。”“整理医生 FAQ。” |
| 联系公司 | “怎么联系公司了解演示或培训？” |

当前可直接回答全膝的产品特点、主要组成、五步流程概览和已有参数出处。全髋、单髁的具体流程、性能参数与兼容性资料仍待补充。公司提供的三术式覆盖信息，不等于已经确认 WeiZ-01 或同一注册证覆盖三术式。

产品培训内容目前包括产品介绍、流程概览与 FAQ；完整操作培训需要对应版本正式说明书。

## 演示、培训与报修咨询

| 操作 | 说明 | 你可以说 |
| --- | --- | --- |
| 查询联系入口 | 提供宣传册中的电话、邮箱和地址 | “怎么联系临床支持？” |
| 整理咨询内容 | 按已提供信息整理咨询要点 | “帮我整理培训需求。” |
| 实际提交业务 | 当前没有已配置的预约、培训申请或报修工具 | “能直接申请培训吗？” |

使用流程：

1. 告诉 AI 助手你关心的产品问题或术式。
2. 助手查阅相应产品资料，必要时确认型号、版本或问题背景。
3. 需要服务时提供已有联系入口；接入真实业务工具后再按实际能力处理提交与状态查询。

## 运行环境

使用能够读取 Skill 和本地 Markdown、PDF 资料的 AI 助手。当前产品资料保存在安装包内。

这是一份供 AI 助手安装的技能与资料包，无需公司另行提供在线聊天或模型服务。

## 关于吴钩资料服务

| 项目 | 内容 |
| --- | --- |
| 当前事实来源 | 包内产品资料与已核验官方来源 |
| 原宣传册 | [三折页411.pdf](assets/三折页411.pdf) |
| 资料入口 | [产品上下文与目录](references/product-context.md) |
| 产品 API／MCP | 当前没有已配置接入点 |
| 业务执行接口 | 当前没有已配置的预约、培训申请或报修工具 |

## 发布平台

- GitHub：[simpledavid/wugou-robot-product](https://github.com/simpledavid/wugou-robot-product)
- 同时提供本地 Skill 文件夹与 ZIP 安装包。

## 宣传册二维码

<img src="assets/wugou-skill-qr.png" alt="吴钩产品 Skill 安装入口二维码" width="240">

[下载 PNG 图片](assets/wugou-skill-qr.png) · [下载 SVG 矢量图](assets/wugou-skill-qr.svg)

两个文件是同一二维码的不同格式，都指向本仓库。用户扫码查看安装说明，把安装链接复制给自己的 AI 助手，再完成安装。二维码本身不会自动安装 Skill。

宣传册配文建议：**扫码获取吴钩产品 Skill** / **Scan to get the Wugou Product Skill**。

印刷排版优先使用 SVG；保留白色边距、等比缩放，完成排版后用实际手机扫码检查。

## 版本

当前技能版本：**0.3.3**，以 [skill.json](skill.json) 为准。产品型号 WeiZ-01、软硬件版本与技能版本分别记录。

当前资料核对日期为 2026-10-03；宣传册没有标明正式版次。历史资料不代表当前注册或服务状态。

需要更新已安装的技能时，可以告诉助手：

> 请从 https://github.com/simpledavid/wugou-robot-product 更新吴钩产品 Skill。

仓库内容会持续按实际取得的资料维护。仓库更新后，已安装的本地副本仍需按所在平台规则更新；没有自动实时同步服务。

## 资料使用范围

资料按公司实际使用范围处理，详见 [产品上下文](references/product-context.md)。原宣传册保留在包内，具体产品要求以相应版本正式资料为准。
