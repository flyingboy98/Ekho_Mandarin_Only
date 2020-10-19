# Ekho_Mandarin_Only_For_Raspberry_Pi
余音(Ekho)简化版，只包含汉语普通话，可用于树莓派。



使用方法：

cd /home/pi/Documents

wget -O yy.zip https://github.com/flyingboy98/Ekho_Mandarin_Only/raw/main/yy.zip

unzip yy.zip

sudo rm yy.zip

python3 /home/pi/Documents/yy/bin/zhspeak.py "余音简化版"



如果改变安装文件夹，需要修改zhspeak.py中第88行的绝对路径:

os.system("mplayer /home/pi/Documents/yy/zhspeak-data/zh_ogg/tem.ogg")
