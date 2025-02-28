# HealthAI-2025-competition-project
HealthAI 2025 临床医学数据处理 参赛项目代码

比赛连接：https://competition.pkucxpl.com/

这个项目主要是使用adalora微调了一个qwen2.5-7b-instruct模型，并调用它生成需要的数据。带标签数据来源为：调用qwen2.5-72b-instruct模型API生成

配置要求：pytorch、transformers、peft、pandas、datasets，使用最新版本
（注：实践的时候发现transformers库和peft库可能出一些奇怪的问题，版本回退能解决一部分）

ft.ipynb执行微调

ProcessingV3.ipynb对微调后的模型进行部署和推理