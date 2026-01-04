#火焰中的旗
1.文件是一个巨大的base64编码数据，解码base64 -d log.txt > log.bin
2.file log.bin ,是一个图片文件，改后缀打开
3.提取图片上的16进制字符串，tesseract log.jpg stdout
4.解码成文本，echo -n “” | xxd -r -p