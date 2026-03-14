# AgentStudy
从原理到实践完整学习 AI Agent 构建 from Datawhale 开源社区做的系统教程
```
AgentStudy
│
├ hello-agents (fork)
│
└ my-agents
     │
     ├ ch1_basic_agent
     ├ ch2_llm
     ├ ch3_prompt
     ├ ch4_react_agent
     └ ch5_memory_agent
```


## my agents
#### ch1 Agent 的最小雏形(LLM + Prompt)
一个能处理分步任务的智能旅行助手。

* 安装依赖`pip install -r requirements.txt`
  
     依赖：
  1. `requests` HTTP 库, 访问网络 API
  2. `tavily-python`  AI 搜索 API 客户端，用于获取实时的网络搜索结果
  3. `openai`  Python SDK(软件开发工具包-Software development kit) 用于调用 GPT 等大语言模型服务。一个基本的 SDK 通常由编译器、调试器和应用编程接口（API）等组成。
  4. `python-dotenv` 管理API key
  5. `rich` 更好看的终端输出