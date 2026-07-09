# LLM Chat

一个基于 Web 的大语言模型聊天界面，支持连接 OpenAI API 兼容的服务端。

A web-based large language model chat interface that supports connecting to OpenAI API compatible endpoints.

---

## 功能特性 | Features

- **API 连接 | API Connection**：支持 OpenAI 兼容的 API 端点，自动发现可用模型 | Supports OpenAI compatible API endpoints, automatically discovers available models
- **多对话管理 | Multi-Conversation Management**：创建、切换、删除对话，每个对话独立保存 | Create, switch, delete conversations, each saved independently
- **流式输出 | Streaming Output**：实时流式显示 AI 响应 | Real-time streaming display of AI responses
- **PDF 上传 | PDF Upload**：支持上传 PDF 文件进行内容分析 | Supports uploading PDF files for content analysis
- **LaTeX 公式 | LaTeX Formulas**：支持行内公式 `$...$` 和块级公式 `$$...$$` | Supports inline formulas `$...$` and block formulas `$$...$$`
- **主题切换 | Theme Switching**：深色/浅色主题，支持字体大小调整 | Dark/light themes, supports font size adjustment
- **系统提示词 | System Prompt**：每个对话可自定义系统提示词 | Each conversation can have a custom system prompt
- **本地存储 | Local Storage**：API 配置、对话历史自动保存到浏览器 | API configuration and conversation history automatically saved to browser
- **响应式设计 | Responsive Design**：适配桌面和移动端 | Adapts to desktop and mobile devices

---

## 使用方法 | Usage

1. 直接在浏览器中打开 `index.html` | Open `index.html` directly in your browser
2. 输入 API 接入端地址（如 `https://api.openai.com/v1`） | Enter the API endpoint URL (e.g., `https://api.openai.com/v1`)
3. 输入 API 密钥 | Enter your API key
4. 点击"保存配置 & 连接" | Click "Save Config & Connect"
5. 选择模型开始对话 | Select a model to start chatting

---

## 快捷键 | Keyboard Shortcuts

- **Enter**：发送消息 | Send message
- **Shift+Enter**：换行 | New line
- **Esc**：中断当前生成 | Abort current generation

---

## 技术栈 | Tech Stack

- HTML5 / CSS3 / JavaScript
- Marked.js（Markdown 渲染 | Markdown rendering）
- KaTeX（LaTeX 数学公式渲染 | LaTeX math formula rendering）
- PDF.js（PDF 文件解析 | PDF file parsing）

---

## 浏览器兼容 | Browser Compatibility

支持所有现代浏览器（Chrome、Firefox、Safari、Edge）。

Supports all modern browsers (Chrome, Firefox, Safari, Edge).