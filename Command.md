## 01 关闭结构文件

#### 关闭全部结构文件
```
close all
```

#### 关闭单个结构文件
```
close #1
```

## 02 拆开聚合物的每一条链
```
split #1
```

## 03 把几个结构整合在一起
```
combine #2,3 name combined_model
```

## 04 改变单个结构的透明度
```
transparency #1 50
```

## 04 导出选中的结构
```
save asu.pdb selectedOnly true
```

