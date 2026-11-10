# 捞鱼视频创作台 · 免费资源目录

桌面应用的「Skill 商城」读取 `catalog.json`。资源需要由使用者手动下载。

## 投稿

1. 将自己有权分发的 Skill ZIP 或 BGM 标签 JSONL 放在公开 GitHub Release，或使用可直接读取的 GitHub Raw 文件。
2. Fork 此仓库，将应用导出的资源条目加入 `catalog.json` 的 `entries` 数组。保持 ID 唯一并填写文件 SHA-256。Skill ZIP 应带 `SKILL.md`；BGM JSONL 每行一条，支持 `id`、`file` 或 `title`、`kind`、`duration`、`tags` 和 `note`。
3. 提交 PR，写明原创或分发授权、内容范围及测试。维护者合并后，应用「刷新社区」即可看见条目。只接受免费资源。

曲库只发布标签和用法资料。原备注描述的是剪辑判断，音频使用权以音源授权为准。提交前检查个人信息、目录、令牌及私有项目内容。Skill 包下载后可先审阅，再自行交给 Agent。

## BGM 内化示例

[下载示例 JSON](assets/laoyu-bgm-graph-example.json)。在一个空图谱中下载并加入「捞鱼的 BGM 打标库」，再导入这个 JSON。示例覆盖深夜潜入、功能揭示、片尾慎用、动作速度切换等 11 条规则。每条都引用原标签或备注。若图谱已有其它曲库，按当前图谱重新导出并让 Agent 内化。
