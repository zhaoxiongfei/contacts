contacts
========

一个多用户的通讯录

## 一期需求 (三天之内完成)
基于restify 和 sequelize ，使用mysql数据库完成一个多用户的通讯录的 restapi开发。

POST: /users 注册用户接口
GET: /users 获取系统用户列表接口

POST: /sessions 登陆接口
DELETE: /sessions/:id 退出接口

POST: /users/:userId/contacts 给某个用户添加一条通讯录记录
GET: /users/:userId/contacts 获取某个用户的通讯录

GET: /contacts/:id 获取某条通讯录记录
PATCH/PUT: /contacts/:id 修改某条记录
DELETE: /contacts/:id 删除某条记录


### 资源描述
<pre>user</pre>
```js
{
  "id": 999, // 用户ID
  "name": "xxx", // 用户名称
  "email": "xxx@xxx.xx", //email
}
```
<pre>contact</pre>
```js
{
  "id": 999, // 记录id
  "name": "xxx", // 联系人名称
  "tel": "15911016875", //联系人电话
}
```
  
## 二期需求（5天之内完成)
利用 kiwi 来制作这个通讯录的界面，kiwi地址如下
<pre>https://github.com/open-node/kiwi</pre>

kiwi clone回去以后，npm install，之后grunt就可以构建了。
  
  
  
  
  
  
  
  
  
  
