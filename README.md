# XHS-XP1｜小红书美妆AI多角色人工工作流

这是一个与旧项目使用方式相同的“多个GPT聊天 + 人工复制交接”工作流，但底层规则和16个角色来自新版 `xiaohongshuXT` 审核体系，不使用旧 `xiaohongshu2` 角色或旧运行状态。

## 当前阶段
16个角色已部署完成。

当前不是LIVE，而是：

`TEST_ONLY`

必须先完成：

`任务/CONTENT-TEST-001/V1/任务.json`

并建立：

`批准/CONTENT-TEST-001/PASS-V1.json`

之后才允许切LIVE。

## 你怎么用
1. 打开 `角色/00_角色建立与初始化说明.md`
2. 在GPT新项目里一次性建立16个独立角色聊天
3. 每个聊天粘贴对应 `角色/01-16` 文件
4. 从【R01 运营总监AI】开始
5. 按每个角色最后的正式交接复制到指定角色
6. 当前先跑CONTENT-TEST-001
7. 测试PASS后继续使用同一批16个聊天进入真实CONTENT，不需要重建角色

## 当前状态
`READY / INTAKE`

`runtime_enabled=false`

`runtime_mode=TEST_ONLY`

## 三证
1. SYS-003 MODULE LOCK：PASS
2. SYS-004 ROLE-INSTRUCTION-AUDIT-LOCK：PASS
3. CONTENT-TEST-001 PASS：未完成

只有三证齐全才能LIVE。
