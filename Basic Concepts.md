# a. 界面元素 
用户界面设计领域（UI，User Interface），共有 36个原子元素，15 个组合元素。
- 一、布局类
- 二、导航类 
- 三、信息展示类  
- 四、媒体与数据可视化
- 五、排版与装饰 
- 六、输入与交互控件
- 七、反馈与提示 
- 八、组合型界面元素


## 一、布局类 
布局与结构（Layout & Structure）

### 📐 1. 栅格系统 

栅格系统(Grid / Flexbox) 是现代网页设计的重要基础，它为内容布局提供了规范化的解决方案。

#### (1) 作用
- 对齐元素，使界面看起来统一  
- 排列有序、减少视觉混乱，使阅读更轻松  
- 响应式设计，多种客户端下保持良好布局、完美适配   
- 设计提效，不用每次都重新思考布局，开发更容易实现   

#### (2) 常见栅格系统
- 12列栅格系统（最流行）
> 将页面宽度分成12等份，内容可以占1列、2列、3列...或者组合使用，Bootstrap、Material Design都在用。
> 
```
常用布局组合：
6 + 6  = 两栏等宽布局
8 + 4  = 主内容区 + 侧边栏
4 + 4 + 4  = 三栏等宽布局
```
- 8列栅格系统
> 适合移动端设计，更简洁的布局选择。

#### (3) 使用方法 
步骤：设置栅格 - 对齐元素 - 使用栅格的间隙 gutter 作为元素间距 


#### (4) 实际案例
- 导航栏：Logo占2列，菜单占8列，用户头像占2列
- 内容区域：主内容占8列，侧边栏占4列
- 卡片布局：每个卡片占4列，一行放3个

#### *>> 拓展内容*

<details>
<summary>Bootstrap简介</summary>  

>.  
> Bootstrap是什么？
> - 一个前端框架，主要给程序员用的  
> - 提供了大量预制的UI组件（按钮、表格、导航栏等）  
> - 程序员可以快速搭建网站，不用从零开始写代码  
>  
> 对UI设计师的意义：
> - Bootstrap定义了很多标准的设计规范
> - 比如按钮尺寸、颜色、间距等都有统一标准
> - 很多网站都基于Bootstrap，所以了解它有助于理解常见的网页布局

</details>

<details>
<summary>Material Design简介</summary>

>.  
> Material Design是什么？
> - Google制定的设计语言
> - 不只是给程序员的，更是给设计师的完整设计指南
> - 包含颜色、字体、动效、交互等各方面规范
> 
> 核心理念：
> - 拟物化概念：像纸张一样有层次、阴影
> - 统一体验：Android、Google网站都遵循这套规范
> - 响应式：适配各种设备尺寸
> 
> 实际应用：
> - Android应用的标准设计风格
> - Gmail、YouTube等Google产品都在用
> - 很多设计工具（Figma等）都有Material Design组件库

</details>

<details>
<summary>Bootstrap vs Vue 对比</summary>

>. 
> 特点 | Bootstrap | Vue
> -- | -- | --
> 类型 | CSS框架 | JavaScript框架
> 主要作用 | 样式和布局 | 应用逻辑和数据处理
> 解决问题 | 让网页好看 | 让网页有交互功能
> 
> Bootstrap（样式层）： 
> - 提供现成的CSS样式和组件
> - 解决"界面长什么样"的问题
> - 包含按钮、表格、导航栏等视觉组件
> - 专注于外观和布局
> 
> Vue.js（逻辑层）：
> - JavaScript应用开发框架
> - 解决"界面如何工作"的问题
> - 处理用户交互、数据变化、页面跳转等逻辑
> - 专注于逻辑和功能 
> 
> 生活化理解：想象装修一套房子
> - Bootstrap = 装修材料（地板、墙纸、家具） → 决定房子的外观
> - Vue.js = 智能家居系统（灯光控制、温度调节） → 决定房子的功能
> 
> 实际分工举例：
> - Vue.js负责： 按钮点击后的弹窗显示、表单数据验证、页面路由跳转
> - Bootstrap负责： 按钮的样式设计、弹窗的视觉效果、整体页面布局
> 
> 对UI设计师的意义：
> - Bootstrap 直接相关性高！提供可参考的设计规范和组件样式，影响日常设计决策和组件选择，需要深入了解其栅格系统和组件设计原则。
> - Vue.js 主要供开发者使用，了解基本概念有助于与开发团队更好协作，理解哪些交互效果在技术上容易实现。
> 
> 同类技术对比：
> - Bootstrap的同类： Tailwind CSS、Bulma、Foundation（样式框架）
> - Vue.js的同类： React、Angular、Svelte（JavaScript框架）

</details>

---
### 🏗️ 2. 容器 / 区块  

容器(Containers / Sections) 是页面布局的基础单元，用于包裹和组织页面内容，确保内容在不同设备上的合理展示。

#### (1) 作用
- 视觉组织：相关内容归类，让界面看起来整洁有序。
- 信息层次：帮助用户快速理解哪些内容是相关的。
- 布局控制：更好地安排元素在页面上的位置。
- 响应式设计：在不同设备上保持良好的显示效果。

#### (2) 使用技巧
- 保持一致性：同类容器使用相同的样式
- 留白很重要：容器内外都要有适当的间距
- 层次分明：用不同的背景色、边框来区分重要程度

#### (3) 常见容器 
- 卡片（Cards）：适合展示独立的信息块，比如商品、文章预览。
- 面板（Panels）：较大的区域，用来组织复杂内容，常见于仪表板、设置页面。
- 模态框（Modals）：弹出式容器，暂时覆盖主界面，用于重要提示或表单填写。
- 标签页（Tabs）：将内容分组到不同的"页签"中，节省空间，适合相关但不同的内容类型。


---

### 🗂️ 3. 面板 / 折叠面板 
(Panels / Accordions / Drawers)

---

### ➖ 4. 分隔线 / 空白 / 间距  
(Divider / Spacer)

--- 

## 二、导航类 
Navigation

### 1. 顶部导航栏 
Top Navigation Bar 

--- 

### 2. 侧边栏 
Sidebar 

--- 

### 3. 标签页
Tabs

--- 

### 4. 文字链 
Text Link / Hyperlink 

--- 

### 5. 面包屑导航
Breadcrumbs 

--- 

### 6. 分页器 
Pagination

--- 


## 三、信息展示类  
Information Display

### 1. 卡片
Card 

--- 

### 2. 列表 / 表格 
List / Table 

--- 

### 3. 标签 / 徽章 
Tag / badge 

--- 

### 4. 头像 
Avatar 

--- 

### 5. 图标  
Icon

--- 

### 6. 进度条 / 加载动画   
Progress Bar / Spinner 

--- 


## 四、媒体与数据可视化
Media & Visualization

### 1. 图片
Image 

--- 

### 2. 视频 / 音频播放器 
Video / Audio Player 

--- 

### 3. 图表 
Charts / Graphs 

--- 

### 4. 插画 / 装饰图形  
Illustration  

--- 

## 五、排版与装饰 
Typography & Style

### 1. 标题 / 段落 
Heading / Paragraph 

--- 

### 2. 字体样式 
Typography 

--- 

### 3. 颜色 / 阴影 / 圆角  
Colors / Shadows / Border / Radius 

--- 

### 4. 背景 
Background   

--- 

## 六、输入与交互控件
Input & Interaction

### 1. 按钮 
Button 

--- 

### 2. 输入框 
Text Field / Textarea 

--- 

### 3. 下拉选择  
Dropdown / Select  

--- 

### 4. 单选 / 多选 
Radio / Checkbox 

--- 

### 5. 开关 
Switch / Toggle 

--- 

### 6. 滑块 
Slider 

--- 

### 7. 上传控件  
Files Upload 

--- 


## 七、反馈与提示 
Feedback & Status 

### 1. 弹窗 
Modal / Dialog 

--- 

### 2. 提示气泡   
Tooltip / Popover   

--- 

### 3. 通知  
Toast / Snackbar / Push / Banner 

--- 

### 4. 表单校验提示 
Validation Message 

--- 

### 5. 空状态 
Empty State  

--- 


## 八、组合型界面元素 
Composite Components 

### 1. 数据采集与输入
Data Entry

#### (1)表单  
Form

--- 

#### (2)登录框 / 注册框   
Login / Signup Form 

--- 

#### (3)步骤条 / 向导表单 
Stepper / Wizard Form 

--- 

#### (4)对话框表单 
Modal Form 

--- 


### 2. 信息检索与筛选 
Search & Filter 

#### (1)搜索栏 
Search Bar 

--- 

#### (2)过滤器 / 筛选面板 
Filter Panel 

--- 


### 3. 内容展示与推荐
Content Display & Recommendation

#### (1)轮播图 / 轮播Banner 
Banner Carousel 

--- 

#### (2)轮播卡片  
Card Carousel 

--- 

#### (3)横滑卡片 
Horizontal Scroll Cards 

--- 

#### (4)瓷片区 
Tile Area / Tile Grid 

--- 


### 4. 数据管理与操作
Data Management & Operation

#### (1)可编辑表格 
Editable Table / Data Grid 

--- 

#### (2)树形数据表格 
Tree Table / Hierarchical Grid 

--- 

#### (3)批量操作面板 
Bulk Action Panel 

--- 

### 5. 功能面板  
Functional Panels

#### (1)消息通知中心 
Notification Center 

--- 

#### (2)侧边抽屉面板 
Drawer Panel 

--- 
