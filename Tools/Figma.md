## Figma快捷键 
显示/隐藏栅格 Shift + Ctrl + 4  
Shift+A 自动布局  
Ctrl+Alt+G 为所有元素创建画框（Frame）   
Ctrl + G 创建组  
Shift + 1： 缩放至适应屏幕（看清画布上所有的内容）。 
Shift + 2： 缩放至选中物体（快速定位到画布上的某个特定部分）。 
Ctrl/Cmd + \ ： 隐藏/显示侧边栏，让你拥有更大的画布视野。 

画布的操作 
平移 (Panning)： 按住 空格键 并拖动鼠标，或者使用鼠标中键，在无限的画布中移动视角。 
缩放 (Zooming)： 使用 Cmd/Ctrl + 鼠标滚轮，或者按 Z 键点击，来放大或缩小查看画布上的细节。 





## 技巧 
1、clip content 不显示画框外的内容   
裁剪内容，于控制父容器（如 Frame、Component、Group 等）是否裁剪超出其边界的子元素内容。  
Frame：默认开启，Group：默认关闭。  
- 操作：选中父容器（如 Frame/Component/Group）后，在右侧属性面板的 「Design」 标签下找到 「Clip Content」 复选框。  
- 与Mask的区别：Clip Content 是矩形裁剪（依据容器边界）。Mask 可使用任意形状路径裁剪（如圆形、多边形）。  

2、创建自动布局后，调整间距，  
快速设置两个模块间的位置关系  

3、底部栏  
设置 position = bottom，  
改变页面高度时，将始终保持在页面下方  

4、卡片名称高度控制  
选 fixed heigh，为标题区域留出2行空间  

5、自动布局技巧、同类样式替换  
如 底部栏、轮播卡片 等元素，先做好第一个，复制多个，创建自动布局，剩余几个直接替换里面的图标元素，可快速完成区块的设计。  

6、轮播设置方法  
以轮播卡片为例，每个卡片是子Frame，多个卡片组成轮播区块 父Frame  
确保所有子Frame的排列宽度，超出父Frame边界，父Frame开启"Clip Content"（裁剪溢出内容） 


7、响应式布局：自动布局后，宽度 选 fill container  





## 认识 Figma 
- Assets：素材面板，所有可用的组件库。  
- Prototype：原型面板，可设计交互原型、动效等等。  


## 使用流程 

### step1 建立基础设计元素 
- 颜色
- 字体
- 图标：可以绘制，也可以找现成的 >>> 准备好所有的图标  
** Variable 变量
** Style 样式    

#### 图标  
- (1) Assets - 图书图标(右侧) - UI kits，查看有哪些可用的 UI Kits（用户界面工具包）。  
  ** Simple Design System，Figma提供的组件库  
  ** Material 3 Design Kit，安卓设计规范  
  ** iOS 18 and iPadOS 18，iOS and iPadOS 26，iOS设计规范  

- (2) 添加后，**先修改 size**   
- (3) 点击右键断开链接 Ctrl+Alt+B，选中 Detach instance（分离实例），用于断开组件实例（Instance）与主组件（Master Component）的关联，使其成为独立可编辑的图层。  

- (4) 修改颜色：选中元素 - 在颜色设置区域 - Detach variable - 设置颜色  
** Detach Variable（分离变量） 是指将设计元素与已绑定的**变量**解除关联，使其恢复为固定值。  


### step2 创建页面和网格系统  
规范元素的排列、对齐   
帮助页面实现响应式   

- APP 竖网格 4列  
- Web 一般设置为 12列  

### step3 封装组件
重复使用的内容设置为组件后，改动主组件，相关实例会统一修改  
成为组件的元素会显示为紫色  










