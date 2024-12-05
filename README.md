
**备注**
该补丁只适用64位的谷歌浏览器,32位不支持!!


1. 复制 chrome.exe, 并命名为 chrome1.exe
2. 复制 chrome1.hook.dll 到 chrome1.exe 同目录
3. winmm.dll 放在版本号目录, 例如 129.0.6668.59\winmm.dll
4. 启动 chrome1.exe

文件位置示例如下

```

chrome1.exe
└─129.0.6668.59
    └─winmm.dll 

```


实现功能:

1.集成便携功能,用户数据放在chrome.exe同目录(UserData),可打包带走

2.可直访谷歌系列网站,比如 谷歌搜索, Youtube  等

