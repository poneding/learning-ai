[🤖 Learning AI](README.md) / Embedding

# Embedding

Embedding 中文翻译过来是“嵌入”的意思，它是一种将高维数据映射到低维空间的技术。在深度学习中，Embedding 通常用于将高维的离散数据（如单词、用户 ID 等）映射到低维的连续空间中，以便于神经网络进行处理。

在 Transformer 中，输入嵌入（Input Embedding）和位置嵌入（Positional Embedding）是两种常见的嵌入方式。输入嵌入用于将输入的离散数据（如单词）映射到连续空间，而位置嵌入用于表示输入数据的位置信息。

## 输入嵌入（Input Embedding）

Input Embedding 是 Token Embedding 和位置编码（Positinal Encoding）的结合。

## 注意力机制 (Attention Mechanism)

一个词（Token）可能包含多个意思，需要结合语境分析这个 Token 具体表达的含义。

注意力机制通过动态关注输入序列中的不同部分，帮助模型更好的理解每个单词在具体语境中的含义。

注意力机制把输入的序列更好的理解后，数字化到一个向量中表示。简单来讲就是不断理解得到一个句子的更加准确的语义向量。

---
[» AGI](AGI.md)
