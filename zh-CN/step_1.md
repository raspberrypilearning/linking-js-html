要将 JavaScript 文件链接到 HTML 文档，请添加一个 `<script>` 元素，并将 `src` 属性设置为 JavaScript 文件的名称。

你应该将 `<script>` 元素放置在结束 `</body>` 标签之前，因为你可能需要在运行 JavaScript 函数之前加载页面上的所有 HTML 内容。

## --- code ---

language: html
filename:
line_numbers: true
-------------------------------------------------------

  <body>
    <!-- HTML content -->

```
<script src="scripts.js"></script>
```

  </body>

\--- /code ---
