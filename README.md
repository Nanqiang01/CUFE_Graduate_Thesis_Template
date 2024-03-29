# CUFE_thesis_LaTeX_template

非官方中央财经大学本科论文LaTeX模板（2024重制）

Unofficial Central University of Finance and Economics LaTeX template for banchelor thesis (2024 renew)

Powered by GPT-4

> ## 20240330更新
> 1. 根据教务处最新模板修改
> 2. 修正全局字体问题
> 3. 修正脚注字体
> 4. 修正了标号列表、段落间、图名表名的行间距问题
> 5. 放弃使用旧版的宏包
> 6. 对样式根据毕业论文格式要求和原版word进行了微调

# 使用说明

建议采用编译链：latexmk (xelatex)（推荐）、xelatex->biber->xelatex->xelatex

模板采用的宏包并不复杂，但建议编译环境：TeXLive2024

如果不需要bibtex管理参考文献，可以不用biber，直接单次（或多次）xelatex，能节省一些时间

# 注意事项
1. 表格字号需要手动设置\small
2. 图表部分间隔需手动加间距，具体见代码

# 参考资源

1. 格式参考[中央财经大学本科毕业论文材料]((https://jwc.cufe.edu.cn/info/1124/3608.htm))

2. 基于github用户zshicode的[南开大学系列模板项目](https://github.com/zshicode/LaTeX-Beamer-Nankai)以及DoniaHakurei的[CUFE_template_graduate_thesis](https://github.com/DoniaHakurei/CUFE_template_graduate_thesis)修改
