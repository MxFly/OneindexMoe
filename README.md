# OneIndex-mod
Onedrive Directory Index mod

## 功能：
不占用服务器空间，不走服务器流量，  直接列出 OneDrive 目录，文件直链下载。  

## mod特点
1.采用最新down/oneindex,萌化默认主题
2.无需手动设置定时任务，后台每10分钟自动刷新
3.docker全自动搭建
4.新增导航栏+支持修改背景图

## 安装运行

```
docker run -d -p 8181:80 --restart=always baiyuetribe/oneindex
```

## 特殊文件实现功能  
` README.md `、`HEAD.md` 、 `.password`特殊文件使用  

可以参考[https://github.com/donwa/oneindex/tree/files](https://github.com/donwa/oneindex/tree/files)  

**在文件夹底部添加说明:**  
>在 OneDrive 的文件夹中添加` README.md `文件，使用 Markdown 语法。  

**加密文件夹:**  
>在 OneDrive 的文件夹中添加`.password`文件，填入密码，密码不能为空。  

**直接输出网页:**  
>在 OneDrive 的文件夹中添加`index.html` 文件，程序会直接输出网页而不列目录。  
>配合 文件展示设置-直接输出 效果更佳。  


**上传文件:**  

推荐使用系统自带的OneDrive程序客户端或者使用RaiDrive进行文件的修改、上传、删除操作。

**文章来源** ：[佰阅部落](https://baiyue.one/archives/457.html)
