# GitHub UI 相关 Skill 清单（按分类 · 按 Star 排序）

> 数据来源：GitHub REST API（`gh api`），抓取时间 **2026-10-12**。
> "Skill" 指以 `SKILL.md` / Agent Skill 形态分发的仓库；每类末尾另附「配套资源」，列出该场景下常用的组件库 / 脚手架（非 Skill 形态，仅作搭配参考）。
> Star 为仓库级总数（不是单个技能文件的安装量），会持续变动。

---

## 0. 跨端通用设计底座（官网 / H5 / 小程序 / 后台 / App 都能用）

| # | 仓库 | Star | 最近更新 | 说明 |
|---|------|------|----------|------|
| 1 | [anthropics/skills](https://github.com/anthropics/skills) | 180,655 | 2026-10-09 | Anthropic 官方 Agent Skills 仓。含 `frontend-design`：先定审美方向、排版与信息层级，避免"默认 AI 站"观感，是绝大多数 UI Skill 的基座  |
| 2 | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | 135,038 | 2026-10-12 | UI/UX 设计智能库：风格、配色、字体搭配、产品类型、UX 准则、图表类型，覆盖 22 种技术栈（React / Vue / Svelte / Astro / SwiftUI / RN / Flutter / Tailwind / shadcn 等） |
| 3 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 125,403 | 2026-10-12 | 组件库本体 + 官方 `shadcn` skill：增删组件、样式、组合、读取 `components.json` 上下文。Web 与中后台的事实标准底座 |
| 4 | [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | 105,328 | 2026-10-10 | 生产级交付导向：可访问性、质量门禁、上线前检查，偏"能上线的界面"而非好看的效果图 |
| 5 | [nexu-io/open-design](https://github.com/nexu-io/open-design) | 100,687 | 2026-10-12 | 开源版 Claude Design 替代：原型、落地页、管理后台、幻灯片、图片 / 视频，输出真实 HTML / PDF / PPTX / MP4 |
| 6 | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 94,966 | 2026-10-11 | 反 AI 味审美技能包：`minimalist-ui`、`industrial-brutalist-ui`、`high-end-visual-design`、`redesign-existing-projects` 等子技能 |
| 7 | [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 80,110 | 2026-10-12 | 界面诊断与打磨语言：UX 评审、视觉层级、信息架构、认知负荷、无障碍、响应式、动效、设计令牌 |
| 8 | [emilkowalski/skills](https://github.com/emilkowalski/skills) | 45,573 | 2026-10-11 | 设计师 / 工程师技能集：动效、交互质感、产品级界面细节打磨 |
| 9 | [wshobson/agents](https://github.com/wshobson/agents) | 40,453 | 2026-10-12 | 多宿主 agent / 插件市场，含大量前端与 UI 相关子代理与技能 |
| 10 | [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) | 35,558 | 2026-10-12 | 1000+ agent skills 精选索引，UI/设计分组是找库的重要入口 |
| 11 | [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | 32,274 | 2026-08-28 | Vercel 官方：React / Next.js 性能规则、Web Interface Guidelines 审查、组件组合模式 |
| 12 | [greensock/gsap-skills](https://github.com/greensock/gsap-skills) | 16,244 | 2026-07-29 | GSAP 官方动画技能：时间线、缓动、插件用法、滚动动效 |
| 13 | [ibelick/ui-skills](https://github.com/ibelick/ui-skills) | 9,633 | 2026-10-11 | 面向 Design Engineer 的 UI 技能集：交互细节与组件质感 |
| 14 | [jakubkrehel/skills](https://github.com/jakubkrehel/skills) | 7,832 | 2026-10-11 | 界面打磨合集：动效、无障碍、产品文案，串联成总审查流程 |
| 15 | [bergside/awesome-design-skills](https://github.com/bergside/awesome-design-skills) | 3,136 | 2026-06-28 | 67 份 `DESIGN.md` / `SKILL.md` 索引，含 dashboard、landing 等场景分类 |
| 16 | [bergside/design-md-chrome](https://github.com/bergside/design-md-chrome) | 2,990 | 2026-05-25 | 浏览器插件：从任意网站抽取样式并生成 `DESIGN.md` / `SKILL.md`，做设计基线复刻很实用 |
| 17 | [plugin87/ux-ui-agent-skills](https://github.com/plugin87/ux-ui-agent-skills) | 1,584 | 2026-10-10 | DTCG 设计令牌 + 52 组件 + WCAG 2.2 AA/AAA + 138 套设计系统 |

---

## 1. 官网 / 品牌站 / 落地页

| # | 仓库 | Star | 最近更新 | 说明 |
|---|------|------|----------|------|
| 1 | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) | 54,301 | 2026-10-08 | 营销技能集：CRO、文案、SEO、分析、增长工程；落地页转化结构这一块最对口 |
| 2 | [oso95/scroll-world](https://github.com/oso95/scroll-world) | 10,034 | 2026-07-29 | 把品牌做成可滚动"穿越世界"的 3D 官网 |
| 3 | [nexu-io/html-anything](https://github.com/nexu-io/html-anything) | 9,093 | 2026-09-15 | Agentic HTML 编辑器：75 skills × 9 输出形态（杂志 / 海报 / 原型 / 数据报告等），一键出 HTML / PNG，可直发微信、X、知乎 |
| 4 | [Affitor/affiliate-skills](https://github.com/Affitor/affiliate-skills) | 707 | 2026-09-15 | 50 个联盟营销技能：内容选题、落地页、转化素材 |
| 5 | [AIwithhassan/lets-scroll](https://github.com/AIwithhassan/lets-scroll) | 130 | 2026-08-15 | 滚动擦除式"飞越世界"落地页，AI 生成场景 + 相机运镜 |
| 6 | [musoyangrigor/scroll-video-website-skill](https://github.com/musoyangrigor/scroll-video-website-skill) | 55 | 2026-09-04 | 把视频转成滚动控制的 canvas 官网 |
| 7 | [braxtonROSE4/clone-any-website](https://github.com/braxtonROSE4/clone-any-website) | 54 | 2026-08-03 | 像素级复刻任意网站（改版时先取基线很好用） |
| 8 | [Carlos-Dominguez-faber/forja-landing](https://github.com/Carlos-Dominguez-faber/forja-landing) | 30 | 2026-04-17 | 电影级落地页：Seedance 视频素材 + 反 AI 味评审 |
| 9 | [tsogjavklann/awwwards-3d](https://github.com/tsogjavklann/awwwards-3d) | 26 | 2026-05-08 | Awwwards 风格滚动 3D 站（Three.js r170 + GSAP + Lenis） |
| 10 | [zyliu0/3d-frontend](https://github.com/zyliu0/3d-frontend) | 17 | 2026-03-03 | 滚动驱动的 3D 官网 |
| 11 | [YuanASI/landing-page-doctor](https://github.com/YuanASI/landing-page-doctor) | 13 | 2026-03-19 | 落地页首屏转化诊断，10 项打分 |
| 12 | [Zooeyii/ship-page-skill](https://github.com/Zooeyii/ship-page-skill) | 11 | 2026-03-08 | 零依赖、单 HTML 文件的交互式落地页 |
| 13 | [XIEXU0706/Web-Design-Skill](https://github.com/XIEXU0706/Web-Design-Skill) | 5 | 2026-08-28 | 高质感网页 / UI 核心 skill，横跨落地页、后台、详情页、H5 / 小程序 / App |
| 14 | [ChuluuMGL/business-website-skill](https://github.com/ChuluuMGL/business-website-skill) | 1 | 2026-07-10 | SEO/GEO 友好的企业 / 品牌 / B2B 官网与提案级站点 |

---

## 2. H5 / 移动端 Web

| # | 仓库 | Star | 最近更新 | 说明 |
|---|------|------|----------|------|
| 1 | [o2team/H5Skills](https://github.com/o2team/H5Skills) | 827 | 2017-07-11 | 移动端开发技巧集合（H5 兼容、适配、性能）。⚠️ 内容较老，作参考而非直接套用 |
| 2 | [undsky/doudou-ai-coding](https://github.com/undsky/doudou-ai-coding) | 208 | 2026-09-17 | 覆盖后端、Web 前端、移动端 H5、App、小程序的全栈 AI 编码技能，面向个人与中小企业 |
| 3 | [mobbin/skills](https://github.com/mobbin/skills) | 33 | 2026-10-12 | Mobbin 官方技能：用真实 App / H5 UI 库做检索式设计参考 |
| 4 | [enze00/uniapp-frontend-skills](https://github.com/enze00/uniapp-frontend-skills) | 17 | 2026-01-18 | uni-app 跨端前端（Vue 3 + TypeScript）综合技能 |
| 5 | [hxx2001/screenshot_to_code_agent-skill](https://github.com/hxx2001/screenshot_to_code_agent-skill) | 6 | 2026-09-14 | 网页 / 移动端 H5 截图还原为可编辑前端代码 |
| 6 | [SJSIAD/uni-app-expert](https://github.com/SJSIAD/uni-app-expert) | 2 | 2026-08-11 | uni-app 全端专家：多端兼容、包体积、性能、审核红线 |
| 7 | [caiqianha/vue-skills](https://github.com/caiqianha/vue-skills) | 1 | 2026-10-12 | Vue 3 + Element Plus 后台、微信小程序、uni-app 的技能包 |
| 8 | [linjiashu/luxury-hotel-ui](https://github.com/linjiashu/luxury-hotel-ui) | 1 | 2026-05-31 | 深色奢华风 C 端 UI，适用于微信小程序 / H5 移动端 |

**配套资源（非 Skill）**：[dcloudio/uni-app](https://github.com/dcloudio/uni-app) 41,615 · [MrXujiang/h5-Dooring](https://github.com/MrXujiang/h5-Dooring) 9,999（H5 低代码搭页）

---

## 3. 微信小程序

| # | 仓库 | Star | 最近更新 | 说明 |
|---|------|------|----------|------|
| 1 | [NocodeMrLi/mini-program-engineering-skill-suite](https://github.com/NocodeMrLi/mini-program-engineering-skill-suite) | 88 | 2026-10-11 | 证据优先的小程序工程技能套件：开发、调试、验收全链路 |
| 2 | [niuhuoshan/launch-wechat-miniprogram](https://github.com/niuhuoshan/launch-wechat-miniprogram) | 76 | 2026-08-11 | 新手向全流程：需求确认 → 原生 UI 与高保真原型 → AppID / 备案 / 测试 → 体验版 → 提审发布 |
| 3 | [TencentCloudBase/awesome-miniprogram-skills](https://github.com/TencentCloudBase/awesome-miniprogram-skills) | 44 | 2026-06-18 | 官方（腾讯云 CloudBase）示例集合：待办 → 数据存储 → 支付 → AI 调用，开箱即用 |
| 4 | [Sun-sunshine06/miniprogram-skills](https://github.com/Sun-sunshine06/miniprogram-skills) | 27 | 2026-07-20 | 可复用 Codex / Claude Code 技能：小程序开发、DevTools 诊断、脚手架 |
| 5 | [larkwins/wechat-miniprogram-skills](https://github.com/larkwins/wechat-miniprogram-skills) | 24 | 2026-03-31 | 小程序开发指导、性能优化与最佳实践技能包 |
| 6 | [beeyang0/miniprogram-VirtualPayment](https://github.com/beeyang0/miniprogram-VirtualPayment) | 22 | 2026-04-03 | 微信小程序虚拟支付接入技能（含审核要点） |
| 7 | [asdyych/wechat-miniprogram-skill](https://github.com/asdyych/wechat-miniprogram-skill) | 16 | 2026-02-14 | Claude Code 用的小程序开发技能 |
| 8 | [TencentCloudBase/mp-skills](https://github.com/TencentCloudBase/mp-skills) | 9 | 2026-06-22 | 官方 CLI（`npx mp-skills`）：快速创建 AI 小程序 / 把存量小程序改造成 AI 开发模式，内置评测校验 |
| 9 | [Gourdbaby/wechat-miniprogram-skill](https://github.com/Gourdbaby/wechat-miniprogram-skill) | 9 | 2026-01-23 | 原生 JS 小程序专家技能 |
| 10 | [Billzhouheart/wechat-miniprogram-designUI](https://github.com/Billzhouheart/wechat-miniprogram-designUI) | 6 | 2026-05-22 | 官方设计规范：颜色体系、暗黑模式、组件规范、审核红线、WeUI 标准 |
| 11 | [jojowang521/wechat-miniprogram-design-skill](https://github.com/jojowang521/wechat-miniprogram-design-skill) | 3 | 2026-08-27 | 设计规范技能：UI 组件、尺寸、安全区、交互与审核合规 |
| 12 | [karlgao616-cpu/wechat-miniprogram-cloudbase-skill](https://github.com/karlgao616-cpu/wechat-miniprogram-cloudbase-skill) | 0 | 2026-08-24 | 小程序 + 腾讯云 CloudBase 通用技能 |
| 13 | [ielcharme/wechat-miniprogram-skill](https://github.com/ielcharme/wechat-miniprogram-skill) | 0 | 2026-08-30 | 商用实战手册：云开发、微信支付 API v3 直连、平台审核合规、踩坑速查 |

**配套资源（非 Skill）**：[justjavac/wechat-miniapp-radar](https://github.com/justjavac/wechat-miniapp-radar) 51,187（选型 / 趋势 / 迁移诊断工具） · [youzan/vant-weapp](https://github.com/youzan/vant-weapp) 18,462 · [wux-weapp/wux-weapp](https://github.com/wux-weapp/wux-weapp) 5,036 · [Tencent/westore](https://github.com/Tencent/westore) 4,283 · [logamee/lin-ui](https://github.com/logamee/lin-ui) 4,141 · [Moonofweisheng/wot-design-uni](https://github.com/Moonofweisheng/wot-design-uni) 2,299

---

## 4. 管理后台 / B 端中后台

| # | 仓库 | Star | 最近更新 | 说明 |
|---|------|------|----------|------|
| 1 | [data-goblin/power-bi-agentic-development](https://github.com/data-goblin/power-bi-agentic-development) | 1,037 | 2026-10-11 | Power BI AI 技能与代理插件市场，面向数据看板 / BI 场景 |
| 2 | [coffeefuelbump/csv-data-summarizer-claude-skill](https://github.com/coffeefuelbump/csv-data-summarizer-claude-skill) | 468 | 2025-10-16 | CSV 自动分析：摘要统计、异常检测、可视化建议（后台数据页常用） |
| 3 | [ahpxex/open-dashboard](https://github.com/ahpxex/open-dashboard) | 146 | 2026-06-29 | 36 种可直接复制的管理后台 UI 形态目录，由 agent 安装并组合成真实后台 |
| 4 | [myunwang/ppt-report-skills](https://github.com/myunwang/ppt-report-skills) | 81 | 2026-06-03 | 网页报告 / 看板：ECharts 图表更丰富，一页一文件便于维护 |
| 5 | [jiaiyan/element-plus-skills](https://github.com/jiaiyan/element-plus-skills) | 26 | 2026-03-13 | Element Plus 组件库技能，供 AI 正确理解与使用（Vue 系后台） |
| 6 | [Aiminnotes/UIUX-Demo-Design](https://github.com/Aiminnotes/UIUX-Demo-Design) | 12 | 2026-06-12 | 面向企业级 AI SaaS、B 端后台、Agent 平台、CRM、业财税、数据运营的 UI/UX 设计规范 |
| 7 | [Owais232/Admin-Panel-Skill-LLM-Models](https://github.com/Owais232/Admin-Panel-Skill-LLM-Models) | 6 | 2026-07-07 | 从调研到设计、构建、部署，为任意应用搭管理后台与看板 |
| 8 | [shinwood/awesome-dashboard-skill](https://github.com/shinwood/awesome-dashboard-skill) | 4 | 2026-09-01 | 把表格 / 主题 / 实时数据变成单文件高密度交互 HTML 看板 |
| 9 | [taleilon/Ayla-Saas-Admin-UI-UX-Pro](https://github.com/taleilon/Ayla-Saas-Admin-UI-UX-Pro) | 2 | 2026-05-25 | 跨 agent 的像素级 SaaS 管理后台生成技能 |
| 10 | [keskinonur/tabler-ui-skill](https://github.com/keskinonur/tabler-ui-skill) | 1 | 2026-08-12 | Tabler（Bootstrap 5）管理后台 / 看板 UI 技能 |
| 11 | [peihongjun688/wcs-plugins](https://github.com/peihongjun688/wcs-plugins) | 0 | 2026-09-05 | 多皮肤中后台脚手架插件市场 |

**配套资源（非 Skill）**：[vue-element-admin](https://github.com/PanJiaChen/vue-element-admin) ~62.2k · [AdminLTE](https://github.com/ColorlibHQ/AdminLTE) ~36.8k · [ant-design-pro](https://github.com/ant-design/ant-design-pro) ~27.2k · [ngx-admin](https://github.com/akveo/ngx-admin) ~21.7k

---

## 5. App（iOS / Android / 跨端）

| # | 仓库 | Star | 最近更新 | 说明 |
|---|------|------|----------|------|
| 1 | [ZSeven-W/openpencil](https://github.com/ZSeven-W/openpencil) | 6,127 | 2026-10-12 | 开源 AI 原生矢量设计工具，支持并发 Agent 协作出图 |
| 2 | [twostraws/SwiftUI-Agent-Skill](https://github.com/twostraws/SwiftUI-Agent-Skill) | 5,798 | 2026-10-07 | SwiftUI 技能（Paul Hudson 出品），iOS 界面首选 |
| 3 | [expo/skills](https://github.com/expo/skills) | 2,777 | 2026-10-07 | Expo 官方：Expo / EAS 项目与原生 UI 构建技能 |
| 4 | [Appllama/appllama-skills](https://github.com/Appllama/appllama-skills) | 2,549 | 2026-09-06 | 把畅销 App 的成熟模式转成原生质感界面与设计系统 |
| 5 | [hamen/material-3-skill](https://github.com/hamen/material-3-skill) | 1,472 | 2026-07-15 | Material Design 3：30+ 组件、设计令牌、主题、响应式、合规审查 |
| 6 | [dickwu/apple-design-skill](https://github.com/dickwu/apple-design-skill) | 1,210 | 2026-10-02 | 基于 Apple HIG 的跨端 UI/UX 评审，通吃 Flutter / Tauri / Electron / React Native |
| 7 | [maxrave-dev/kotlin-footguns](https://github.com/maxrave-dev/kotlin-footguns) | 1,176 | 2026-09-25 | Kotlin / Compose Multiplatform / 桌面 JVM 的踩坑地图 |
| 8 | [new-silvermoon/awesome-android-agent-skills](https://github.com/new-silvermoon/awesome-android-agent-skills) | 972 | 2026-07-27 | 现代 Android 技能合集 |
| 9 | [evanca/flutter-ai-rules](https://github.com/evanca/flutter-ai-rules) | 651 | 2026-10-10 | Flutter 技能与规则集 |
| 10 | [aldefy/compose-skill](https://github.com/aldefy/compose-skill) | 596 | 2026-07-23 | Jetpack Compose 技能，附 androidx 源码级配方 |
| 11 | [skydoves/compose-performance-skills](https://github.com/skydoves/compose-performance-skills) | 516 | 2026-06-16 | Jetpack Compose 性能专题技能库 |
| 12 | [AThevon/genjutsu](https://github.com/AThevon/genjutsu) | 462 | 2026-10-05 | 创意编码技能：动效、微交互、设计系统 |
| 13 | [ceorkm/mobile-app-ui-design](https://github.com/ceorkm/mobile-app-ui-design) | 417 | 2026-06-25 | 专业移动 App UI/UX 设计技能 |
| 14 | [ai-dashboad/flutter-skill](https://github.com/ai-dashboad/flutter-skill) | 388 | 2026-09-01 | Flutter 端到端测试技能（253 个 MCP 工具，覆盖 10 平台） |
| 15 | [Meet-Miyani/compose-skill](https://github.com/Meet-Miyani/compose-skill) | 302 | 2026-10-11 | Compose Kit：Jetpack Compose 与 Compose Multiplatform 技能 |
| 16 | [Wholiver/swiftui-design-skill](https://github.com/Wholiver/swiftui-design-skill) | 207 | 2026-05-01 | SwiftUI 前端设计六条铁律 + 设计方向咨询 |
| 17 | [yzfly/awesome-design-html](https://github.com/yzfly/awesome-design-html) | 159 | 2026-06-14 | 115 套品牌主题 HTML 设计（93 Web + 22 iOS，含 20 套中国品牌） |
| 18 | [Drjacky/claude-android-ninja](https://github.com/Drjacky/claude-android-ninja) | 124 | 2026-09-29 | Android + Kotlin + Compose：模块化架构、导航、测试 |
| 19 | [ameyalambat128/swiftui-skills](https://github.com/ameyalambat128/swiftui-skills) | 121 | 2026-07-06 | 基于 Apple Xcode AI 文档整理的 SwiftUI 技能 |
| 20 | [awesome-skills/mobile-app-design](https://github.com/awesome-skills/mobile-app-design) | 79 | 2026-02-05 | 移动 App UI/UX 综合技能：iOS、Android、无障碍、React Native |
| 21 | [ayush016/android-lead-agent-skills](https://github.com/ayush016/android-lead-agent-skills) | 68 | 2026-07-01 | 面向 Android 技术负责人的技能与提示词 |
| 22 | [haider-nawaz/liquid-glass-skill](https://github.com/haider-nawaz/liquid-glass-skill) | 65 | 2026-02-14 | Apple Liquid Glass 设计体系（iOS 26/27）落地与迁移 |

---

## 选型建议

- **只装一套打底**：`anthropics/skills` 的 `frontend-design`。官方维护、文档齐全，先让 Agent 立一套能被认出来的审美，再写代码。
- **页面能出但一股 AI 味**：叠加 `Leonxlnx/taste-skill`（管方向与禁区）+ `pbakaus/impeccable`（带审查命令，对着现成页面挑毛病）。
- **要色板 / 字体 / 风格库存**：`nextlevelbuilder/ui-ux-pro-max-skill` 一份搞定检索。
- **管理后台**：`shadcn-ui/ui`（官方 skill）+ `ahpxex/open-dashboard` 补布局形态；Vue 系走 `jiaiyan/element-plus-skills`。
- **微信小程序**：工程侧优先腾讯云 CloudBase 官方两个仓（`awesome-miniprogram-skills` + `mp-skills`），设计规范用 `Billzhouheart/wechat-miniprogram-designUI`。
- **App**：iOS 首选 `twostraws/SwiftUI-Agent-Skill`，Android 走 `skydoves/compose-performance-skills` / `aldefy/compose-skill`，跨端 Flutter 用 `evanca/flutter-ai-rules`。
- **别按 star 从第 1 个装到最后一个**——同类只留 1～2 个，否则技能之间会互相打架。

> 图片 / 星标每天在变，本清单的数字截至 2026-10-12，如需最新值可重新跑一遍 GitHub API。
