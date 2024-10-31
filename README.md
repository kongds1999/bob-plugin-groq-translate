# Groq-translate-bob-plugin



基于 [Groq API](https://console.groq.com/keys) 的 Bob 翻译插件。

![image-20240425195855409](./assets/groqcloud.png)

### 可选模型
新增`llama-3.2`系列模型
* `llama-3.2-11b-text-preview`
* `llama-3.2-11b-vision-preview`
* `llama-3.2-1b-preview`
* `llama-3.2-3b-preview`
* `llama-3.2-90b-text-preview`
* `llama-3.2-90b-vision-preview`

* `llama-3.1-70b-versatile`： llama-3.1的最新中杯🥤，兼具质量和速度
* `llama-3.1-8b-instant`: (最新默认)，速度快，质量也不错
* `llama3-8b-8192`：兼具质量和速度
* `llama3-70b-8192`：效果更好，但速度不如`llama3-8b-8192`
* `llama3-groq-70b-8192-tooluse-preview`: Groq官方微调的可使用其他工具调用的测试版本
* `llama3-groq-8b-8192-tooluse-preview`: Groq测试版小杯
* `mixtral-8x7b-32768`
* `gemma2-9b-it` ：更新支持, 谷歌最新开源, 2024 / 07 /07
* `gemma-7b-it`

## 使用

1. 下载安装此插件

	![image-20240425195737758](./assets/plugin.png)

2. 获取 [Groq API](https://console.groq.com/keys) 的 API KEY

![image-20240425195737758](./assets/groqapi.png)

3. 将 API KEY 填入 Bob 偏好设置 > 服务 > 此插件配置界面的 API KEY 的输入框中

![image-20240425195855409](./assets/bobapi.png)

## Notes

得益于`GroqCloud`本身巨快的推理速度，结合最新开源模型`llama3`，目前性价比超高（Groq API目前免费，但有速率限制，个人使用足够）。

![image-20240724](assets/limits.png)
## 感谢

本仓库参考部分其他优秀源码，感谢[bob-plugin-cohere](https://github.com/missuo/bob-plugin-cohere)、[bob-plugin-openai-translator](https://github.com/openai-translator/bob-plugin-openai-translator)。
