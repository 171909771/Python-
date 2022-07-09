# 列表中的sort
## sort后重新排列数据
```
a=[['b',2],['a',4],['d',3],['t',7]]
size=lambda x: x[1]
a.sort(key=size, reverse=True)
a
```
# sorted 的用法
## 直接sorted 数据，不改变列表
```
sorted(map(size,a))
```
