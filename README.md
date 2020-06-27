# mathprolib
[![star](https://gitee.com/index-1048576/mathlib/badge/star.svg?theme=white)](https://gitee.com/index-1048576/mathlib/stargazers)  [![fork](https://gitee.com/index-1048576/mathlib/badge/fork.svg?theme=white)](https://gitee.com/index-1048576/mathlib/members)

9种编程语言通用的数学运算专用库，使用简单，内含三角学、分数运算、科学计算法等实用功能。


# 下载
| 编程语言 | 下载方法/命令                          |
|--------|----------------------------------------|
| Python | pip install mathprolib                 |
| Go     | go get -u github.com/wrmdcxy/mathprolib|
| C      | unknow                                 |
| C++    | unknow                                 |
| Java   | unknow                                 |
| JavaScript| unknow                              |
| Ruby   | unknow                                 |
| Lua    | unknow                                 |
| Julia  | unknow                                 |



# 分数运算
下面是分数运算的用法示例，这里以Python为例子

```python
from mathprolib import Fraction,Float2Fraction
f = Fraction.VulgarFraction(1,4) #1是分子，4是分母
print(f)
print(f + f/2) #测试加法、除法功能
print(f + 0.5) #测试＋float功能
print(Float2VulgarFraction(7.777777777)) #测试float2VulgarFraction
```

# 科学计数法运算
下面是科学计数法的用法示例，这里以Python为例子
```python
from mathprolib import Scientific
s = Scientific.Scientific_notation(3,5)
print(s)
print((a*a)**2) #就是a**4的意思
print(a+666)
```
