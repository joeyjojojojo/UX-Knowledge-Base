既然你希望帮助新人建立专业知识体系，这份速查表的核心逻辑就是：**将模糊的“感觉”转化为精确的“工程语言”**。

当新人学会使用这些术语与 Stitch 或 Figma Make 交流时，他们不仅是在写提示词（Prompt），而是在学习 **前端组件规范** 和 **UI 交互逻辑**。

---

## 🎨 UI 结构与布局：从“摆放”到“盒模型”

不要只说“把东西排开”，要使用描述**容器关系**的术语。

| 需求场景 | 推荐专业术语 (Prompt Keywords) | 建立的知识点 |
| :--- | :--- | :--- |
| **容器间距** | `Auto Layout`, `Gap: 16px`, `Padding: 24px` | **盒子模型**：理解内边距与外边距。 |
| **对齐方式** | `Flex-start`, `Center`, `Space-between` | **Flexbox 布局**：掌握现代网页的对齐逻辑。 |
| **响应式策略** | `Fill container`, `Hug contents`, `Fixed width` | **自适应思维**：理解组件如何随屏幕缩放。 |
| **层级关系** | `Z-index`, `Sticky header`, `Floating Action Button` | **空间维度**：理解 UI 在 Z 轴上的堆叠逻辑。 |



---

## 🏗️ 组件解剖：从“画图”到“原子设计”

引导新人观察一个组件由哪些**原子要素**组成。

| 组件类型 | 必须包含的术语 (Properties) | 建立的知识点 |
| :--- | :--- | :--- |
| **输入框 (Input)** | `Label`, `Placeholder`, `Helper text`, `Prefix icon` | **组件构成**：识别标准表单的视觉元素。 |
| **按钮 (Button)** | `Primary/Secondary`, `Border-radius: 8px`, `Min-width` | **设计系统**：理解组件的主次与物理属性。 |
| **列表 (List)** | `List item`, `Divider`, `Chevron icon`, `Thumbnail` | **模式识别**：掌握常见 UI 模式的固定组合。 |
| **卡片 (Card)** | `Box-shadow`, `Corner radius`, `Aspect ratio` | **视觉重量**：学习如何通过样式区分内容块。 |



---

## ⚡ 交互状态：从“静态”到“动态系统”

这是新人最容易忽略的部分，利用 AI 强制要求生成**状态机**。

| 交互场景 | 必须包含的术语 (States) | 建立的知识点 |
| :--- | :--- | :--- |
| **基础反馈** | `Default`, `Hover`, `Active/Pressed`, `Disabled` | **交互链路**：理解用户操作的每一个瞬间。 |
| **数据加载** | `Skeleton screen`, `Loading spinner`, `Empty state` | **用户体验**：学习如何处理系统响应延迟。 |
| **表单校验** | `Focus state`, `Error state`, `Success validation` | **容错设计**：掌握如何引导用户纠正错误。 |
| **溢出处理** | `Truncate text`, `Horizontal scroll`, `Ellipsis` | **极限情况**：考虑真实数据过长时的 UI 表现。 |



---

## 🧪 进阶：如何用这套表进行“刻意练习”？

你可以给新人布置这样一个**“指令对比实验”**：

1.  **初级指令**（新人常犯）：
    > “帮我做一个用户登录页面，要有账号密码和登录按钮，颜色要蓝色。”
2.  **专业指令**（应用速查表）：
    > “使用 **Auto Layout** 创建一个登录卡片。包含：1. 带有 **Label** 和 **Placeholder** 的垂直 **Input Group**；2. 一个 **Primary Button**，设置 **Border-radius: 6px**；3. 考虑 **Error State** 的视觉反馈；4. 背景使用浅灰色，卡片带微弱的 **Box-shadow**。”

### 实验结论：
让新人对比两个工具产出的结果。他会发现，**专业指令产出的 UI 几乎不需要手动二次调整，且代码结构异常整洁**。

---

**下一步建议：**
你可以直接把这个表格打印出来贴在他们的工位上。你想让我针对其中某一个维度（例如 **“响应式布局”** 或 **“交互状态”**），为你出一道专门考察新人的**“AI 辅助设计实战题”**吗？
