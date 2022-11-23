# Copy the snippets from the `html.json` and `javascript.json` into vs code
## File > Preferences > Configure User Snippets
## Search for `html.json` or `javascript.json` and paste the content in their respective file

![Add user snippets to vscode](https://media.giphy.com/media/IYyX02GYXZiksrbg5F/giphy.gif)

# Add snippets
**Create a json file with your snippets, name it `[language].json` mention them like in the below format**

```
"Print to console": {
  "prefix": "log",
  "body": [
    "console.log('$1');",
    "$2"
  ],
  "description": "Log output to console"
 }
```

[docs](https://code.visualstudio.com/docs/editor/userdefinedsnippets)
