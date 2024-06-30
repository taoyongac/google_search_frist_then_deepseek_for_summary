# 学术搜索助手

欢迎使用学术搜索助手! 这个工具旨在帮助科研工作者从Google搜索结果中快速提取所需的信息。

## 功能特点

* 根据您提供的关键词进行谷歌学术搜索
* DeepSeek AI根据您的科学问题有目的地总结排名前20的检索结果页面内容
* 私密邀请制,请勿外传
* 使用DeepSeek API,成本为每篇文献一分钱人民币,使用前需填入自己的DeepSeek API

## 使用方法

1. 复制`code`文件中的代码到本地,保存为`app.py`
2. 安装必要的Python包:
   pip install requests json os re urllib asyncio playwright logging beautifulsoup4 fake_useragent PyMuPDF openai flask flask_socketio random

3.申请DeepSeek API并充值

4.运行app.py

5.打开浏览器,访问http://127.0.0.1:5000

6.在搜索查询输入框中输入您的搜索关键词(请使用英文)

7.在问题输入框中输入您的问题(可以使用英文或中文)

8.DeepSeek适合用于初筛,请注意提问方式

9.建议问是否包含您需要的信息,而非具体问题

10.例如:"是否包含影响lentivirus包装效率的信息?"

11.初筛找到相关文献后,可以使用Claude回答具体问题

12.点击"搜索和抓取"按钮
抓取开始后,页面可能暂时没有反应,请耐心等待结果逐个显示

13.某些网站可能需要更长的抓取时间
如果超过5分钟没有任何结果显示,请尝试更换检索关键词

14。抓取完成后,结果将显示在页面下方
请勿同时进行多个搜索,以免结果混淆
单次检索最终会显示10-20条结果

15.抓取完成时,网页末尾会显示"Deepseek results are complete."



注意事项

使用前请确保已申请DeepSeek API并充值
如有任何问题或建议,欢迎随时联系我们

祝您使用愉快,科研顺利!

Updated on 2024-06-26 @YNU
Taolab



Academic Search Assistant
Welcome to the Academic Search Assistant! This tool is designed to help researchers quickly extract desired information from Google search results.
Features

Perform Google Scholar searches based on your provided keywords
DeepSeek AI purposefully summarizes the content of the top 20 search result pages according to your scientific question
Private invitation only, please do not share
Uses DeepSeek API, with a cost of one cent (RMB) per paper, please enter your own DeepSeek API before use

How to Use

1.Copy the code file to your local machine and save it as app.py

2.Install the necessary Python packages:
pip install requests json os re urllib asyncio playwright logging beautifulsoup4 fake_useragent PyMuPDF openai flask flask_socketio random

3.Apply for a DeepSeek API and top up your account

4.Run app.py

5.Open your browser and visit http://127.0.0.1:5000

6.Enter your search keywords in the search query input box (please use English)

7.Enter your question in the question input box (you can use English or Chinese)

8.DeepSeek is suitable for initial screening, please pay attention to the questioning method

9.It is recommended to ask whether it contains the information you need, rather than specific questions

For example: "Does it contain information that affects the packaging efficiency of lentivirus?"
After finding relevant papers in the initial screening, you can use Claude to answer specific questions

10.Click the "Search and Crawl" button

11.After the crawling starts, the page may temporarily have no response, please wait patiently for the results to appear one by one

12.Some websites may require a longer crawling time

13.If no results are displayed after more than 5 minutes, please try changing the search keywords

14.After the crawling is completed, the results will be displayed at the bottom of the page

15.Please do not perform multiple searches at the same time to avoid confusion of results

15.A single search will eventually display 10-20 results

16.When the crawling is completed, "Deepseek results are complete." will be displayed at the end of the webpage



Notes

Please make sure you have applied for a DeepSeek API and topped up your account before use
If you have any questions or suggestions, please feel free to contact us at any time

We wish you a pleasant experience and successful research!

Updated on 2024-06-26 @YNU
Taolab
