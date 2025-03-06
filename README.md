# Pikpak-Verification-Code

短效邮箱一键提取PikPak验证码

## 在线测试网站：

https://code.kiteyuan.info/

## 使用方法：

```python
# 设置客户端 ID 和邮箱信息
client_id = ""  # 替换为你的 client_id
email = ""  # 替换为你的邮箱
refresh_token = ""  # 替换为你的 refresh_token
```
对比源代码，新增前端以及自动识别功能
![image](https://github.com/user-attachments/assets/45cdc15b-c92d-4e34-9716-b58de3bfc33d)


由于微软邮箱新机制，闪邮箱提供了refresh_token为用户提供登录邮箱的服务：[邮箱批发|-闪邮箱 (shanyouxiang.com)](https://shanyouxiang.com/)

```
闪邮箱提供的邮箱信息(此为举例参考):

[email] f73e6XXXlt1g@hotmail.com
[password] GDrQ2BSb8
[refresh_token] M.C523_BAY.0.U.-CgeAVXXbUEcbmFRjAS4UURT!ZNo0zq0Co!OvgroOByjwBHW8t3KloX6rdDAp2Ugpy4qIz84Xa2oyIPDUwvuEdb7xSYBPna74RRIGnOp5yp6D5Rb*GgdBEDxEZdEkCOdbwsC9JMLg6FlVnwgY6ubWIYKvULJmKOGKs*YXXXXXXXXXXXXXXXXX6QjBjjMY2ezziJDfga4TI*z9AMDW3*DSvSpGAkKtHG8bdFO4B7NItxLlMHiAEaVaOxSeqQuKAZVxy7N8kzKMcVNxTcjX1sbjfAZIznfKZXU*rQ4z64lTc6vMq*7hf774q3yFXQj2OMJoNXr6KUr9WcG!vrKHp1F5lVX!6defcYA8SgtXtMCFtrh3JrNsJJAAnUXNbXOgnGmwvdnZ5jxnYxegjVIn6!yv*tw$
[client_id] 8b4ba9dd-3ea5-4e5f-86f1-ddba2230dcf2
```

