# 邓小平语音工作室 v0.2.0

蓝白版式，文字与歌曲入口并排，播放器和导出集中在下方。 右上角语言菜单列出全球使用人数最多的 20 种语言，普通话可选简体或繁体。切换语言会保留草稿。

[下载 Windows 安装包](https://github.com/2009Wu/deng-xiaoping-voice/releases/latest/download/Deng-Xiaoping-Voice-Studio-Windows.zip) · [Hugging Face 项目页](https://huggingface.co/spaces/Little-Wang/deng-xiaoping-voice)

Windows 启动时会自动检查更新，可在「更新与帮助」中关闭。v0.1.0 用户需先下载新版 ZIP。

Windows 10 / 11，NVIDIA 显卡，建议至少 6 GB 显存。首次安装预留 30 GB 空间。

1. 完整解压安装包，双击 Start Deng Voice Studio.exe。
2. 首次点击“安装并打开工作室”。依赖和模型下载完成后，工作室在浏览器中打开。
3. 输入文字或上传有原唱的音频／视频，点击“一键生成”。也可先试听一小段歌曲。
4. 生成结果自动保存到“文档 / Voice Studio作品 / 邓小平语音工作室”。使用期间保持启动器开启。

固定音色参考来自 1974 年联合国大会讲话。所有生成结果均为 AI 合成。

代码采用 GPL-3.0。参考音频和图标分别见 [来源说明](THIRD_PARTY_NOTICES.md)。本机已验证启动、输出界面和安装包解压，实际生成效果尚待试听。

Windows 启动器会自动从 FLAC 恢复参考 WAV。直接运行源码前可执行 `python windows/restore_references.py`。

[给小王买杯咖啡](https://ko-fi.com/little_wang)

![新版生成界面](docs/studio-preview.jpg)

## 提交反馈

欢迎分享功能建议、程序问题，以及配音或翻唱质量上的意见。[打开反馈表单](https://github.com/2009Wu/custom-voice-studio/issues/new?template=studio-feedback.yml)（需登录 GitHub，内容公开）。
