# 捞鱼视频创作台 · 免费资源目录

桌面应用的「Skill 商城」读取 `catalog.json`。资源需要由使用者手动下载。

## 投稿

1. 将自己有权分发的 Skill ZIP 或 BGM 标签 JSONL 放在公开 GitHub Release，或使用可直接读取的 GitHub Raw 文件。
2. Fork 此仓库，将应用导出的资源条目加入 `catalog.json` 的 `entries` 数组。保持 ID 唯一并填写文件 SHA-256。Skill ZIP 应带 `SKILL.md`；BGM JSONL 每行一条，支持 `id`、`file` 或 `title`、`kind`、`duration`、`tags` 和 `note`。
3. 提交 PR，写明原创或分发授权、内容范围及测试。维护者合并后，应用「刷新社区」即可看见条目。只接受免费资源。

曲库只发布标签和用法资料。原备注描述的是剪辑判断，音频使用权以音源授权为准。提交前检查个人信息、目录、令牌及私有项目内容。Skill 包下载后可先审阅，再自行交给 Agent。
