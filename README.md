# py-ai-companion 🤖

## 📖 项目简介
基于 Streamlit 与 DeepSeek API 构建的 AI 智能伴侣，支持人格自定义、多轮对话记忆与本地会话持久化。

## 🚀 核心特性
- **大模型对话**：接入 DeepSeek API，实现流式打字机输出。
- **长期记忆**：基于“滚雪球”逻辑维护历史消息，支持多轮对话上下文。
- **人格定制**：通过 System Prompt 动态注入角色性格与昵称。
- **多会话管理**：基于本地 JSON 文件实现会话的新建、加载与删除。

## 🛠️ 技术栈
- **语言**：Python 3.13
- **框架**：Streamlit
- **核心库**：OpenAI SDK (兼容 DeepSeek API)

## 🚀 快速运行
1. **克隆项目**
   ```bash
   git clone https://github.com/MiloZorin/py-ai-companion.git
   cd py-ai-companion
   ```

2. **创建虚拟环境并安装依赖**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate  # Windows
   pip install streamlit openai
   ```

3. **配置 API Key**
   本项目依赖系统环境变量注入 API Key：
   ```powershell
   $env:DEEPSEEK_API_KEY="你的真实Key"
   ```

4. **运行应用**
   ```bash
   streamlit run ai_companion.py
   ```

## 📌 版本记录
v1.0.0 (2026-10-07)：项目初始化，完成基础 UI、流式对话、上下文记忆及多会话持久化。

## 📝 个人记录
本项目是我学习 Python+AI 的第一个实战项目。
*   **课程来源**：B站黑马程序员
*   **视频 BV 号**：`BV1sHU9BmEne`
*   **课程全称**：《黑马程序员Python+AI零基础入门到大神全套视频课程，覆盖Python核心语法、AI应用、数据分析及Web应用等python实战项目开发全流程》
*   **主讲老师**：邓昌涛（涛哥）
*   **项目定位**：AI 应用实战