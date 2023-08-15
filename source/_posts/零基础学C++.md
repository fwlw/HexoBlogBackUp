---
title: 零基础学C++
date: 2023-08-15 16:56:31
tags: c++

---

# 要求：逆序输出三位数

```cpp
#include <iostream>
using namespace std;

int main () {
    int a;
    while(cin >> a){
    int bai = a / 100;
    int shi = a %100 /10;
    int ge = a % 10;
    cout << ge << shi << bai << endl;
    }
}
```

# 结果显示如下：

![](https://cdn.jsdelivr.net/gh/fwlw/HexoFiles/files/%E9%9B%B6%E5%9F%BA%E7%A1%80%E5%AD%A6C++01.png)
