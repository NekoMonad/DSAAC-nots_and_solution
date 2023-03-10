# 第一章：引论

---

### 1.2.4 模运算

如果$N$整除$A-B$，那么我们就说$A$与$B$模$N$同余(congruent)，记为$A\equiv B(mod\ N)$

若$A\equiv B(mod\ N)$，则$A+C\equiv B+C(mod\ N)$以及$AC\equiv BC(mod\ N)$

### 1.2.5 证明方法
最常用的是*归纳法*和*反证法*

- 归纳法
    
    主要由两个部分组成：
    1. 证明基准情况
    2. 进行归纳假设
- 反证法
    
    通过假设定理不成立，然后证明该假设导致某个已知的性质不成立，从而说明原假设是错误的

### 1.3 递归简论

注：最好别拿C系语言学递归，找门支持尾递归优化的函数式语言（比如Haskell或Scheme）稍微了解一下，就能对递归的简便有一个较为深刻的理解了（就是可能会恨不得在任何语言里都全写递归:)）
