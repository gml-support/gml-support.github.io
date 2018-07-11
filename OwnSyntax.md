# Add own syntax highlighting

In the current version I added highlighting support for some plugins, but I can not provide highlighting support for every plugins, so in 1.3.6 you can add your own highlighting.

In 1.3.8 this feature is removed in this extension, you need install [`GML Support Custom`](https://marketplace.visualstudio.com/items?itemName=liaronce.gml-support-custom) to continue.

## How to add

 - Install [`GML Support Custom`](https://marketplace.visualstudio.com/items?itemName=liaronce.gml-support-custom)

 - Edit `gmlextra.json` file in the `syntaxes` directory in the extension directory. e.g. `C:\Users\(your username)\.vscode\extensions\liaronce.gml-support-custom-0.0.1\syntaxes`.

 - Writing and saving syntax highlighting in the following format (like `TextMate` grammar).

```json
{
	"$schema": "https://raw.githubusercontent.com/martinring/tmlanguage/master/tmlanguage.json",
    "fileTypes": ["gml"],
    "scopeName": "source.gml-extra",
	  "patterns": [
      {
         "match": "(?i)\\b(liaronce_test)\\b",   //This is functions
         "name": "support.function.gml-extra"
      },
      {
         "match": "(?i)\\b(liaronce_test)\\b",   //This is constants
         "name": "constant.gml-extra"
      },
      {
         "match": "(?i)\\b(liaronce_test)\\b",   //This is variables
         "name": "support.variable.gml-extra"
      }
   ]
}
```

 - Reloading Visual Studio Code