[中文](README.md) | [English](README-en.md) 

# ComfyUI 的 Kokoro 文本转语音节点

![image](https://github.com/billwuhao/ComfyUI_KokoroTTS_MW/blob/master/images/2025-02-17_01-39-16.png)

## 特性

- 高质量文本转语音
- 多种音色可选
- 支持多种语言的文本
- 与ComfyUI工作流轻松集成

## 支持语言

'a' => American English 美式英语

'b' => British English 英语

'j' => Japanese 日语

'z' => Chinese 中文

## 可用音色

"a": 

["af_alloy", "af_aoede", "af_bella", "af_heart", "af_jessica", 
   "af_kore", "af_nicole", "af_nova", "af_river", "af_sarah", 
   "af_sky", "am_adam", "am_echo", "am_eric", "am_fenrir", 
   "am_liam", "am_michael", "am_onyx", "am_puck", "am_santa"]

"b": 

["bf_alice", "bf_emma", "bf_isabella", "bf_lily", "bm_daniel",
   "bm_fable", "bm_george", "bm_lewis"]

"j": 

["jf_alpha", "jf_gongitsune", "jf_nezumi", "jf_tebukuro", "jm_kumo"]

"z": 

["zf_xiaobei", "zf_xiaoni", "zf_xiaoxiao", "zf_xiaoyi",
   "zm_yunjian", "zm_yunxi", "zm_yunxia", "zm_yunyang"]

## 模型和音色下载

1. 模型将自动下载到 `C:\Users\xxx\.cache\huggingface\hub\models--hexgrad--Kokoro-82M`
2. 音色请 [这里](https://huggingface.co/hexgrad/Kokoro-82M/tree/main/voices) 手动下载放到 `ComfyUI\models\Kokorotts\voices` 路径下

## 感谢

- [Kokoro](https://github.com/hexgrad/kokoro)