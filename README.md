# README
# 代码注释助手

手动一条一条为代码添加注释太麻烦？让代码注释助手来帮你！使用此python脚本一键为你长长的代码生成中文注释。

·此脚本可以自动为你的代码添加中文注释。

·解决了chatGPT、new Bing的输入长度限制问题。

·支持几乎所有编程语言。

·支持修改prompt以实现更多可能性，例如为代码添加任意语言注释、翻译长篇文章、概括长篇文章等等。

**注意**：要运行这个脚本，你需要确保你的网络能连接到openai API。

此脚本为开源脚本，可以[点这里](https://github.com/RaycarlLei/Add-comments-to-your-code-Chinese/blob/main/src.py)查看源代码。



## 使用指南

1. 点击[此链接](https://github.com/RaycarlLei/Add-comments-to-your-code-Chinese/archive/refs/heads/main.zip)下载项目压缩包。
2. 解压项目压缩包。打开解压后的文件夹，找到auto_comment_GUI_github.zip
3. 解压 auto_comment_GUI_github.zip
4. 进入解压后的文件目录 auto_comment_GUI_github\dist\run 
5. 找到run.exe，双击运行。
6. 输入你的OpenAI API密钥。如果你还没有OpenAI API，请参考[获取openai API key](https://github.com/RaycarlLei/Add-comments-to-your-code-Chinese/blob/main/README.md#%E8%8E%B7%E5%8F%96openai-api-key)。
7. 请确保你的输入代码文件中没有超过1000个字符的行，建议将代码保存入.txt文件中。
8. 选择输入和输出文件的路径，以及打开文件时使用的编码方式。
9. 点击'运行脚本'以开始注释过程。
10. 请耐心等待。
11. 运行完成后，输出文件将以.txt文件格式保存并且自动打开。



## 特性

- 图形用户界面，便于交互。
- 将大文件分割以分段处理，避免token数超过限制。
- 将代码发送到OpenAI的API以生成注释。
- 处理错误和异常。
- 任务进度条。
- 测量每个操作所花费的时间。




## 获取openai API key

1. 如果你还没有API，你可以在[此链接](https://platform.openai.com/account/api-keys)获取你的API。

2. 注册或者登录后，点击右边的View API keys，然后点击 Create new secret key，给Key起一个名字，然后即可生成新的API Key。

3. 注意生成后立即复制保存这个API Key，这个Key只显示一次，如果忘记保存就需要重新创建。

4. 按照[使用指南](https://github.com/RaycarlLei/Add-comments-to-your-code-Chinese/blob/main/README.md#%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)运行脚本，在“在下方输入你的OpenAI API Key。”栏输入的API Key。或者将API Key保存到run文件夹里的api_key.txt文件中。

