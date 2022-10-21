# GLSL

## 基本类型

GLSL 支持数值类型和布尔类型，不支持字符串类型

数值类型分为:

- int
- float

布尔类型存在`true`和`false`两个常量

## 转换基本类型

GLSL 一般来说类型名称就是转换函数, `init()`就是将值转换成`init`的转换函数

| 函数        | 描述                              |
| ----------- | --------------------------------- |
| int(float)  | float -> init                     |
| int(bool)   | true---> 1 false ---> 0           |
| float(int)  | int ---> float                    |
| float(bool) | true ---> 1.0 false --> 0.0       |
| bool(int)   | 0 ---> false, 其他被转换为 true   |
| bool(float) | 0.0 ---> false, 其他被转换为 true |

## 矢量和矩阵
