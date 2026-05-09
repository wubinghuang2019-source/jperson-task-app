# J-Order · 秩序

**AI 人生秩序管理系统** - 专为 MBTI J 型人格设计

---

## 产品定位

这不是普通待办清单 APP。

> "帮助 J 型人格恢复秩序感、掌控感、人生推进感的 AI 生活系统。"

用户核心情绪：
- 害怕失控、害怕任务堆积
- 喜欢规划、喜欢明确进度
- 会因为完成计划获得满足感

**核心不是效率，而是让用户感觉人生重新进入掌控。**

---

## 核心功能（MVP v2）

### 1. AI 语音输入脑内 dump
- 按住说话或文字输入
- AI 自动提取任务、分类、识别时间、判断优先级
- 标记拖延事项，生成执行顺序

### 2. J 人秩序恢复系统
- 秩序值动态显示（高度有序 / 恢复中 / 需要关注）
- 人格化文案："你的事项已经重新归位"
- 完成率驱动的状态变化

### 3. 任务完成爽感系统
- 完成任务时弹出庆祝弹窗
- 秩序值 +10 动态反馈
- 随机鼓励文案

### 4. J 人专属 UI
- 极简、克制、高级、冷静、秩序感
- 参考：Things3 / Linear / Apple Reminders
- 避免花哨、二次元、可爱风

---

## 技术栈

- **前端**: 原生 HTML5 + CSS3 + Vanilla JS
- **数据**: localStorage（MVP 阶段）
- **AI**: 本地解析 + DashScope API（可选）
- **语音**: Web Speech API
- **部署**: Vercel 静态托管

---

## 页面结构

1. **首页 · 今日秩序** - 秩序值卡片 + 今日任务列表
2. **AI整理** - 语音/文字输入，脑内 dump
3. **整理结果** - AI 提取结果确认
4. **任务详情** - 任务信息 + 备注
5. **本周进度** - 连续天数 + 每日完成图表

---

## 快速开始

```bash
cd "J 人任务 App"
python3 -m http.server 8080
```

访问 http://localhost:8080

---

## 部署

推送到 GitHub → Vercel 自动部署

- GitHub: https://github.com/wubinghuang2019-source/jperson-task-app
- Vercel: https://jperson-task-app.vercel.app

---

## 后续扩展

- [ ] Supabase 后端 + 用户系统
- [ ] DashScope API 真实 AI 解析
- [ ] 推送通知 / 智能提醒
- [ ] 数据同步（多设备）
- [ ] 原生 iOS App（SwiftUI）

---

**项目状态**: MVP v2 开发中  
**最后更新**: 2026-05-09
