## 2. 開放格式與互操作性的戰略意義

### 2-1 解放之路

- 古時候各種手機有自己的充電頭 vs 世界統一的 USB

- 花俏複雜的 PPT vs 這次的 Markdown + Slidev slides

Microsoft Office 等專有格式長期控制我們的思維方式，讓我們專注於格式而非內容。

### 2-2 開放格式在 AI 時代的重要性

- **JSON**：API 通信的通用語言，讓不同系統能無縫交換數據

- **Markdown**：結構化文本的標準，被 GitHub、ChatGPT 等廣泛採用

- **MCP**：AI 世界的 USB 接口，透過統一的標準，跨越不同模型實現「工具串接 AI Agent」

### 2-3 避免技術依賴的戰略考量

與軟體高度綁定的檔案格式已經落伍。選擇開放格式意味著：

- 不被單一廠商綁架

- 能自由選擇最適合的工具

- 數據具有長期可存取性

- 促進創新競爭

## 3. Demo：CSV, Markdown, MCP

- [Cline + MCP](https://docs.cline.bot/mcp/mcp-overview) + Gemini API

- MCP servers: fetch, file-system

- [pandoc](https://pandoc.org/) (the document converter)

```
1. according the csv's "url" field of each rows, to read the page's full content
2. save the title and summary as markdown into new file "./news_summary.md"
3. summary have to between 150 words to 300 words
```

```
I've installed pandoc in the computer, please convert "news_summary.md" to ODT format
```

## 4.
