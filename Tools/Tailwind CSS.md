```html
<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded-lg shadow-lg">
  确认提交
</button>
```

bg-blue-500：背景颜色。  
hover:bg-blue-700：鼠标悬浮时的颜色（伪类支持）。  
py-2 px-4：内边距（Padding）。  
rounded-lg：大圆角。  

text-white   
font-bold  
shadow-lg  



**Tailwind 命名逻辑**：属性-方向-数值   
https://nerdcave.com/tailwind-cheat-sheet   

1. 布局与空间语义 (The Box Model)
这是还原 Wireframe 时最频繁使用的部分。

边距 (Margin & Padding):

m- (Margin), p- (Padding)。

方向控制： t (top), b (bottom), l (left), r (right), x (左右), y (上下)。

例子： py-4 = 上下内边距 1rem (16px)；ml-2 = 左外边距 0.5rem (8px)。

间距 (Gap): * 在 Flex 或 Grid 容器中，直接用 gap-4 定义子元素之间的距离，不再需要繁琐的 margin-right。


2. 视觉特征语义 (Visual Styles)
将设计稿中的“装饰”属性转化为代码。

圆角 (Border Radius): * 语义：rounded-{size}。

常用：rounded-sm (2px), rounded-md (6px), rounded-lg (8px), rounded-full (彻底圆角/胶囊形)。

边框 (Border):

border (默认 1px), border-2 (2px)。

颜色：border-blue-500。

投影 (Shadow):

语义：shadow-{size}。

常用：shadow-sm, shadow-md, shadow-xl。


3. 文本与排版语义 (Typography)
对应您在设计系统中的字体阶梯。

字号 (Font Size): * text-xs (12px), text-sm (14px), text-base (16px), text-xl (20px) 等。

字重 (Font Weight): * font-light, font-normal, font-medium, font-bold (700)。

对齐与行高: * text-center, leading-tight (紧凑行高), tracking-wide (字间距)。


4. 颜色与透明度 (Color System)
Tailwind 使用的是数字色阶（50-950），500 通常是标准色。

背景： bg-slate-100 (浅灰背景), bg-blue-600 (主按钮色)。

文字： text-slate-900 (正文黑), text-slate-500 (辅助灰)。

透明度： 直接在后面加 /。例如 bg-blue-500/20 表示蓝色的 20% 透明度。

