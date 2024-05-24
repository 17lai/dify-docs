# 节点说明

🚧 维护中

**节点是工作流中的关键构成**，通过连接不同功能的节点，执行工作流的一系列操作。

### 核心节点

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>开始（Start）</strong></td><td>定义一个 workflow 流程启动的初始参数。</td><td></td></tr><tr><td><strong>结束（End）</strong></td><td>定义一个 workflow 流程结束的最终输出内容。</td><td></td></tr><tr><td><strong>直接回复（Answer）</strong></td><td>定义一个 Chatflow 流程中的回复内容。</td><td></td></tr><tr><td><strong>LLM</strong></td><td>调用大语言模型回答问题或者对自然语言进行处理。</td><td></td></tr><tr><td><strong>知识检索（Knowledge Retrieval）</strong></td><td>从知识库中检索与用户问题相关的文本内容，可作为下游 LLM 节点的上下文。</td><td></td></tr><tr><td><strong>问题分类（Question Classifier）</strong></td><td>通过定义分类描述，LLM 能够根据用户输入选择与之相匹配的分类。</td><td></td></tr><tr><td><strong>条件分支（IF/ELSE）</strong></td><td>允许你根据 if/else 条件将 workflow 拆分成两个分支。</td><td></td></tr><tr><td><strong>代码执行（Code）</strong></td><td>运行 Python / NodeJS 代码以在工作流程中执行数据转换等自定义逻辑。</td><td></td></tr><tr><td><strong>模板转换（Template）</strong></td><td>允许借助 Jinja2 的 Python 模板语言灵活地进行数据转换、文本处理等。</td><td></td></tr><tr><td><strong>变量聚合（Variable Aggregator）</strong></td><td>将多路分支的变量聚合为一个变量，以实现下游节点统一配置。</td><td></td></tr><tr><td><strong>参数提取器（Parameter Extractor）</strong></td><td>利用 LLM 从自然语言推理并提取结构化参数，用于后置的工具调用或 HTTP 请求。</td><td></td></tr><tr><td><strong>迭代（Iteration）</strong></td><td>对列表对象执行多次步骤直至输出所有结果。</td><td></td></tr><tr><td><strong>HTTP 请求（HTTP Request）</strong></td><td>允许通过 HTTP 协议发送服务器请求，适用于获取外部检索结果、webhook、生成图片等情景。</td><td></td></tr><tr><td><strong>工具（Tools）</strong></td><td>允许在工作流内调用 Dify 内置工具、自定义工具、子工作流等。</td><td></td></tr></tbody></table>
