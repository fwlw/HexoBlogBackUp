---
title: C语言 九九乘法表
date: 2023-08-15 20:45:12
tags: c
---

# 要求

![](https://cdn.jsdelivr.net/gh/fwlw/HexoFiles/files/C%E8%AF%AD%E8%A8%80%E4%B9%9D%E4%B9%9D%E4%B9%98%E6%B3%95%E8%A1%A8.png)

# 代码实现：

```c
#include<stdio.h>
int main()
{
    int i,j;
    for(int i=1; i<10;i++){
        for(int j=1; j<=i; j++) {
            printf("%d*%d=%-3d",j,i,j*i); //%nd定义结果数据宽度为n，不足n补足位数，就是右对齐，添加-号表示相反，左对齐
        }
        printf("\n");
    }
    return 0;
}
```

# 结果：

![](https://cdn.jsdelivr.net/gh/fwlw/HexoFiles/files/C%E8%AF%AD%E8%A8%80%E7%BB%93%E6%9E%9C%E5%AE%9E%E7%8E%B0.png)
