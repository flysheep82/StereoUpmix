# StereoUpmix
This is a python software to upmix 2.0 stereo audio to 5.1 or 7.1 FLAC, AC3 or EAC3.
It is assembled by Gemini from below projects. Unzip and double click run_remix.bat to launch the GUI.

https://huggingface.co/jarredou/BS-ROFO-SW-Fixed

https://github.com/ZFTurbo/Music-Source-Separation-Training

https://github.com/HG3112/md71

本人完全不会编程。这是通过Gemini问答方式开发的小工具。可以把2.0的音频文件混音成5.1或者7.1音频。
思路借鉴了CHEN-Technology大神的https://github.com/CHEN-Technology/2TO5.1-OR-2TO7.1/

主要增加了GUI和换成FLAC作为中间转存文件。

使用方式很简单，下载两个压缩包解压后，直接双击run_remix.bat。等待GUI窗口弹出即可。所有需要运行环境都已经打包好。由于没有深度测试过，建议解压位置不要防止在太深的有特殊字符或者中文的目录下。

程序支持批量导入导出。显卡加速只支持N卡。混音后会在temp文件夹里留存一些AI模型分离出的临时音轨文件。如果文件夹由于临时文件太多变得太大，可以点击clean temp files，或者自己手动删除temp文件夹。
