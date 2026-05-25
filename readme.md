# 总的目标

输入检查报告， 经过诊断诊断标准，得出诊断结论（什么病，或不是206种病）

# 工作内容

诊断标准，诊断条件都完整、准确分解和细化

# 检查项数据

(1) 原始数据项
(2) 复合计算数据项
(3) 复合判断数据项（医生给出或标准）
(4) 其它疾病列表项

extract_basic.txt      患者基本信息
extract_bma.txt        骨髓血检查项
extract_bmb.txt        骨髓活检查项
extract_caa.txt        染色体检查项
extract_cbc.txt        血常规检查项
extract_fcm.txt        流式细胞检查项
extract_fish.txt    FISH基因检查项
extract_pcr.txt     PCR基因检查项
extract_pba.txt        外周血检查项
extract_dis.txt        疾病结果项
... 根据需要添加

# 工作要求

原则：

- 专业 准确 可追溯

- 每一项诊断结果都有可靠人诊断标准依据，可追溯到检查的结果

具体要求：

- 每个诊断项的数据都要准确对应检查项数据的名称

- 每个诊断项的条件都能给出标准的出处（页码）

# 成果物

1. 诊断标准的json文件
2. 输出目录submissions_姓名

注:共享目录 \\192.168.124.11\0520