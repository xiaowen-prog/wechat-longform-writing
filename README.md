# 公众号长文写作 Skill

一份给 Claude 用的写作 skill，用来写公众号深度长文和行业观察稿，尤其适合 AI、AIGC、科技产品演进这类题材。

它是在一篇 AIGC 视频演进长文从大纲到定稿的过程中整理出来的。作者在改稿时提出的每一条意见，比如"不要虚构故事""这句像被鬼上身了""加个但是"，都整理成了规则。

## 它会做什么

- 先交大纲，确认以后再写全文
- 只用可查证的真实案例，不替作者编经历
- 第一人称、口语、平视的口吻，参考作者亲自改过的引子
- 每章按"生活体感、卡点、技术突破、市场变化"的因果链推进
- 重点检查段落衔接，删掉突然跳出来的旁白句，转折处补上"但是"
- 每章 3 到 4 个小标题，少量加粗
- 规划配图，示意图一张只讲一件事
- 交付 Markdown，配图位置单独标记
- 最后做一遍标点检查

## 安装

把 `wechat-longform-writing` 文件夹完整复制到你的 Skills 目录，比如：

```text
~/.claude/skills/wechat-longform-writing/
```

在 claude.ai 上，可以在设置里上传这个文件夹作为自定义 skill。

建议同时安装 [human-writing（活人感写作）](https://github.com/KKKKhazix/human-writing)，本 skill 在它的基础上补充了作者本人的偏好。

## 目录

```text
wechat-longform-writing/
├── SKILL.md                     主规则
└── references/
    ├── voice-sample.md          口吻样板
    └── revision-log.md          改稿意见记录
```

## 许可

MIT
