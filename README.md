# kadai1
ロボットシステム学の課題1

# 概要
講義内で使用したデバイスドライバを実際に書きました。

# 環境
Ubuntu 18.04

# 使用したもの
Raspberry Pi 4 

ブレッドボード

LED 青 

220Ω抵抗器 

# インストール・実行
     $ git clone https://github.com/mrks333/kadai1.git 
     $ cd myled
     $ make
     $ sudo insmod myled.ko
     $ sudo chmod 66 /dev/myled0
     $ echo 1 > /dev/myled0
     $ echo 0 > /dev/myled0

# 動画
https://youtu.be/yT8UOSn05oI

# ライセンス
GNU General Public License v3.0 　
