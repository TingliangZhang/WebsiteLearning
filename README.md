# WebsiteLearning
网页搭建学习



## 框架选择

[React – A JavaScript library for building user interfaces](https://reactjs.org/)

[Vue.js](https://cn.vuejs.org/index.html)

[Angular](https://angular.io/)



[Django](https://www.djangoproject.com/) - The Web framework for perfectionists with deadlines



## 数据库选择

SQL(Relational Database) or NoSQL(Non-Relational Database)

[What is a database in under 4 minutes](https://www.youtube.com/watch?v=Tk1t3WKK-ZY)

### NoSQL

[MongoDB](https://www.mongodb.com)

[Apache CouchDB](http://couchdb.apache.org/)

[Amazon DynamoDB | NoSQL Key-Value Database](https://aws.amazon.com/dynamodb/)

### SQL

[PostgreSQL: The World's Most Advanced Open Source Relational Database](https://www.postgresql.org/)

[SQL Server 2019 | Microsoft](https://www.microsoft.com/en-us/sql-server/sql-server-2019)

[MySQL](https://www.mysql.com/)



## React入门

[Tutorial: Intro to React](https://reactjs.org/tutorial/tutorial.html)

If you need to review JavaScript, we recommend reading [this guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript).

[Next.js](https://nextjs.org/) is a popular and lightweight framework for **static and server‑rendered applications** built with React. It includes **styling and routing solutions** out of the box, and assumes that you’re using [Node.js](https://nodejs.org/) as the server environment.

Learn Next.js from [its official guide](https://nextjs.org/learn/).



## 傻瓜式操作

[Free Website Builder | Create a Free Website | Wix.com](https://www.wix.com/)

[WordPress.com: Create a Free Website or Blog](https://wordpress.com/)



## 需求

实现

用户新Tag拿到手时候扫描Tag，数据库查询UID是否被注册用户绑定，并结合密钥验真。弹出注册或登录页面，如果已经登陆使用Cookie登录。

登陆后用户可以填写自己的个人信息，组织并选择这个名片能访问的个人信息，生成类似于个人主页门户的页面，预览并确认后，数据库记录数据和顺序。

收到Tag的另一用户自行NFC读取到特定网址+ID+密钥的时候，能弹出社交信息分享页面。

如果是可复用的，可以设置页面有效期，在一段时间后密钥更换，使用原链接和密钥地址无法访问或只能访问原先定义的信息。

如果是扫码，逻辑基本一致，针对手机太老没有NFC功能的提供二维码分享功能，但是是阉割版，无法更改二维码的信息，故编辑信息不具有保密性，需要在第一次编辑的时候提醒用户。微信扫码提示按右上角由浏览器打开。

准备包含的社交软件有：

1. 微信
2. QQ
3. TIM
4. Telegram
5. 微博
6. Linkedin
7. Instagram
8. 钉钉
9. 飞书
10. 哔哩哔哩
11. 个人网站
12. 斗鱼直播
13. Steam
14. Skype
15. Facebook
16. Twitter
17. Github
18. Slack
19. Snapchat
20. Reddit
21. Twitch
22. Google+
23. Pinterest
24. Dribbble
25. Flickr
26. Tumblr
27. 作品集网站叫啥我忘记了