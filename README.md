# my-first-project

Python 与 GitHub 实操 —— 我的第一个仓库

## 项目简介

本仓库用于练习 **Python 基础语法** 与 **GitHub 日常使用流程**：

- 新建仓库并添加 README
- 用 Markdown 编写项目说明
- 编辑文件并提交（Commit）变更
- 克隆 / 下载他人项目并复现运行

## 目录结构

```text
my-first-project/
└── README.md
```

## 示例代码（函数与运算符）

```python
def max(a, b):
    if a > b:
        return a
    else:
        return b

a, b = 4, 5
print(max(a, b))      # 5
print(21 // 10)       # 2  取整除
print(21 % 10)        # 1  取模
print('winner'[0:3])  # win 切片
```

## 学习笔记

| 内容 | 说明 |
| --- | --- |
| 标识符 | 字母/下划线开头，区分大小写 |
| 类型转换 | int()、float()、str() 显式转换 |
| 注释 | `#` 单行，三引号多行 |

> 参考课程：基于大模型的具身智能机器人实践 —— Python 练习与 GitHub 使用
