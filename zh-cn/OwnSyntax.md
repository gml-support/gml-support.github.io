# 添加自定义语法高亮

在目前的版本中我添加了部分插件的语法高亮支持，但我不可能对每一个插件都提供语法高亮支持，所以在 1.3.6 中加入了自定义语法高亮，你可以自行添加。

在 1.3.8 中插件内已移除这个功能，需安装 [`GML Support Custom`](https://marketplace.visualstudio.com/items?itemName=liaronce.gml-support-custom) 以继续。

## How to add

 - 安装 [`GML Support Custom`](https://marketplace.visualstudio.com/items?itemName=liaronce.gml-support-custom)

 - 在插件目录的`syntaxes`文件夹内修改`gmlextra.json`文件。 例如 `C:\Users\(your username)\.vscode\extensions\liaronce.gml-support-custom-0.0.1\syntaxes`.

 - 按照以下格式书写并保存（类似 `TextMate` 语法格式）。

```json
{
	"$schema": "https://raw.githubusercontent.com/martinring/tmlanguage/master/tmlanguage.json",
    "fileTypes": ["gml"],
    "scopeName": "source.gml-extra",
	  "patterns": [
      {
         "match": "(?i)\\b(liaronce_test)\\b",   //这是函数
         "name": "support.function.gml-extra"
      },
      {
         "match": "(?i)\\b(liaronce_test)\\b",   //这是常量
         "name": "constant.gml-extra"
      },
      {
         "match": "(?i)\\b(liaronce_test)\\b",   //这是变量
         "name": "support.variable.gml-extra"
      }
   ]
}
```

 - 重新加载 Visual Studio Code