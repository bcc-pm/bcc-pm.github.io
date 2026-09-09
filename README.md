# 白崇村 · 个人作品集站

> **AI 产品经理 · 企业级 AI Agent 平台构建** · 求职意向：广州（可深圳 / 杭州）

这里是托管在 GitHub Pages 的**个人作品集站源码仓库**。站点本身即简历的"证据链"——每个项目页用 STAR 结构展开"背景 → 角色 → 关键决策 → 成果 → 复盘"，重点呈现我在 0→1 平台搭建、商业化落地与质量成本治理中的真实产品决策。

👉 **直接访问作品集站**：<https://bcc-pm.github.io>

---

## 关于我

- **姓名**：白崇村（男 · 33 岁）
- **10 年产品经验，其中近 8 年 ToB**（2015 入行 → UI 设计师 → ToC PM → ToB PM/RPA → AI PM/Agent）
- **近 2 年深耕企业级 AI Agent 平台**：主导 APA（智能体流程自动化）平台 0→1，落地 9 大模块、服务数十家央国企
- **行业背书**：信通院《机器人流程自动化能力评估方法》行业标准参编专家
- **核心成果**：单次 Agent 任务 Token 成本精算到 **0.06–0.26 元**、AI 处理采纳率 **65% → 92%**、模型幻觉率 **≤5%**

---

## 仓库内容（站点文件结构）

```
bcc-pm.github.io/
├── README.md            ← 你正在看的文件
├── index.html           ← 作品集站首页（Hero / 关于 / 能力 / 项目 / 经历 / 资质 / 联系）
├── style.css            ← 全站共享样式表（indigo 主题、响应式、滚动入场动画）
├── apa-agent-platform.html        ← 项目 01：APA 智能体流程自动化平台
├── k2v-delivery-platform.html     ← 项目 02：K2V 智能咨询交付平台
├── finance-ai-agent.html          ← 项目 03：财务 AI 智能体（6 款 LLM + 4 款 OCR 评测）
└── manufacturing-ai-agent.html    ← 项目 04：制造业 AI 智能体（东方电气 / TCL 华星光电）
```

### 站点访问方式

- **线上预览**：<https://bcc-pm.github.io> （GitHub Pages 已自动部署）
- **本地预览**：下载本仓库后直接双击 `index.html` 即可（无需任何构建工具）

### 维护说明

- 修改任意 HTML 后，**必须连同 `style.css` 一起提交**，否则页面会失去样式（样式表为外部引用）
- 新增项目页：在 `index.html` 的 `Projects` 区块复制一份 `.proj-card` 卡片，并在本仓库追加对应 `.html` 即可

---

## 相关项目仓库

| 项目             | 仓库链接                                                                              | 主题                                    |
| -------------- | --------------------------------------------------------------------------------- | ------------------------------------- |
| APA 智能体流程自动化平台 | [bcc-pm/apa-agent-platform](https://github.com/bcc-pm/apa-agent-platform)         | RPA → Agent 架构升级 · 三层解耦 · IBO/VBO 原子化 |
| K2V 智能咨询交付平台   | [bcc-pm/k2v-delivery-platform](https://github.com/bcc-pm/k2v-delivery-platform)   | 多引擎协作 Agent · 七层 PromptOps · 8 周 MVP  |
| 财务 AI 智能体      | [bcc-pm/finance-ai-agent](https://github.com/bcc-pm/finance-ai-agent)             | 6 款 LLM + 4 款 OCR 选型评测 · 报销自动化        |
| 制造业 AI 智能体     | [bcc-pm/manufacturing-ai-agent](https://github.com/bcc-pm/manufacturing-ai-agent) | 工业 RPA + 智能问答 · 12 万+ 订单              |

> 每个项目仓库都包含一份 `README.md`，按 STAR 结构详细展开项目背景、关键决策、量化成果与复盘。

---

## 技术栈

- **HTML5** + **CSS3**（CSS 变量、Grid/Flex 布局、IntersectionObserver 滚动入场动画）
- **原生 JavaScript**（仅用于移动端汉堡菜单切换与平滑滚动）
- **零依赖、零构建**：不引入任何前端框架与打包工具
- **字体**：系统字体栈 + 中文 fallback（不依赖 Google Fonts，国内访问无压力）

> 选型理由：作品集站重在内容可读性与长期可维护性，避免引入会被版本淘汰的前端框架。所有设计 token（颜色、间距、字号）集中在 `style.css` 的 `:root` 中管理，改色改风格只需改一处。

---

## 联系我

- **手机 / 微信**：15690713579
- **邮箱**：<bcc48625@163.com>
- **GitHub**：[github.com/bcc-pm](https://github.com/bcc-pm)
- **意向城市**：广州（可考虑深圳 / 杭州）

如果你是 HR / 面试官，欢迎邮件沟通面试安排；如果是同行，欢迎在 Issues / Discussions 里交流产品看法。

---

## 内容脱敏说明

- 客户名称保留作为公开背书（中海油、国家电网、TCL华星光电、东方电气、建信金科等）
- 合同金额、Prompt 原文、内部业务流流程图等均经过改写或抽象化处理
- 作品集所有量化数据与简历保持口径一致，但展示口径优先服务于"读懂我做了什么"

## License

MIT — 欢迎参考本仓库的版式与结构，但请勿直接复制内容用作你自己的作品集。
