# StereoUpmix
This is a python software to upmix 2.0 stereo audio to 5.1 or 7.1 FLAC, AC3 or EAC3.
It is assembled by Gemini from below projects.

https://huggingface.co/jarredou/BS-ROFO-SW-Fixed

https://github.com/ZFTurbo/Music-Source-Separation-Training

https://github.com/HG3112/md71

本人完全不会编程。这是通过Gemini问答方式开发的小工具。可以把2.0的音频文件混音成5.1或者7.1音频。
思路借鉴了CHEN-Technology大神的https://github.com/CHEN-Technology/2TO5.1-OR-2TO7.1/

主要增加了GUI和换成FLAC作为中间转存文件。

使用方式很直观，支持批量导入导出。显卡加速只支持N卡。
