# magapp-jssdk
MagAPP JSSDK npm版本

项目中的ts文件由通过官方开发者文档生成，若有遗漏可提交issue。

## 注意
本仓库将MagAPP官方的sdk下载到仓库中略做改动，并加上了TS的描述文件。

## 对官方改动
将jssdk下载到index.js中。在头部增加
``` js
/*!
  * magapp-jssdk v1.3.2
  * (c) 2018 MagAPP Inc.
  */
let mag;
```
在尾部增加
``` js
export default mag;
```
未改动官方其他任何方法。

