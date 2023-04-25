
`manifest.json`是Chrome浏览器扩展的配置文件，指明了扩展的各类信息。

基础配置：
```json5
{
  "manifest_version": 3,
  "name": "Chapter 01",
  "version": "1.0",
  "description": "Chapter 01",
  "author": "ijunfu",
  "icons": {
    "16": "icons/16.png",
    "48": "icons/48.png",
    "128": "icons/128.png"
  }
}
```

+ `manifest_version`指定清单文件格式的版本，目前版本为`3`。 Chrome version 18+ 使用 `2`, Chrome version 88+ 使用 `3`。
+ `name`指定插件的名称
+ `version`指定插件的版本号
+ `description`简洁的介绍插件
+ `author`指定开发者
+ `icons`指定插件显示的图标