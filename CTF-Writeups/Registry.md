#谜语登记册
#解题思路
1.PDF文件混乱，无有效信息，下载文件用exiftool查看文件元数据
2.发现author字段base64编码字符串
3.解码echo | base64 -d获得flag
