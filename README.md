# my-cli-tool

> 一个基于 Node.js + TypeScript 编写的命令行工具。

## 功能特性

- 待补充：列出 CLI 的核心能力，例如批量处理、代码生成、本地开发辅助等。
- 待补充：参数解析、子命令、配置文件、日志输出等。

## 安装

从 npm 安装（发布后）：

```bash
npm install -g my-cli-tool
# 或
yarn global add my-cli-tool
# 或
pnpm add -g my-cli-tool
```

本地从源码运行：

```bash
git clone https://github.com/2955491041-art/my-cli-tool.git
cd my-cli-tool
pnpm install
pnpm build
node dist/index.js --help
```

## 使用

```bash
# 查看帮助
my-cli-tool --help

# 查看版本
my-cli-tool --version

# 示例命令（按需替换）
my-cli-tool <command> [options]
```

## 命令

| 命令 | 说明 |
| --- | --- |
| `init` | 初始化项目 / 配置 |
| `build` | 执行构建类操作 |
| `--help` | 显示帮助信息 |

## 开发

```bash
# 安装依赖
pnpm install

# 开发模式（监听文件变化）
pnpm dev

# 类型检查 + 构建
pnpm build

# 运行测试
pnpm test

# 代码规范
pnpm lint
pnpm format
```

## 目录结构

```
my-cli-tool/
├── src/
│   ├── index.ts        # 入口，注册子命令
│   ├── commands/       # 子命令实现
│   ├── lib/           # 核心逻辑
│   └── utils/         # 工具函数
├── package.json
├── tsconfig.json
└── README.md
```

## License

待定（建议 MIT 或 Apache-2.0）。
