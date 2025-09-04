## Markdown 使用技巧 

### 常用语法 
标题  
`# 一级标题`  
`## 二级标题`  
`### 三级标题`  
`（最多支持六级，`#` 后需加空格）`  
<br>

文字样式  
`*斜体* 或 _斜体_`  
`**加粗** 或 __加粗__`  
`***加粗斜体***`  
`~~删除线~~`  
`行内代码`  
<br>

列表  
`- `  
<br>

链接与图片  
`[链接文字](https://example.com)`  
`![图片描述](图片路径.png)`  
<br>

多行代码  
```python
def hello():
    print("Markdown")
```
<br>

表格  
| 左对齐 | 居中对齐 | 右对齐 |
|:-------|:-------:|-------:|
| 单元格 | 单元格  | 单元格 |
<br>

引用与分割线  
`> 引用内容`  
`--- 或 *** （分割线，至少三个符号）`
<br>

转义符号  
用 \ 输出特殊符号（如 \* 显示为 *）  
<br>

任务列表（GitHub 扩展）
- [x] 已完成 
- [ ] 未完成



### 折叠收起样式 

#### 折叠示例代码 
<details>
<summary>查看CSS代码</summary>

```css
.container {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  gap: 20px;
}
```
</details>


#### 折叠内容片段 
<details>
<summary>如何使用12列栅格？</summary>

12列栅格的使用方法：
1. 设置栅格
2. 对齐元素
...

</details>


#### 默认展开折叠内容 
<details open>
<summary>这个默认是展开的</summary>

添加`open`属性，内容默认展开

</details>
