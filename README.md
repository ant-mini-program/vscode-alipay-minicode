# 支付宝小程序开发助手

该仓库仅供反馈使用。  
this repository is for bug report.

## 须知

您可以在 [本仓库的 Issues 中](https://github.com/ant-mini-program/vscode-alipay-minicode/issues) 提需求，提建议，提错误。  
You can make suggestions and bug report in [Issues](https://github.com/ant-mini-program/vscode-alipay-minicode/issues).

在提 issue 之前您可以搜索是否已经存在相关 issue。  
Search the existing issues to see if someone else has already opened one.

## 链接

- 支付宝小程序开发助手 [插件市场链接](https://marketplace.visualstudio.com/items?itemName=alipay.minicode)  
  提供小程序相关业务能力的支持，如 API 补全、新建小程序页面、snippets 等。
  提供 AXML/ACSS/JS/JSON 等各种文件的代码提示、语法诊断、类型推断、定义跳转等功能的支持。

## FAQ

### 为什么编辑 AXML/JS 等文件时没有提示？

请确认打开的根目录有没有以下文件之一：

- app.json
- mini.project.json

只有当这些文件存在时插件才会启动。

### 如何创建 ts/less 模板文件？

可以开启设置项：

```jsonc
{
  // 创建 ts
  "Mini-Program.scaffold.createTs": true,
  // 创建 less
  "Mini-Program.scaffold.createLess": true
}
```
