# Groq-translate-bob-plugin



基于 [Groq API](https://console.groq.com/keys) 的 Bob 翻译插件。

### 可选模型

* `llama3-8b-8192` (默认)：兼具质量和速度
* `llama3-70b-8192`：效果更好，但速度不如`llama3-8b-8192`
* `mixtral-8x7b-32768`
* `gemma-7b-it`

## 使用

1. 下载安装此插件
2. 获取 [Groq API](https://console.groq.com/keys) 的 API KEY

![image-20240425195737758](https://p.ipic.vip/h3hrsg.png)

3. 将 API KEY 填入 Bob 偏好设置 > 服务 > 此插件配置界面的 API KEY 的输入框中

![image-20240425195855409](https://p.ipic.vip/a3ewye.png)

## Notes

得益于`GroqCloud`本身巨快的推理速度，结合最新开源模型`llama3`，目前性价比超高（Groq API目前免费，但有速率限制，个人使用足够）。

![Image](https://pbs.twimg.com/profile_banners/842860575289819136/1703180970/1500x500)

## 感谢

本仓库参考部分其他优秀源码，感谢[bob-plugin-cohere](https://github.com/missuo/bob-plugin-cohere)、[bob-plugin-openai-translator](https://github.com/openai-translator/bob-plugin-openai-translator)。
