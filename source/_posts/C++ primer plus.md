---
title: C++ primer plus第二章作业 
date: 2023-08-09 16:06:04
tags: c++
category: 编程学习
---

# 要求：

![](https://cdn.jsdelivr.net/gh/fwlw/HexoFiles/files/C++primerplus01.png)

# 代码实现如下

```cpp
#include <iostream>
void Time(int hour, int minutes) {
 cout << hour << " " << minutes;
}
int main (){
 int hour = 0;
 int minutes = 0;
 cout << "Enter the number of hours" << endl;
 cin >> hour;
 cout << "Enter the number of minutes" << endl;
 cin >> minutes;
 Time(hour, minutes);
}
```
