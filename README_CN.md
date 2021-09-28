![screenshot](./screenshot.png)

Processing 4.0 黑色主题
===================

Processing4.0软件的黑色主题模式（护眼模式）

| Processing历史版本 | 黑色主题 |
| :---- | :---- |
| 3.0 | [https://github.com/jeffThompson/DarkProcessingTheme_3.0](https://github.com/jeffThompson/DarkProcessingTheme_3.0) |
| 2.0 | [https://github.com/jeffThompson/DarkProcessingTheme_2.0](https://github.com/jeffThompson/DarkProcessingTheme_2.0) |
| 1.5 | [https://github.com/jeffThompson/DarkProcessingTheme](https://github.com/jeffThompson/DarkProcessingTheme) |


## 内容描述

* `status`文件夹: 更新了显示错误消息的底部栏的 png 文件，主要是为了清理颜色并摆脱渐变
* `footer`文件夹: Processing软件底部栏的 png 文件
* `toolbar`文件夹: Processing软件的顶部栏的 png 文件
* `theme.txt`: 主题色的各种配置
* `README.md`: 默认的英文说明文档  
* `README_CN.md`: 中文说明文档  
* `screenshot.png`: 黑色主题截图

## 安装

在安装任何东西之前，一定要制作一份原件的副本，只需将文件从此存储库复制到适当的位置即可，万一你不喜欢这样的更改或者出了什么问题，还能替换还原回去（如果确实有问题，您可以再次重新安装 Processing IDE）。

* **Mac:** 转到`Applications`文件夹中的 Processing 应用程序，右键单击它并选择`Show Package Contents`(显示包内容）并导航到`Java/lib`。 或者，只需从终端转到`~/Applications/Processing.app/Contents/Java/lib`。
* **Windows:** `%HomeDrive%\processing64\processing-3.2.1\lib\`
* **Linux:** 转到安装 Processing 的目录的 `lib` 文件夹，可能是 `~/processing-{{version-number}}`。 用这个 repo 中的文件夹替换原来的 `footer`、`status` 和 `toolbar` 文件夹，并添加 `theme.txt` 文件。

## 代码高亮色主题

在主题配置文件`theme.txt`中，我们使用了经典的`monokai`主题色。

```sh
# monokai
editor.token.function1.style=#66D9EF,plain
editor.token.function2.style=#66D9EF,plain
editor.token.function3.style=#F92672,plain
editor.token.function4.style=#A6E22E,bold
editor.token.keyword1.style=#66D9EF,bold
editor.token.keyword2.style=#66D9EF,bold
editor.token.keyword3.style=#66D9EF,bold
editor.token.keyword4.style=#F92672,plain
editor.token.keyword5.style=#66D9EF,bold
editor.token.keyword6.style=#F92672,plain
editor.token.literal1.style=#E6DB74,plain
editor.token.literal2.style=#AE81FF,plain
editor.token.operator.style=#F92672,plain
editor.token.label.style=#999999,bold
editor.token.comment1.style=#75715E,plain
editor.token.comment2.style=#75715E,plain
editor.token.invalid.style=#F92672,bold#
```


----------------

遵循创作共用许可协议: [Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/)