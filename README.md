# Obf-BPB-Panel
BPB Panel 混淆代码

未经混淆或使用人数过多的BPB拷贝 很容易让Cloudflare检测到并报1101错误。已部署的BPB脚本，非必要不建议更新。

如果想混淆一个自己独有的BPB拷贝，可以拿原 worker.js 文件，复制或替换到根目录下，就会生成新的 _worker.js。


worker.js：原作者BPB代码，无论混淆与否。

_worker.js：混淆后的个人专属 BPB 代码。


使用方法：

每次在你更新 worker.js 文件的时候，就会触发 自动重新生成 _worker.js 文件。

也可以随时手动强制重新生成新文件，方法是：

在仓库的 Actions 标签页，在左侧选择 Auto Obfuscate Worker，在中间偏右 会看到一个 "Run workflow" 的按钮。

点击它，再点击main，就可以强制运行一次工作流，从而在你需要的时候 再生成重新混淆过的 _worker.js。


BPB Panel 💦 的源文件及具体操作说明请访问作者仓库：

https://github.com/bia-pain-bache/BPB-Worker-Panel?tab=readme-ov-file


BPB Panel Obfuscation Code
Unobfuscated copies of BPB or copies used by too many people can easily be detected by Cloudflare, 

resulting in a 1101 error. It is not recommended to update already deployed BPB scripts unless necessary.

If you want to obfuscate your own unique copy of BPB, you can take the original worker.js file, 

copy or replace it in the root directory, and a new _worker.js will be generated.


worker.js: The original author's BPB code, regardless of whether it is obfuscated or not.
_worker.js: The obfuscated personal exclusive BPB code.


Usage:
Every time you update the worker.js file, it will trigger the automatic regeneration of the _worker.js file.

You can also manually force the regeneration of a new file at any time by:

In the repository's "Actions" tab, select "Auto Obfuscate Worker" on the left side, and on the middle-right, 

you will see a "Run workflow" button.Click it, then click "main", to forcefully run the workflow once, 

generating the re-obfuscated _worker.js whenever you need it.

For source files and specific operation instructions for BPB Panel 💦, please visit the author's repository:

https://github.com/bia-pain-bache/BPB-Worker-Panel?tab=readme-ov-file
