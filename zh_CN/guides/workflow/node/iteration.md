# 迭代

🚧 维护中

### 定义

对列表对象执行多次步骤直至输出所有结果。

迭代步骤在列表中的每个条目（item）上执行相同的步骤。使用迭代的条件是确保输入值已经格式化为列表对象。迭代节点允许 AI 工作流处理更复杂的处理逻辑，迭代节点是循环节点的友好版本，它在自定义程度上做出了一些妥协，以便非技术用户能够快速入门。

### 场景

使用迭代节点可以实现更灵活的多步骤生成，充分发挥 Workflow 的能力。例如首先让 LLM 根据用户提供主题和摘要生成故事章节提纲，然后将故事章节提纲列作为输入，让 LLM 节点中进行多次迭代，直到生成完整的文故事。

<figure><img src="../../../.gitbook/assets/image (206).png" alt=""><figcaption></figcaption></figure>

### 什么是列表内容

列表是一种特定的数据类型，其中的元素用逗号分隔，以 `[` 开头，以 `]` 结尾。例如：

**数字列表：**

```
[0,1,2,3,4,5]
```

**字符串列表：**

```
["monday", "Tuesday", "Wednesday", "Thursday"]
```

**JSON 对象列表：**

```
[
    {
        "name": "Alice",
        "age": 30,
        "email": "alice@example.com"
    },
    {
        "name": "Bob",
        "age": 25,
        "email": "bob@example.com"
    },
    {
        "name": "Charlie",
        "age": 35,
        "email": "charlie@example.com"
    }
]
```

### 如何获取列表格式的内容

**🚧** 维护中

