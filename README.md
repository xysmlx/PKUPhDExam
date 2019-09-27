# TeX Template of Ph.D. Examination @ Peking University

## Compile

* Please use XeLaTeX to compile this template
* This template has been tested in TeXLive2017
* Required fonts: SimSun, SimHei, Times New Roman, KaiTi

## Files

* resources: figures about Peking University
* pkuphdexam.sty: template file
* bnubib.bst: bibliography format file
* bibliography.bib: bib file
* template.tex: an example

## FAQ

1. how to support long title?
    * Edit the parameter ```\makebox[0.5\textwidth]``` in line 105 ```{\begin{center}\fontsize{22 pt}{\baselineskip}题目：\bfseries \underline{\makebox[0.5\textwidth]{\cntitle{}}} \end{center}}``` of the pkuphdexam.sty file.
2. font not found?
    * Install required fonts: SimSun, SimHei, Times New Roman, KaiTi
