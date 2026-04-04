### 修复
- 修复 DeepSeek 模型通过第三方 API 服务商（如 SiliconFlow）调用时认证失败的问题。
- 修复 Claude 模型通过 API 网关调用时报错 "'dict' object has no attribute 'model_dump'" 的问题。

### 更新
- 更新默认模型列表至最新版本：GPT-5.4、Claude Opus 4.6、Gemini 3.1、Grok 4.20、GLM-5、Qwen3、ERNIE 5.0，并移除过时模型。

### 优化
- MCP 和视觉识别配置现在仅显示当前已配置（有 API Key）的模型，支持模型计数更准确。
