# Arduino
Arduinoに対してコマンドラインから
- コンパイル
- 書き込み
- シリアル通信

ができるようにするものである。

#####Environment
OS : Ubuntu 14.04 LTS

#####Links
[Emacs Arduino Support](http://www.emacswiki.org/emacs/ArduinoSupport)
[github : Arduino-Makefile](https://github.com/sudar/Arduino-Makefile)


##Install
git cloneでダウンロードしてください。
```
git clone https://github.com/RyodoTanaka/Arduino/
```

##Usage
1. .inoファイルの編集
2. Makefileの編集
3. コンパイル
 - コンパイルのみ
 ```
 make
 ```
 - 書き込み
 ```
 make upload
 ```
 - シリアル通信
 ```
 make monitor
 ```
