<p align="center">
  <img width="16%" align="center" src=".github/icon/shortcuts.png" alt="logo">
</p>
  <h1 align="center">
  Shortcuts Hub
</h1>
<p align="center">
  Apple Shortcuts 广场
</p>

分享你的 Apple 快捷指令并在这里提交。

# 如何加入？
1. fork 本仓库
2. `如果你从未贡献过本仓库` 在 shortcuts 文件夹中新建一个以你 Github 用户名为名的文件夹,如 Detritalw  
3. 在刚刚创建的文件夹中新建一个以`你的项目的名称`为名的文件夹  
4. 在刚刚创建的项目文件夹中上传 `.shortcuts 文件`  
5. 在刚刚创建的项目文件夹中新建 `shortcuts.json` , 并按照下列示例填写

```json
{
    "name":"Sleepy-Client",//项目名称
    "describe":"用快捷指令实现的 Sleepy 客户端支持 Apple Watch, iPhone, iPad, mac...",//项目描述
    "author":"Detritalw",//作者 Github 用户名
    "date":"2025-03-28",//上传时间
    "repository":{//存储库，如果没有可以不填，后续可能会用这个来自动更新
        "github":"https://github.com/Detritalw/Sleepy-Client-Shortcuts"
    }
}
```
> 由于是 json , 所以打乱也没关系（？

6. 向本仓库提交拉取请求