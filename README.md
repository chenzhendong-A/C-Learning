# C-Learning

> 东莞理工 · 工业软件 · C 语言学习仓库
> 从零开始，把每一次敲过的代码都留下来。

## 这个仓库是什么

存放 C 语言课程作业、课后练习、PTA/实验题目和一些自己写着玩的小程序。
目的不是凑 star，是把整个大一的代码 growth 过程完整记录下来 —— 一年后回头看，
这一条一条 commit 就是你的简历素材。

## 目录结构

```
C-Learning/
├── 01-basics/        # 语法基础：分支、循环、数组
├── 02-pointer/       # 指针、字符串
├── 03-memory/        # 动态内存分配 malloc/free
├── 04-bitwise/       # 位运算
├── 05-exercises/     # 课后题 / 竞赛题
└── 06-coursework/    # 课程设计、大作业
```

## 编译方式

本机工具链：MSYS2 UCRT64 gcc 16.2.0

```bash
gcc -std=c11 -Wall -Wextra -o main main.c
./main
```

`-Wall -Wextra` 建议一直开着，把 warning 当 error 看，
比事后调试省十倍时间。

## 学习进度

- [x] 基础语法
- [ ] 指针与地址
- [ ] 动态内存
- [ ] 位运算
- [ ] 结构体与文件 IO

## 作者

大一在读 · 工业软件专业 · 目标：HCIE-AI + 考研 408
