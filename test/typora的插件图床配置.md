**安装目录为

```
C:\Users\alone\AppData\Roaming\Typora\picgo\win64
```

进入安装目录后cmd运行 **

```
picgo set uploader
```

**来进入交互式命令行，配置成功后会自动生成配置文件，无需复制粘贴！**

同时，填好图床配置之后，请务必通过 

```
picgo use uploader
```

 `选择当前要 使用的 `图床。

配置文件目录为

```
C:\Users\alone\.picgo
```

手动更改配置文件

```
{
  "picBed": {
    "current": "tcyun",
    "upyun": {
      "bucket": "dreamstarcloud",
      "operator": "aloneicymoon",
      "password": "EqpNhWhwHBDTjOwfNLOZtvIQjh1xr4CM",
      "url": "dreamstarcloud.test.upcdn.net",
      "options": "",
      "path": "picgo/"
    },
    "aliyun": {
      "accessKeyId": "LTAI5tEUa34wfGFZeybFnNKA",
      "accessKeySecret": "8ipFR0o6juxYgah1ffXVsTIrnWffgj",
      "bucket": "dreamstarcloud",
      "area": "oss-cn-hangzhou",
      "path": "picgo/",
      "customUrl": "dreamstarcloud.oss-cn-hangzhou.aliyuncs.com",
      "options": ""
    },
    "uploader": "tcyun",
    "transformer": "path",
    "tcyun": {
      "secretId": "AKIDVoreBRRBj00jBMGtGMBj00jBNIwINHuF",
      "secretKey": "5uSjjTw822lDNGtFK7euta0A2dx1oKZY",
      "bucket": "dreamstar-1301645405",
      "appId": "1301645405",
      "area": "ap-chengdu",
      "path": "picgo/",
      "customUrl": "dreamstar-1301645405.cos.ap-chengdu.myqcloud.com",
      "version": "v5"
    }
  },
  "picgoPlugins": {
    "picgo-plugin-smms-user": true
  }
}
```

