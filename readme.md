# 计算机组成与系统结构实验报告

夏锦熠

## 编译

本文档需使用 `xelatex` 进行编译。

编译主文档时，使用以下指令。

```powershell
latexmk -xelatex main.tex
```

编译各个章节时，需要先切换到章节目录，再进行编译。例如，编译 `chapters/chp1.tex` 具体指令如下。

```powershell
cd chapters
latexmk -xelatex chp1.tex
```