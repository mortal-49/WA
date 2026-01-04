#服务器端模版注入  
1.  
{{7*7}} → 如果页面显示 49，则存在SSTI（Jinja2/Twig）  
${7*7} → 如果显示 49，可能是Freemarker  
<%= 7*7 %> → 可能是ERB  
${{7*7}} → 可能是AngularJS  
2.输入{{7*'7'}}返回7777777，确认是Jinja2 SSTI  
3.  
获取可用子类列表  
 os._wrap_close 或 subprocess.Popen 类  
4.输入命令列出目录读取flag  
###脑壳疼，没搞懂，不会！！！  

