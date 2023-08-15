---
title: C++ primer plus 第三章作业
date: 2023-08-10 18:00:31
tags: c++

---

# 要求：

![](https://cdn.jsdelivr.net/gh/fwlw/HexoFiles/files/C++primerplus02.png)

# 代码实现如下

```cpp
#include <iostream>

using namespace std;
const int Day_To_Hour = 24; // 天转换小时
const int Hour_To_Minute = 60; //小时转换分钟
const int Minute_To_Second = 60; //分钟转换秒
int main() {
    long long seconds = 0;

    int day,hour, minute = 0;
    cout << "请输入你的秒数" << endl;
    cin >> seconds;
    day = seconds / (Day_To_Hour * Hour_To_Minute * Minute_To_Second);
    seconds = seconds % (Day_To_Hour * Hour_To_Minute * Minute_To_Second);

    hour = seconds / (Hour_To_Minute * Minute_To_Second);
    seconds = seconds % (Hour_To_Minute * Minute_To_Second);

    minute = seconds / Minute_To_Second;
    seconds = seconds % Minute_To_Second; //每次的秒的余数

    cout << day <<"day" << hour <<"hour" << minute <<"minute" << seconds << "seconds" << endl;
}
```
