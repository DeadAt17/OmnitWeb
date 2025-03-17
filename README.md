# Omnit - 多引擎AI翻译与润色工具

Omnit 是一款功能强大的多引擎AI翻译与文本润色工具，支持多种主流大语言模型作为翻译和润色引擎。

## ✨ 主要特性

- 🔄 **多引擎支持**：集成多个AI大语言模型作为翻译引擎，包括OpenAI、DeepSeek、Gemini、Claude、Grok、Qwen和Kimi等
- 🌐 **多语言翻译**：支持超过40种语言之间的互译，自动检测输入语言
- ✏️ **文本润色**：针对译文进行优化和润色，提高表达准确性和流畅度
- 📱 **iOS原生应用**：基于SwiftUI开发，提供流畅的用户体验和原生性能
- 🔍 **语言检测**：自动检测输入文本的语言，优化翻译效果
- 🔊 **语音输入**：支持通过语音识别直接输入文本
- 📷 **图像输入**：支持从相机或相册中导入图片，识别文本后进行翻译
- 📝 **历史记录**：保存翻译历史，方便查阅和再次使用
- 🎛️ **自定义服务**：允许用户配置自己的API端点和参数
- 🌓 **深色模式**：支持系统深色模式，保护眼睛

## 支持的语言

Omnit支持多种语言之间的互译，包括但不限于：
- 简体中文
- 繁體中文
- 英语
- 日语
- 韩语
- 法语
- 德语
- 西班牙语
- 俄语
- 意大利语
- 葡萄牙语
- 阿拉伯语
以及更多30多种语言

## 支持的翻译引擎

- OpenAI (GPT系列)
- DeepSeek
- Google Gemini
- Anthropic Claude
- Grok
- Qwen (通义千问)
- Kimi
- 自定义API服务

## 系统要求

- iOS 15.0 或更高版本（最佳体验于iOS 18.2及以上版本）
- macOS Monterey (12.0) 或更高版本 (Mac Catalyst)

## 使用方法

1. **选择模式**：在应用顶部切换"翻译"或"润色"模式
2. **选择语言**：设置源语言和目标语言（翻译模式）
3. **输入文本**：直接输入文本，或使用相机/相册导入图片识别文本
4. **获取结果**：点击"翻译"或"润色"按钮，查看结果
5. **管理引擎**：在设置中配置和管理翻译引擎及API密钥

## 项目结构

```
Omnit/
├── Views/            # 用户界面视图
├── Models/           # 数据模型
├── Services/         # 服务层
│   └── Engines/      # 翻译引擎实现
├── Extensions/       # Swift扩展
├── Utils/            # 工具类
└── Assets.xcassets/  # 应用资源
```

## 隐私说明

Omnit 重视用户隐私，所有的翻译请求直接从您的设备发送到选择的AI服务提供商，我们不会存储或查看您的翻译内容和API密钥。

## 许可证

[MIT License](LICENSE)

---

© 2024 Omnit. 版本 1.0.0

