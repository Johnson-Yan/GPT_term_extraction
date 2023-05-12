# GPT_term_extraction
EN:This is a project using selenium to form requests in bulk to extract terms in multiple docs.
ZH:本项目使用selenium包批量提取一个文件夹中所有文档的术语。

content _ summit: 
EN:The role of content _ summit is to enable selenium scripts on the GPT proxy website (https: Enter the prompt (prompt parameter) on https://chat.ninvfeng.xyz/)
and a list of content extracted from the document (content_list)
ZH:content _ summit脚本的作用是在GPT代理网站上启用selenium（网站为：https：//chat.ninvfeng.xyz/）,并提交提示(pompt参数)以及文本列表(content_list)

content _ summit:
EN:The role of content _ summit is responsible for splitting all the file content in the stored document folder into a list of specific lengths 
in order to submit the gpt web page to generate the term.
ZH:由于gpt网站只能最多支持4096个字符，因此content _ summit负责将存储的文档文件夹中的所有文件内容拆分为特定长度的列表以便提交gpt网页生成术语。

xzzz:
EN:xzzz is responsible for saving the terms collected on the web page to a specific xlsx document
ZH:xzzz负责将GPT网页上收集的术语保存到特定的xlsx文档

EN:Finally, modify the prompt in content _ summit and the folder address containing the document file to run.
ZH:最后,修改content_submit中的提示符和包含要运行的文档文件的文件夹地址，运行content_submit即可。

Screenshot of the program running process(程序运行截图)
1、Automated scripts beginning to control web page operation:(自动脚本开始控制网页)
![image](https://github.com/Johnson-Yan/GPT_term_extraction/assets/49894683/d5767d61-b498-4c35-92a9-6749a527d784)
2、Automate Script Entry of Request Text with Prompt:(将带有提示的文本列表输入文本框中并提交请求)
![image](https://github.com/Johnson-Yan/GPT_term_extraction/assets/49894683/6b4d7073-1385-4696-94dc-0fd8307ac004)
3、Target web page responds and outputs bilingual glossary list:(目标网页响应并生成双语词汇表)
![image](https://github.com/Johnson-Yan/GPT_term_extraction/assets/49894683/a0a9a8a5-7d5d-498f-a313-1757792a5c97)
![image](https://github.com/Johnson-Yan/GPT_term_extraction/assets/49894683/16ff13c2-1497-4860-af97-19e7a508dbc8)
4、Output printed in designated excel (输出结果保存在特定excel文件中)
![image](https://github.com/Johnson-Yan/GPT_term_extraction/assets/49894683/21849e53-33bf-4396-a5df-0aabc5c59fde)
