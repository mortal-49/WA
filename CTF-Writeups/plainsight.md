#隐藏在平原  
1.查看文件元数据发现comment的base64编码字符串  
2.解码，得到steghide:cEF6endvcmQ=，是一个隐写术工具及密码  
3.提取隐写文件，steghide extract -sf img.jpg  

