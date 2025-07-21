# Obf-BPB-Panel
BPB混淆代码

未经混淆或使用人数过多的BPB拷贝 很容易让Cloudflare检测到并报1101错误。已部署的BPB脚本，非必要不建议更新。

如果想混淆一个自己独有的版本，可以拿原 worker.js 文件，拷贝或替换到根目录下，就会生成新的 _worker.js。

worker.js：原 BPB 代码，无论混淆与否。

_worker.js：混淆后的个人专属 BPB 代码。
