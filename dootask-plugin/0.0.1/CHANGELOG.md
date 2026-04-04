### Fixed
- Fixed DeepSeek models not working with third-party API providers (e.g., SiliconFlow) due to incorrect base URL parameter.
- Fixed Claude models failing with "'dict' object has no attribute 'model_dump'" error when using API gateways.

### Updated
- Updated default model list to latest versions: GPT-5.4, Claude Opus 4.6, Gemini 3.1, Grok 4.20, GLM-5, Qwen3, ERNIE 5.0, and removed outdated models.

### Improved
- MCP and Vision config now only display models that are actually available (configured with API keys), giving accurate supported model counts.
