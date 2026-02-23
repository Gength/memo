# memo

dataset strong reject

实验一，在wildguard test用Mistral输入 harmful prompt，获得response。用wildguard筛选出response harm的，作为baseline，看一下response harmful rate（寻找一个不安全模型）
实验二，用去毒的头测一下response harmful rate，对比实验1，harm rsp rate是否下降
实验三，泛化性，在其他数据集上，去毒化之后，rsp harm rate是否下降
实验四：utility test， 消融实验①在日常prompt查看模型的触发率 ②外挂的层对实验结果的影响，用wildguard看rsp harm rate

0.6B/1B/3B, 7B, 32B
计算时延
创新性：训练，测试都加速，可以几乎实时计算
画图：时间，精度

去毒之后对
泛化性
回复的差异性: embed, 

可视化prompt harmful detection效果

超长上下文harmful detection，performance下降的幅度有多少？和别的模型相比？

TODO：幻觉检测，P(response| prompt, Ht)
https://arxiv.org/pdf/2505.07293
模型编辑-hidden states编辑-有害内容，个人隐私，特定隐私信息

