# XHS-XP1｜小红书美妆AI多角色正式生产工作流

这是一个“多个GPT聊天 + 人工复制交接”的正式生产系统。

底层规则和16个角色来自新版审核体系，不使用旧 xiaohongshu2 的角色或旧运行状态。

## 当前状态
- runtime_enabled = true
- runtime_mode = LIVE
- state = READY
- phase = INTAKE
- active_task_path = null
- publish_authority = USER_ONLY

## 使用方法
1. 打开 `角色/00_角色建立与初始化说明.md`
2. 在GPT新项目里一次性建立16个独立角色聊天
3. 每个聊天粘贴对应 `角色/01-16` 文件
4. 从【R01 运营总监AI】开始
5. 只按R01和各角色的正式交接复制
6. 系统一路完成账号初始化、研究、商品/SKU、策划、文案、视觉、图片、三审、合规、CONTENT LOCK和发布包
7. 真实发布由用户本人完成

## 首次启动
由于当前ACCOUNT_STRATEGY / VOICE / PERSONA尚未建立，R01会先按状态机完成这些初始化，再进入首篇真实CONTENT。

## 正式入口
- `项目匹配.json`
- `数据库入口.json`
- `当前进度.json`
- `生产/数据库入口.json`
- `生产/当前进度.json`
- `启动说明.md`
- `角色工作流.md`

GitHub XP1 是跨角色唯一正式真源。
