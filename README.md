<div align=center>
<img  src="src/assets/logo.svg"/>
</div>

<h1 align="center">
  Qwerty Learner
</h1>

<p align="center">
  为键盘工作者设计的单词记忆与英语肌肉记忆锻炼软件
</p>

<p align="center">
  <a href="https://github.com/tiger6/qwerty-learner/blob/master/LICENSE"><img src="https://img.shields.io/github/license/tiger6/qwerty-learner" alt="License"></a>
  <a><img src="https://img.shields.io/badge/Powered%20by-React-blue"/></a>
</p>

<div align=center>
<img  src="docs/Screenshot.png"/>
</div>

## 📸 在线访问

**在线地址**: <https://qwerty.tigerfuye.com/>

## 🙏 致谢

本项目 Fork 自 [Realkai42/qwerty-learner](https://github.com/Realkai42/qwerty-learner)，感谢原作者的开源贡献！

原项目还提供了 VSCode 插件版：[qwerty-learner-vscode](https://github.com/Realkai42/qwerty-learner-vscode)

## ✨ 设计思想

软件设计的目标群体为以英语作为主要工作语言的键盘工作者。部分人会出现输入母语时的打字速度快于英语的情况，因为多年的母语输入练就了非常坚固的肌肉记忆 💪，而英语输入的肌肉记忆相对较弱，易出现输入英语时"提笔忘字"的现象。

同时为了巩固英语技能，也需要持续的背诵单词 📕，本软件将英语单词的记忆与英语键盘输入的肌肉记忆的锻炼相结合，可以在背诵单词的同时巩固肌肉记忆。

## 🛠 功能特性

- **丰富词库**：内置 CET-4、CET-6、GMAT、GRE、IELTS、SAT、TOEFL、考研英语等常用词库
- **程序员友好**：包含程序员常用单词及多种编程语言 API 词库
- **音标发音**：支持音标显示和单词发音
- **默写模式**：章节练习完成后可进行默写巩固
- **数据统计**：实时显示输入速度和正确率

## 🚀 本地运行

### 环境要求

- Node.js
- Git
- Yarn

### 安装步骤

```bash
# 克隆项目
git clone https://github.com/tiger6/qwerty-learner.git

# 进入项目目录
cd qwerty-learner

# 安装依赖
yarn install

# 启动项目
yarn start
```

项目默认运行在 `http://localhost:5173/`

## 🌐 部署

### Vercel 部署

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Ftiger6%2Fqwerty-learner)

部署时需要设置 `Output Directory` 为 `build`

### 自建服务器部署

```bash
# 构建生产版本
yarn build

# 将 build 目录部署到你的 Web 服务器
```

## 📝 License

[GPL-3.0](LICENSE)
