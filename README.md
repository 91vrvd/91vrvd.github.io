# Liu OS · 公开静态版源码（GitHub Pages）

这是 Liu OS 的**公开静态版源码**，对应 [91vrvd.github.io](https://91vrvd.github.io/)。它不是当前功能最全的主站源码。完整版网站在 [Liu OS 主站](https://liu-os-7obu.qq1279622658.chatgpt.site/desktop/)，其源码保存在私有仓库 [7obu（仅仓库所有者可访问）](https://github.com/91vrvd/7obu/tree/sites-source)。

| 要找什么 | 打开哪里 | 说明 |
| --- | --- | --- |
| 当前完整版网站 | [Liu OS 主站](https://liu-os-7obu.qq1279622658.chatgpt.site/desktop/) | 网站可公开访问；“私有”指源码仓库，不是网站访问权限 |
| 当前完整版源码 | [私有仓库 7obu · sites-source](https://github.com/91vrvd/7obu/tree/sites-source) | 仅有仓库权限的账号可以查看，包含完整版前端和服务端源码 |
| 公开静态版网站与源码 | [91vrvd.github.io](https://91vrvd.github.io/) · [本仓库](https://github.com/91vrvd/91vrvd.github.io) | 这是独立的 GitHub Pages 版本，不包含完整版全部功能 |
| 旧版历史源码 | [7obu · master](https://github.com/91vrvd/7obu/tree/master) | 历史备份，不是当前主站的更新入口 |

**English:** This public repository contains only the GitHub Pages edition of Liu OS, not the full source. The current full website is [Liu OS](https://liu-os-7obu.qq1279622658.chatgpt.site/desktop/); its source is in a private repository.

[打开 GitHub Pages 版](https://91vrvd.github.io/) · [编辑网站内容](https://github.com/91vrvd/91vrvd.github.io/edit/main/content/site.json) · [发布进度](https://github.com/91vrvd/91vrvd.github.io/actions)

## 项目目录

| 项目 | 说明 | 在线查看 |
| --- | --- | --- |
| [Liu OS 主站](https://liu-os-7obu.qq1279622658.chatgpt.site/desktop/) | 目前在用的个人网站；源码暂未公开 | [打开](https://liu-os-7obu.qq1279622658.chatgpt.site/desktop/) |
| [给生活的答案](https://github.com/91vrvd/answers-for-life) | 本地保存答案的互动问答册 | [打开](https://91vrvd.github.io/answers-for-life/) |
| [空气吉他](https://github.com/91vrvd/vibe-air-guitar) | 用摄像头手势切换和弦 | [打开](https://91vrvd.github.io/vibe-air-guitar/) |
| [U 卡对比百科](https://github.com/91vrvd/ucards-compare) | 对比加密货币消费卡的费用和申请条件 | [打开](https://91vrvd.github.io/ucards-compare/) |
| [加密入门教程](https://github.com/91vrvd/crypto-tutorial-site) | 给新手看的单页教程 | [打开](https://91vrvd.github.io/crypto-tutorial-site/) |
| [新电脑配置助手](https://github.com/91vrvd/ai-setup-hub) | 新电脑安装常用工具的步骤和离线包 | [打开](https://ai-setup-hub-91vrvd.qq1279622658.chatgpt.site/) |
| [企业知识库页面](https://github.com/91vrvd/Add-Enterprise-Knowledge-Base) | 使用示例数据的静态界面 | [查看代码](https://github.com/91vrvd/Add-Enterprise-Knowledge-Base) |

## 更新网站内容

1. 用拥有此仓库写入权限的 GitHub 账号（91vrvd）登录，打开上方的“编辑网站内容”。
2. 在 `content/site.json` 中查找要修改的文字。`zh` 是中文，`en` 是英文。只改文字时，请保留两侧引号、逗号和括号。字符串中的换行写成 `\n`，双引号写成 `\"`。
3. 点击 **Commit changes**，将修改提交到 **main**。GitHub Pages 会自动发布，无需重新编译网页。
4. 在“发布进度”中等本次部署成功，再刷新网站。浏览器中的网站也会定期读取最新内容。

| 字段 | 网站里的内容 |
| --- | --- |
| `profile` | 个人介绍、目前在做的事、社交链接 |
| `projects` | 项目介绍、截图、在线体验链接 |
| `experiences` | 工作与项目经历 |
| `skillGroups` | 技能分组、使用场景、熟悉程度 |
| `safariBookmarks` | Safari 书签 |
| `mediaTracks` | 音乐列表 |
| `desktopShortcuts` | 桌面快捷方式 |

技能的 `level` 使用 `regular`（日常使用）、`working`（实践中）或 `learning`（学习中）。保留 `schemaVersion: 2`。图片可上传到仓库的 `images` 文件夹，然后填写 `/images/文件名.png`。

这里的文件和网站内容都是公开的。不要写入密码、Token、API key 或私人资料。网站登录入口只会带你前往 GitHub 官网，不会在网站里保存 GitHub 登录状态。

## 如果修改后没显示

先查看发布进度，确认 main 分支的最新部署已成功，再刷新网站。如果 JSON 格式或字段结构有误，网站会继续显示已加载的内容，或使用内置内容，不会把错误数据直接渲染出来。

在文件页面的 **History** 中可以找到旧版本，复制旧内容回编辑页，再提交一次即可恢复。不要编辑 `assets` 中的压缩脚本；它们是生成文件。

页面的小图标使用 [Wikimedia Commons 上的三星旧版标识](https://commons.wikimedia.org/wiki/File:Samsung_old_logo_before_year_2015.svg)。三星是 Samsung Electronics 的商标，本个人网站与三星没有关联。
