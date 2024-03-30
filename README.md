# CUFE_thesis_LaTeX_template

非官方中央财经大学本科论文LaTeX模板（2024重制）

Unofficial Central University of Finance and Economics LaTeX template for banchelor thesis (2024 renew)

Powered by GPT-4

## 注意！！！

请注意格式问题可能会导致拒绝答辩。以任何形式采用该模板意味着您已承认：使用该模板而引发的一切负面或正面后果与任何你以外的人都没有任何关系。

> ## 20240330更新
> 1. 根据教务处最新模板修改
> 2. 修正全局字体问题
> 3. 修正脚注字体
> 4. 修正了标号列表、段落间、图名表名的行间距问题
> 5. 放弃使用旧版的宏包
> 6. 对样式根据毕业论文格式要求和原版word进行了微调
> 7. 修复了目录的引用超链接问题
> 8. 消灭了所有警告信息

# 使用说明

建议采用编译链：latexmk (xelatex)（推荐）、xelatex->biber->xelatex->xelatex

模板采用的宏包并不复杂，但建议编译环境：TeXLive2024

如果不需要bibtex管理参考文献，可以不用biber，直接单次（或多次）xelatex，能节省一些时间

# 注意事项
1. 表格字号需要手动设置\small
2. 图表部分间隔需手动加间距，具体见代码
3. 根据目前教务处给出的模板，对一个中文字符的理解应当是一个中文空格，即0.5em，本模板使用该标准

# 参考资源

1. 格式参考[中央财经大学本科毕业论文材料](https://jwc.cufe.edu.cn/info/1124/3608.htm)

2. 基于github用户zshicode的[南开大学系列模板项目](https://github.com/zshicode/LaTeX-Beamer-Nankai)以及DoniaHakurei的[CUFE_template_graduate_thesis](https://github.com/DoniaHakurei/CUFE_template_graduate_thesis)修改
