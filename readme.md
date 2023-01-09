# 计算机组成与系统结构实验报告

北京邮电大学网络空间安全学院“计算机组成与系统结构”课程实验报告

## 声明

内容仅供参考。不保证内容的完整性与正确性。

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
