## Lamarck &nbsp; &nbsp; &nbsp; 2025-8-26
#### 该文档用于记录ChimeraX的常用指令、功能
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
close #1  #关闭单个文件
close all  #关闭全部文件
```

*05  导出选中的结构*
```bash
save asu.pdb selectedOnly true
```

*06  选中某条链的残基*
```bash
select #1/A:100-200  #选中连续的残基
select #1/A:100,150,200  #选中离散的残基
select ~sel  #反选残基
```

*08  按链拆分某个模型*
```bash
split #1
```

*09  删除某个氨基酸，从而实现链的断开*
```bash
delete #1/C: 72  #删掉单个残基
delete #1/C: 72-78  #删除离散残基
```

*10  寻找邻近的残基*
```bash
select zone #1/C:260-268 5  #选中距离目标片段距离在5埃内的残基
```

*11  把model1和model2叠在一起（看结构上的突变、差异）*
```bash
mm #3 to #1
```

*12  连续选中残基*
```bash
按住Ctrl+Shift，左键
```

*13  自动选中复合物的相互作用位点*
```bash
Molecule Dispaly导航栏中点Interfaces，在右下角无向图中左键某条线，选择Select contact residues of xx and xx
```

*14  把结构导出为png并设置透明背景*
```bash
save output.png transparentBackground true
```

*15  手动设置选中片段的颜色*
```bash
选中结构后，导航栏依次点: Actions-color
```


