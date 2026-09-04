# 人生决策助手：交互约定

## Canonical UI Map

| Capability | Canonical owner | Source of truth | Allowed variants | Verification |
|---|---|---|---|---|
| Select/Listbox | 原生 select | UX-CONTRACT.md | 平台原生弹层 | 键盘和小屏检查 |
| Form | 原生输入控件与内联提示 | UX-CONTRACT.md | 创建、编辑、打分 | 必填及范围检查 |
| Scrollbar | 全局样式与矩阵容器 | src/styles.css | 矩阵横向滚动 | 小屏检查 |
| Toast | App 顶部状态条 | src/main.jsx | 保存、复制、删除 | 屏幕阅读器状态区 |
| CRUD | App 状态与 localStorage 封装 | src/main.jsx | 创建、编辑、删除 | 刷新后检查 |

| 操作 | 规范 |
|---|---|
| 保存 | 所有编辑即时保存至 localStorage；状态条说明保存结果。 |
| 创建 | 填写名称后进入编辑页；不完整数据以清晰提示阻止进入打分。 |
| 删除 | 首页删除使用应用内确认层，确认后停留首页并提示。 |
| 导航 | 编辑、打分、结果可互相切换；任意修改实时写入本地。 |
| 表单 | 使用原生输入控件、可见焦点与内联校验；没有平台弹窗。 |
| 表格 | 打分矩阵使用语义 table，小屏在表格本身横向滚动。 |
| 反馈 | 顶部状态条为唯一的非关键反馈；关键限制就地说明。 |

数据没有账号、网络同步或恢复保证；浏览器清除站点数据会清除这些记录。
