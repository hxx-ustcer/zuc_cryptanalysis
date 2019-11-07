# zuc_cryptanalysis
## 环境
python 3.7
## 运行
gmssl，pillow
```bash
python zuc.py
```
## 功能描述
针对zuc加密算法的S0和S1盒进行了密码分析，分别进行了差分密码分析和线性密码分析，得到了两个盒的DDT和LAT。实验运行的结果保存在txt文档里。
zuc_s0_DDT.txt保存S0盒差分密码分析的结果，为256\times 256的表格。
zuc_s0_LAT.txt保存S0盒线性密码分析的结果，为256\times 256的表格。
zuc_s1_DDT.txt保存S1盒差分密码分析的结果，为256\times 256的表格。
zuc_s1_LAT.txt保存S1盒差分密码分析的结果，为256\times 256的表格。
