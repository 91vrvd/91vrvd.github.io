# Liu OS

[打开网站](https://91vrvd.github.io/) · [编辑网站内容](https://github.com/91vrvd/91vrvd.github.io/edit/main/content/site.json) · [发布进度](https://github.com/91vrvd/91vrvd.github.io/actions)

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
