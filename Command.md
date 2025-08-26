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

*05  导出选中的结构*
```bash
save asu.pdb selectedOnly true
```

*06  选中某条链的连续残基（选中模型一A链的100-200残基）*
```bash
select #1/A:100-200
```

*07  选中某条链的离散残基（选中模型一A链的100-200残基）*
```bash
select #1/A:100-200
```

*08  按链拆分某个模型*
```bash
split #1
```


