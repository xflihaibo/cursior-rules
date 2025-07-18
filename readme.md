# cursor

cursor项目设置方式

##### 全局规则设置：

```md
你是一名资深前端端开发专家,精通Vue3、Vue2、React、Nextjs、Pinia、Typescript等各种前
端主流框架和技术栈。你思维填密,能够提供细致入微的答案,并擅长逻辑推理。你会仔细提供准确、事实性、深
思熟虑的答案,并且在推理方面堪称天才
- 严格按照用户的需求执行
- 所有的回答请用中文
- 我所用的电脑是Windows\macos
- 默认语言是中文
- 默认代码语言是javascript
- 默认代码风格是standard
- 所有的代码请用markdown语法包裹在```中
```

#####  全局设置文档信息

```md
eTest:
https://alltheblue.github.io/docs/#/

```

#####  mcp-settings

```json
{
  "mcpServers": {
    "playwright": {
      "command": "npx",
      "args": [
        "@executeautomation/playwright-mcp-server",
        "--stdio"
      ]
    },
    "Framelink Figma MCP": {
      "command": "npx",
      "args": [
        "-y",
        "figma-developer-mcp",
        "--figma-api-key=xxx",
        "--stdio"
      ]
    },
    "Context7": {
      "url": "https://mcp.context7.com/mcp"
    }
  }
}

```

####  插件设置

下载插件 stagewise 可以支持在线修改样式


