# index-tts-OneClick
index-tts声音克隆软件免安装一键启动整合包

![](https://raw.githubusercontent.com/aidayang/index-tts-OneClick/refs/heads/main/indextts.webp)

## index-tts声音克隆软件介绍
工业级可控高效零样本文本转语音系统

近年来，基于大型语言模型（LLM）的文语转换（TTS）系统凭借其高自然度和强大的零样本语音克隆能力逐渐成为业界主流。我们推出了IndexTTS系统，该系统主要基于XTTS和Tortoise模型，并增加了一些新颖的改进，具体来说，针对中文场景，我们采用了汉字和拼音相结合的混合建模方法，使多音字和长尾字的发音可控。我们还对矢量量化（VQ）和有限标量量化（FSQ）对声学语音token的码本利用率进行了对比分析。为了进一步提升语音克隆的效果和稳定性，我们引入了基于一致性的语音条件编码器，并用BigVGAN2替换了音码解码器。与XTTS相比，它在自然度、内容一致性和零样本语音克隆方面均取得了显著的提升。与开源中流行的语音合成系统（例如 Fish-Speech、CosyVoice2、FireRedTTS 和 F5-TTS）相比，IndexTTS 的训练过程相对简单，使用方式更可控，推理速度更快，性能也远超这些系统。

## index-tts整合包使用说明

首先把网盘内的软件压缩包下载到本地电脑上并解压，然后双击启动软件.exe，运行，打开webui界面。

软件界面很简单，功能和操作一目了然。

1、上传参考音频。2、输入待合成文本。3、点击按钮生成语音。

推理模式有两种，一个是普通推理，另一个是今天刚更新的批次推理。批次推理更适合长句，在长文本语音合成的时候提高了性能和速度。但是有时候感觉批次推理比普通推理要慢很多，这个具体可以自行测试体验。

简单用了用感觉index-tts对显存要求也不高，不考虑速度的话，2G显存或许也能带动。而且声音音色克隆的更接近原声，相比其它之前分享过的那些软件，效果还是好不少的。

合成的语音也比较有情感，很自然，并没有很机械的感觉。

虽然对长语音合成进行了优化，但是像这类本地合成语音的软件，尽量还是不要一次性合成太长文本。

视频教程及效果演示：https://www.youtube.com/watch?v=mvYW_oVzwtA

## 注意事项
整合包只支持Windows 10或11

软件运行路径中不要有非英文字符和空格

需要英伟达独显，软件配置要求不高但未测试最低配置

## 声音克隆软件index-tts整合包下载链接
https://pan.quark.cn/s/f411d86fc821

https://pan.baidu.com/s/1ulLi6lAoDggL1nSK5n8ENA?pwd=gc7j

## 项目链接
https://github.com/index-tts/index-tts
