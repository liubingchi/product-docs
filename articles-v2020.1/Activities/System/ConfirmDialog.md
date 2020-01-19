# 确认框

以弹框形式将需要人工确认的信息展现出来，并可通过用户的确认结果（确认，取消）来做后续判断与流程走向的控制

## 属性

输入

- **标题** ：弹出的确认框的标题。仅支持字符串变量和字符串
- **描述** ：弹出的确认框中，需要确认的描述信息。仅支持字符串变量和字符串

输出

- **确认结果** ：将确认结果的值存储在此变量。点击&quot;确认&quot;按钮后的返回值为True; 点击&quot;取消&quot;按钮后的返回值为False