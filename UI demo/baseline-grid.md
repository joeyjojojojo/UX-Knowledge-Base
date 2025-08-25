📐 基线网格的核心原理
计算公式 
```
/* 基础设置 */
--baseline: 24px;

/* 所有文字的line-height都是基线的倍数 */
line-height: var(--baseline);    /* 24px */
line-height: calc(var(--baseline) * 2);  /* 48px */

/* 间距也使用基线的倍数 */
margin-bottom: var(--baseline);  /* 24px */
padding: calc(var(--baseline) / 2);  /* 12px */ 
```

为什么选择24px？
- 数学友好：可被2、3、4、6、8、12整除
- 阅读舒适：16px正文 × 1.5倍行高 = 24px
- 设计灵活：可以用12px做精细调整

实际应用技巧
- 先定基线：确定基线高度（通常是正文字号的1.4-1.6倍）
- 统一行高：所有文字的line-height都是基线的倍数
- 对齐间距：margin和padding也使用基线的倍数
- 微调位置：用小量的margin-top来精确对齐不同字号


