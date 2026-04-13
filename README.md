# 创作者发布工作流

[![Workflow](https://img.shields.io/badge/Workflow-Creator%20Publish-111827?style=for-the-badge)](#)
[![Step 1](https://img.shields.io/badge/Step%201-Project%20Front-f59e0b?style=for-the-badge)](#)
[![Step 2](https://img.shields.io/badge/Step%202-X%20Post-2563eb?style=for-the-badge)](#)

把作品从“做出来”，推进到“整理好、发出去”。

这个仓库不是技能大合集，而是一条更聚焦的创作者工作流：

1. 先把作品门面整理出来
2. 再把作品以更合适的方式发到外部平台上

## 一条最短路径

如果你只是想最快开始，用这一条：

1. 先打开 [项目门面生成器](./项目门面生成器/README.md)
2. 整理 README、安装方式和门面入口
3. 再打开 [秋知X推文发帖生成器](./秋知X推文发帖生成器/README.md)
4. 生成主帖、第一条带链接跟帖和配图版文案

## 这仓库是什么

这是一个成熟版、主题化的工作流仓库。  
它把两件常常分开的事情接起来：

- 项目门面整理
- 对外发帖传播

适合这些场景：

- 项目已经做完，但 README 和门面还没整理好
- README 已经有了，但还没有合适的 X 主帖和跟帖
- 想把作品从“做出来”推进到“被看见”

## 工作流

### 第一步：项目门面生成器

路径：
- [项目门面生成器](./项目门面生成器/README.md)

作用：
- 整理 README
- 补安装方式
- 检查遗漏项
- 处理门面收尾

一句话理解：
- 先把作品整理到“能见人、能介绍、能移交”的状态

### 第二步：秋知 X 推文发帖生成器

路径：
- [秋知X推文发帖生成器](./秋知X推文发帖生成器/README.md)

作用：
- 生成 X 主帖
- 生成带链接跟帖
- 生成配图版短文案
- 生成更贴近创作者本人视角的发布文案

一句话理解：
- 再把已经整理好的作品，用更适合传播的方式发出去

## 怎么开始

最稳的顺序是：

1. 先用 [项目门面生成器](./项目门面生成器/README.md)
2. 再用 [秋知X推文发帖生成器](./秋知X推文发帖生成器/README.md)

如果你已经有完整 README 和截图，也可以直接从第二步开始。

## 安装

如果你的代理支持 `skills add`，可以直接装这两个 skill：

### 项目门面生成器

```bash
npx skills add AdgaiWalker/creator-publish-workflow --skill project-front-generator
```

### 秋知 X 推文发帖生成器

```bash
npx skills add AdgaiWalker/creator-publish-workflow --skill qiuzhi-x-post-generator
```

如果你不确定安装方式，也可以直接把对应 skill 的 `SKILL.md` 或目录交给 AI。

## 这两个 skill 的关系

它们不是两个零散工具，而是同一条链上的前后两步：

- `项目门面生成器`：负责把作品整理好
- `秋知X推文发帖生成器`：负责把作品发出去

连起来就是：

`做出来 -> 整理出来 -> 发出去`

你也可以理解成：

- 第一步：让作品能见人
- 第二步：让作品被看见

## 方法总纲

如果你想继续深入研究这套工作流背后的方法，可以看这两份：

- [README框架总纲](./docs/README框架总纲.md)
- [共用底稿字段表](./docs/共用底稿字段表.md)

## 和 Skills-Walker 的关系

- `Skills-Walker`：实验区、母仓库、孵化池
- 本仓库：成熟后的主题发布仓库

也就是说，先在 `Skills-Walker` 里试验、打磨，成熟后再抽出来，形成一个更聚焦的对外仓库。

## 仓库协作规则

这两个仓库默认按以下顺序协作：

1. 新改动先进入 `Skills-Walker`
2. 先在实验区完成审理、验证和打磨
3. 确认稳定后，再同步到本仓库

一句话理解：

- 实验区优先
- 主题仓库后置
