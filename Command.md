## Lamarck &nbsp; &nbsp; &nbsp; 2025-8-26
#### 该文档用于记录ChimeraX的常用指令
---

*01  查看ChimeraX的工作目录*
```bash
pwd
```

*02  打开工作目录中的某个pdb文件*
```bash
open asu.pdb
```

*03  关闭某个结构文件*
```bash
close #1
```

*04  关闭全部结构文件*
```bash
close all
```

*05  选中某条链的连续残基（选中模型一A链的100-200残基）*
```bash
select #1/A:100-200
```

*06  选中某条链的离散残基（选中模型一A链的100-200残基）*
```bash
select #1/A:100-200
```

*07  按链拆分模型*
```bash
split #2
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
？？？？？
```

## 05 导出选中的结构
```
save asu.pdb selectedOnly true
```




