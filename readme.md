# 使用方法
## 🚀设置type及top100_list_final_length值
```
若type==1, 数据从输入行获取; 
否则，输入数据随机自动生成
top100_list_final_length:
    榜单最长长度，为简单起见此处设为10
```
## 🚀运行 log_sort
```
type:
    若type==1, 需手动输入数据
    否则，输入数据随机自动生成
```
## 🚀程序读取数值，并输出当前榜单
```
例：
input item: 8 ;my top 10 logs now is: [814, 823, 832, 836, 836, 885, 892, 918, 978, 991]
```
## 🚀 测试用例
```
当type==1
3
8
4
5
99
75
65
43
73
33
55
77
2
35
46
7
24
56
564
```

### 备注
目前只是简单的插入排序，因为榜单长度确定为100，
所以最坏的时间复杂度为 O(100N) ==> O(N)
