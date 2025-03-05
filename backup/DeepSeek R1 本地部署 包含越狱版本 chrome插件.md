DeepSeek 是一家初创公司，近期发布了全新一代大模型“DeepSeek-V3”，并将其免费开源，供用户本地部署使用。

本地部署方法：
	1.	通过 Ollama 安装：
	•	Ollama 官方下载地址： [点击前往](https://ollama.com/)
	•	安装命令：
	1.5B Qwen DeepSeek R1：

	• run deepseek-r1:1.5b


	•	7B Qwen DeepSeek R1：

ollama run deepseek-r1:7b


	•	8B Llama DeepSeek R1：

ollama run deepseek-r1:8b


	•	14B Qwen DeepSeek R1：

ollama run deepseek-r1:14b


	•	32B Qwen DeepSeek R1：

ollama run deepseek-r1:32b


	•	70B Llama DeepSeek R1：

ollama run deepseek-r1:70b


	2.	下载 AnythingLLM：
	•	GitHub 开源版： [点击下载](https://github.com/anythingllm/anythingllm)
	•	官方版： [点击下载](https://anythingllm.com/)
	•	注意： 本地部署也支持开启联网搜索模式。只需在 AnythingLLM 的设置界面中，找到“代理技能”选项，启用 Web Search，并选择搜索引擎即可。

各项性能指标显示，DeepSeek-V3 与 OpenAI-o1 模型相当，甚至在某些方面有所超越。


DeepSeek R1 越狱版现已发布，提供无审查、无内容限制的体验，用户可在本地部署此 AI 大模型。


	2.	在终端中通过以下命令下载 DeepSeek R1 越狱版：
	•	7B：

ollama run huihui_ai/deepseek-r1-abliterated:7b


	•	8B：

ollama run huihui_ai/deepseek-r1-abliterated:8b


	•	14B：

ollama run huihui_ai/deepseek-r1-abliterated:14b


	•	32B：

ollama run huihui_ai/deepseek-r1-abliterated:32b


	•	70B：

ollama run huihui_ai/deepseek-r1-abliterated:70b


	chrome插件：	安装 Web UI：
	•	Chrome 插件： [点击下载](https://chromewebstore.google.com/) 或 [备用下载](https://www.dongli7.com/)

卸载已安装的模型：

ollama rm <模型名称>