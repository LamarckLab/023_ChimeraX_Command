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
close #1 # 关闭单个文件
close all # 关闭全部文件
```

*05  导出选中的结构*
```bash
save asu.pdb selectedOnly true
```

*06  选中某条链的残基*
```bash
select #1/A:100-200 # 选中连续的残基
select #1/A:100,150,200 # 选中离散的残基
```

*08  按链拆分某个模型*
```bash
split #1
```

*09  删除某个氨基酸，从而实现链的断开*
```bash
delete #1/C: 72 # 删掉单个残基
delete #1/C: 72-78 # 删除离散残基
```




