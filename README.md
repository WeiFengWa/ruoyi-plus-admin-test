# RuoYi-Plus Admin（试岗项目）

基于 [RuoYi-Vue-Plus](https://gitee.com/dromara/RuoYi-Vue-Plus) 的多租户后台管理系统，本仓库用于研发试岗：本地部署、功能开发与 Bug 修复。

正式任务见：[任务清单.md](./任务清单.md)

---

## 仓库结构

| 目录 | 说明 |
|------|------|
| `RuoYi-Vue-Plus` | 后端（Spring Boot 3 / JDK 17） |
| `ruoyi-plus-soybean` | **试岗使用前端**（Vue3 + Naive UI + Vite） |
| `ruoyi-plus-vben5` | 备选前端（Vben5，本次可不看） |
| `plus-ui` | 备选前端（React，本次可不看） |

本次试岗只需关注：`RuoYi-Vue-Plus` + `ruoyi-plus-soybean`。

---

## 环境要求

- JDK 17+
- Maven 3.8+
- Node.js 20+
- pnpm 10+
- MySQL 8
- Redis 6+

---

## 重要说明

1. 开发时优先参考现有模块（用户管理、角色管理、通知公告等），避免重复造轮子

---

## 试岗相关

- 任务与验收标准：[任务清单.md](./任务清单.md)
- 官方文档：[RuoYi-Vue-Plus 文档](https://plus-doc.dromara.org)
- 前端参考：[ruoyi-plus-soybean](https://gitee.com/xlsea/ruoyi-plus-soybean)
- UI 组件：[Naive UI](https://www.naiveui.com/zh-CN/os-theme)

---

## 提交建议

完成任务后请准备：

1. 选择了哪些题目（阶段二 A/B，阶段三 C/D）
2. 功能截图
3. 已修复 Bug 的简要说明（现象 → 根因 → 改法）
4. 未完成项与卡住原因

祝顺利。
