# Toku - AI 驱动的智能项目### 🎯 Toku 核心特性

#### 💰 Token 优化核心
- **### 🎯 Toku 核心特性

#### 💰 Token 优化核心
- **�🔥 极致省钱**: 智能模板 + 分层生成，相比传统方式节省 **80% Token 成本**
- **🔌 多 API 支持**: 支持硅基流动、**Claude API**、OpenAI、通义千问等主流 AI 服务
- **📊 成本透明**: 实时显示 Token 使用量和预估成本，让每一分钱都花得明明白白
- **🎛️ 分层生成**: 第一层生成项目框架，第二层填充业务逻辑，避免重复调用

#### 🏗️ 智能生成能力  
- **🧠 AI 代码生成**: 基于先进 AI 模型，生成符合工业标准的高质量代码
- **📁 完整项目架构**: 一键生成标准 FastAPI 项目，包含路由、模型、服务、测试、Docker等
- **🎯 智能文件识别**: 自动识别12种文件类型，为每种类型应用专门优化的代码模板
- **📋 Markdown 项目定义**: 通过直观的 Markdown 语法描述需求，Toku 自动理解并实现
- **⚡ 批量智能生成**: 支持一次性生成完整项目的所有文件，包含完整业务逻辑智能模板### 2️⃣ 配置 AI API 密钥（支持多种服务）

#### 硅基流动（推荐，成本最低）
```python
# config.py
API_KEY = "your-siliconflow-api-key-here"
API_BASE = "https://api.siliconflow.cn/v1"
MODEL = "Qwen/Qwen2.5-Coder-32B-Instruct"
```

#### Claude API（高质量代码生成）
```python
# config.py  
API_KEY = "your-claude-api-key-here"
API_BASE = "https://api.anthropic.com"
MODEL = "claude-3-5-sonnet-20241022"
```

#### OpenAI（经典选择）
```python
# config.py
API_KEY = "your-openai-api-key-here" 
API_BASE = "https://api.openai.com/v1"
MODEL = "gpt-4-turbo"
```

#### 环境变量方式
```bash
# 选择你要使用的服务
export SILICON_FLOW_API_KEY="your-key-here"
# 或
export ANTHROPIC_API_KEY="your-claude-key-here"  
# 或
export OPENAI_API_KEY="your-openai-key-here"
```*80% Token 成本**
- **🔌 多 API 支持**: 支持硅基流动、**Claude API**、OpenAI、通义千问等主流 AI 服务
- **📊 成本透明**: 实时显示 Token 使用量和预估成本，让每一分钱都花得明明白白
- **🎛️ 分层生成**: 第一层生成项目框架，第二层填充业务逻辑，避免重复调用

#### 🏗️ 智能生成能力  
- **🧠 AI 代码生成**: 基于先进 AI 模型，生成符合工业标准的高质量代码
- **📁 完整项目架构**: 一键生成标准 FastAPI 项目，包含路由、模型、服务、测试、Docker等
- **🎯 智能文件识别**: 自动识别12种文件类型，为每种类型应用专门优化的代码模板
- **📋 Markdown 项目定义**: 通过直观的 Markdown 语法描述需求，Toku 自动理解并实现
- **⚡ 批量智能生成**: 支持一次性生成完整项目的所有文件，包含完整业务逻辑Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Framework](https://img.shields.io/badge/framework-FastAPI-009688.svg)](https://fastapi.tiangolo.com/)
[![AI Model](https://img.shields.io/badge/AI-Qwen2.5--Coder-orange.svg)](https://www.siliconflow.cn/)
[![Language](https://img.shields.io/badge/language-Python-3776ab.svg)](https://www.python.org/)

## 📖 项目简介

**Toku** 是一个专注于**极致 Token 优化**的 AI 项目生成器，通过智能的分层代码生成策略，最大化利用 AI 模型的能力，同时最小化 API 调用成本。

### 🎯 核心优势：Token 优化策略
- **🔥 极低成本**: 通过智能模板和分层生成，相比直接调用减少 80% 的 Token 消耗
- **🔌 多 API 兼容**: 支持硅基流动、Claude API、OpenAI 等多种 AI 服务
- **⚡ 高效生成**: 一次描述，批量生成，避免重复的 API 调用

> **设计理念**: Toku 不仅仅是代码生成器，更是 AI Token 的"节能专家"，让每一个 Token 都发挥最大价值。

### 🎯 Toku 核心特性

- **� 智能 AI 代码生成**: 基于硅基流动 Qwen2.5-Coder 模型，生成符合工业标准的高质量代码
- **🏗️ 完整项目架构**: 一键生成标准 FastAPI 项目结构，包含路由、模型、服务、测试、Docker配置等
- **🎯 智能文件识别**: Toku 能自动识别12种不同文件类型，为每种类型应用专门优化的代码模板
- **� Markdown 项目定义**: 通过直观的 Markdown 语法描述项目需求，Toku 自动理解并实现
- **🎨 专业代码模板**: 内置Router、Model、Schema、Service等多种专业级代码模板
- **⚡ 批量智能生成**: 支持一次性生成完整项目的所有文件，包含业务逻辑和最佳实践
- **🔄 增量更新支持**: 可以在现有项目基础上智能添加新功能
- **🐳 容器化就绪**: 自动生成 Docker 配置，支持一键部署

## 🏗️ 项目架构

```
Toku/
├── 📄 Routerchain.py          # 🤖 智能项目生成器核心
├── 📄 Router.py               # 🔀 路由处理器（辅助模块）
├── 📄 project_structure.md    # 📋 项目结构定义文件
├── 📄 config.py               # ⚙️ API配置文件
├── 📄 FIX_NOTES.md           # 🔧 修复说明文档
├── 📄 README.md              # 📖 项目说明文档
└── 📁 __pycache__/           # 🗂️ Python缓存文件
```

## 🚀 快速开始

### 环境要求

- Python 3.8+
- 硅基流动 API 密钥

### 安装依赖

```bash
# 安装核心依赖
pip install langchain-openai
pip install python-dotenv
pip install pathlib

# 或者一次性安装所有依赖
pip install -r requirements.txt
```

### 依赖说明
- `langchain-openai`: AI 模型调用框架
- `python-dotenv`: 环境变量管理
- `pathlib`: 路径处理工具

### 配置 API 密钥

1. **方法一：配置文件**
   ```python
   # config.py
   API_KEY = "your-siliconflow-api-key-here"
   ```

2. **方法二：环境变量**
   ```bash
   export SILICON_FLOW_API_KEY="your-siliconflow-api-key-here"
   ```

3. **方法三：.env 文件**
   ```bash
   # .env
   SILICON_FLOW_API_KEY=your-siliconflow-api-key-here
   ```

### 运行 Toku 生成器

```bash
# 进入 Toku 项目目录
cd Toku

# 运行代码框架生成器
python Router.py

# 运行智能生成器
python Routerchain.py

# Toku 会自动执行以下步骤：
# 1. 📖 解析 project_structure.md
# 2. 🧠 AI 智能分析项目需求  
# 3. 🏗️ 生成完整项目结构
# 4. 💾 保存高质量代码文件
```

## � Toku 版本历程

### v1.2.0 "智能进化" (2025-10-03)
- 🔧 修复了 AI 模型配置问题，提升生成稳定性
- 🧠 优化项目结构智能解析算法，支持更复杂的项目描述
- 📁 新增 12 种文件类型的智能识别支持
- 🎨 升级代码生成模板，包含更多最佳实践
- 🐳 新增 Docker 容器化配置自动生成

### v1.1.0 "批量生成"
- ⚡ 实现批量文件智能生成功能
- 📂 支持自定义项目输出目录
- 🛡️ 改进错误处理和异常恢复机制
- 📊 添加生成进度实时显示

### v1.0.0 "Toku 诞生"
- 🎉 Toku 首次发布，革命性的 AI 项目生成器
- 🏗️ 基础 FastAPI 项目模板支持
- 🤖 集成硅基流动 AI 模型
- 📝 Markdown 驱动的项目定义系统

## 🌟 为什么选择 Toku？

### 传统 AI 工具 vs Toku

| 传统 AI 工具 | Toku 优势 |
|-------------|----------|
| � 每个文件单独调用 API | 💰 分层生成，节省 80% Token |
| � 重复生成样板代码 | ⚡ 智能模板 + AI 填充 |
| 🔄 多次调用修正错误 | 🎯 一次生成，质量保证 |
| 📊 Token 消耗不透明 | 📈 实时成本监控 |
| � 绑定单一 AI 服务 | 🔌 支持多种 AI API |
| ⏰ 数小时反复调试 | 🚀 几分钟完成完整项目 |

### Token 成本对比 �

```
生成一个完整博客系统项目：

传统方式：
- 主文件生成：      ~2000 tokens
- 路由文件×4：      ~8000 tokens  
- 模型文件×3：      ~4500 tokens
- Schema文件×3：    ~3000 tokens
- 服务文件×3：      ~4500 tokens
- 测试文件×5：      ~5000 tokens
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
总计：约 27000 tokens ≈ $0.54

Toku 方式：
- 项目结构解析：    ~500 tokens
- 批量代码生成：    ~4500 tokens
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
总计：约 5000 tokens ≈ $0.10

💰 节省：~$0.44 (约 81% 成本节约)
```

### Toku 的魔法时刻 ✨

```markdown
# 第一层：你只需要写这些简单描述...
## blog_system/
- get_posts()    # 获取文章列表
- create_post()  # 创建新文章

# 第二层：Toku 智能分析并生成...
🎯 项目架构规划 (消耗: ~200 tokens)
📁 目录结构创建 (消耗: ~100 tokens)  
🎨 代码模板选择 (消耗: ~150 tokens)

# 第三层：批量填充业务逻辑...
✅ 完整的 FastAPI 路由 (复用模板 + AI 填充)
✅ SQLAlchemy 数据模型 (复用模板 + AI 填充)
✅ Pydantic 验证模式 (复用模板 + AI 填充)
✅ 业务逻辑服务层 (复用模板 + AI 填充)
✅ 单元测试用例 (复用模板 + AI 填充)
✅ Docker 配置文件 (标准模板)
✅ API 文档和说明 (自动生成)

💡 核心优势：分层 + 模板复用 = 极低 Token 消耗
```

### 🔌 Claude API 集成优势

Toku 特别针对 Claude API 进行了优化：

- **🎯 精准提示词**: 针对 Claude 的特性定制的提示词模板
- **📊 Token 预估**: 实时显示 Claude API 的 Token 消耗和成本
- **🔄 智能重试**: Claude API 限制时自动切换到备用服务
- **🎨 代码质量**: 充分利用 Claude 在代码生成方面的优势

## 🤝 贡献指南

欢迎加入 Toku 开发团队！请遵循以下步骤：

1. **Fork 项目** 🍴
2. **创建功能分支**: `git checkout -b feature/AmazingFeature`
3. **提交更改**: `git commit -m 'feat: Add some AmazingFeature'`
4. **推送到分支**: `git push origin feature/AmazingFeature`
5. **开启 Pull Request** 🚀

### 贡献类型
- 🐛 Bug 修复
- ✨ 新功能开发
- 📚 文档改进
- 🎨 代码模板优化
- 🧪 测试用例添加

## 📞 技术支持

- **GitHub Issues**: [提交问题](https://github.com/WTU-ETI/Toku/issues)
- **文档**: 查看 [FIX_NOTES.md](FIX_NOTES.md) 获取详细的修复说明
- **团队**: WTU-ETI 开发团队
- **邮箱**: support@toku.dev

## 📝 许可证

本项目基于 MIT 许可证开源。详见 [LICENSE](LICENSE) 文件。

## �🙏 致谢

- **硅基流动**: 提供高性价比的 AI 模型支持
- **Anthropic**: Claude API 的卓越代码生成能力
- **FastAPI**: 现代化的 Python Web 框架
- **LangChain**: 优秀的 LLM 应用开发框架
- **开源社区**: 感谢所有贡献者的支持

## 📊 版本信息

- **当前版本**: v1.0.0
- **最后更新**: 2024-12-27
- **开发状态**: 活跃维护中
- **兼容性**: Python 3.8+

## 🔗 相关链接

- [GitHub 仓库](https://github.com/WTU-ETI/Toku)
- [问题反馈](https://github.com/WTU-ETI/Toku/issues)
- [更新日志](https://github.com/WTU-ETI/Toku/releases)

---

<div align="center">

**⭐ 如果 Toku 对你有帮助，请给我们一个 Star！**

*"用更少的 Token，创造更多的价值"*

Made with ❤️ by [WTU-ETI Team](https://github.com/WTU-ETI)

</div>