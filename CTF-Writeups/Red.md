binwalk -e 文件名：检查是否附加文件  
zsteg自动扫描图片
采用LSB隐写，放在绿色通道的最低位隐写flag


zsteg red.png   
meta Poem           .. text: "Crimson heart, vibrant and bold,\nHearts flutter at your sight.\nEvenings glow softly red,\nCherries burst with sweet life.\nKisses linger with your warmth.\nLove deep as merlot.\nScarlet leaves falling softly,\nBold in every stroke."                                                        
b1,rgba,lsb,xy      .. text: "cGljb0NURntyM2RfMXNfdGgzX3VsdDFtNHQzX2N1cjNfZjByXzU0ZG4zNTVffQ==cGljb0NURntyM2RfMXNfdGgzX3VsdDFtNHQzX2N1cjNfZjByXzU0ZG4zNTVffQ==cGljb0NURntyM2RfMXNfdGgzX3VsdDFtNHQzX2N1cjNfZjByXzU0ZG4zNTVffQ==cGljb0NURntyM2RfMXNfdGgzX3VsdDFtNHQzX2N1cjNfZjByXzU0ZG4zNTVffQ=="                                 
b1,rgba,msb,xy      .. file: OpenPGP Public Key  
b2,g,lsb,xy         .. text: "ET@UETPETUUT@TUUTD@PDUDDDPE"  
b2,rgb,lsb,xy       .. file: OpenPGP Secret Key  
b2,bgr,msb,xy       .. file: OpenPGP Public Key  
b2,rgba,lsb,xy      .. file: OpenPGP Secret Key  
b2,rgba,msb,xy      .. text: "CIkiiiII"  
b2,abgr,lsb,xy      .. file: OpenPGP Secret Key  
b2,abgr,msb,xy      .. text: "iiiaakikk"  
b3,rgba,msb,xy      .. text: "#wb#wp#7p"  
b3,abgr,msb,xy      .. text: "7r'wb#7p"  
b4,b,lsb,xy         .. file: 0421 Alliant compact executable not stripped  


b1:最低位，胶片上每个点最后一个像素细节  
rgba:同时看红绿蓝透明这四张胶片  
lsb:最低有效位  
xy:从左到右从上到下扫描图片  
