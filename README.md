# template

# application-nsfc(国家自然科学基金LaTeX模板)

在这个模版之前，国内基本上没有开源的国家自然科学基金Latex模版。因此，本人根据国家自然科学基金Word模板改造的，适合习惯用LaTex和对格式细节把控有些许洁癖的人士。建议在Windows平台下用TexLive和PDFLaTeX编译（这个配置下参考文献部分对自己名字的加粗会体现出来）。Mac和Linux平台亲测可用（xeLatex或者luaLaTeX）。可以通过Overleaf在线预览：<https://www.overleaf.com/read/jydxqkkkskzp>

我自己用这个模版成功申请到过国基金杰青项目、优青项目、面上项目等，亲测可用。我自己也认识数十位老师用这个模版的前序版本成功申请到国基金，从未听说过有人因为格式问题遇到障碍。建议大家不要纠结Windows、Mac、Linux等不同平台下的微小字体差异，而是把精力放在材料内容本身。我也考虑过上传字体文件对这些微小的差异做统一，但是会导致模版文件太大，不符合我自己精简的习惯。

近期，我根据2025年的模版进行了更新，特别分享了我的撰写经验。根据我自己函评和会评的精力，我也在该模版中把各部分应该注意的问题进行了说明，希望这些经验能够帮助大家更好整理自己思路。

如果您有任何修改建议，可以联系：cmm AT nankai dot edu dot cn

南开大学，程明明

# SYSU Beamer Template

A LaTeX beamer template for SYSU modified from the RUC beamer template [https://github.com/andelf/ruc-beamer-template](https://github.com/andelf/ruc-beamer-template).

## Screenshots

![](./screenshots/sysu-beamer-titlepage.png)

![](./screenshots/sysu-beamer-toc.png)

## Build

Complie the `main.tex` file using

    latexmk with xelatex engine

or,

    xelatex x2

## Dependencies

- Change the fonts compatible with your computer
