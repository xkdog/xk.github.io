---
title: LaTeX文档模板
published: true
layout: post
comments: true
---

请拷贝以下语句。


\documentclass[hyperref, UTF8]{ctexbook}

\title{\textbf{我的天哪}

\author{\textit{吕小康} \\ \textit{南开大学周恩来政府管理学院}}


\CTEXsetup[name={第,章},number={\arabic{chapter}}]{chapter} % 章节编号使用数字
\usepackage{amssymb}
\usepackage{amsmath}

\usepackage{graphicx}  % 插图
\usepackage{multirow}  % 制作复杂表格的宏包
\usepackage{multicol}  % 页面分栏
\usepackage{booktabs}  % 制作三线表
\usepackage{tabu}
\usepackage{extarrows} % 使用上下可加文字的长等号
\usepackage{float} % 控制表格位置

\usepackage{theorem}
\theorembodyfont{\normalfont}
\newtheorem{definition}{定义} % 按章节号对定义进行编号
\newtheorem{theorem}{定理}   % 按章节号对定理进行编号
\newtheorem{eg}{\hskip 2em 例}[chapter]% 出现例之后先空两个字符
\newtheorem{property}{\hskip 2em 性质}

\newcommand{\solution}{\textbf{解\quad}}
\newcommand{\proof}{\textbf{证\quad}}
\newcommand\mi{\mathrm{i}}          % 定义数学状态下的虚数符号i
\newcommand\me{\mathrm{e}}          % 定义数学状态下的欧拉数e
\newcommand\tr{^\mathrm T}          % 定义矩阵的转置符号
\newcommand*\abs[1]{\lvert#1\rvert} % 定义绝对值符号
\DeclareMathOperator{\dif}{d\!}     % 定义直立微分算子
\newcommand{\grad}{\ensuremath{^{\circ}}}  % 摄氏度符号
\newcommand*{\rsoft}{\texttt{R}} % 定义等宽字体的R

\usepackage{mathtools} % 数学工具
%\usepackage{txfonts}   % 使用Times New Roman字体
\usepackage{upgreek}   % 直立希腊体
\usepackage{bm}        % 数学字体加粗


%\usepackage{stata}    % 结合stata与latex
%\usepackage{epsfig}
%\usepackage{epstopdf} % 自动将eps图像转为pdf图像

\usepackage{xcolor}    % 使用颜色包

%\usepackage[a4paper,left=3cm,right=3cm]{geometry} % 设置页面
%\usepackage{tocloft}  % 修改省略号
%\renewcommand{\cftdot}{...}
%\renewcommand{\cftdotsep}{0}


\usepackage[perpage]{footmisc} % 让每页脚注重新编号


\usepackage{float} % 可禁止表格浮动
\usepackage{caption}   % 使用caption宏包
\captionsetup[table]{labelsep= quad}  % 表格编号后空一格em的宽度
\captionsetup[figure]{labelsep= quad} % 图像编号后空一格em的宽度


\begin{document}

	\date{}

	\maketitle

我的天哪！


\end{document}

