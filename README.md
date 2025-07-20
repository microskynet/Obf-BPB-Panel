# Obf-BPB-Panel
混淆代码

未经混淆的代码很容易让Cloudflare检测到并报1101错误。已部署的BPB脚本，非必要不建议更新。
如果确实想自己混淆，可以拉BPB库，按照workflows过程编译混淆。

新建一个 Github 仓库，在仓库里新建文件夹 .github/workflows，并在该文件夹中创建 Obfuscate.yml 文件，粘贴代码如下（也可以去我提供的 demoPanel示例仓库 中复制相关代码。）：

注意

仓库主分支名需为 main。

Obfuscate.yml 为你的代码仓库创建了一个 action，它将在每次 main 分支有 push 时、每天1点钟下载最新的 BPB 源代码，并执行混淆。

push Obfuscate.yml 到你的代码仓库。稍等片刻，仓库根目录中会出现两个新的文件：

origin.js：最新未加密的 BPB 源代码
_worker.js：混淆后的个人专属 BPB 代码
