# CmlPHP V2.x API项目示例

本项目为基于CmlPHP V2.x开发的一个api项目示例。包含了api开发的两个接口示例以及根据代码注释自动生成文档的示例。

还不知道什么是CmlPHP?[点这里了解](http://cmlphp.com/ "CmlPHP")

> 下载本示例之前请先下载 [CmlPHPV2.x 项目推荐目录骨架](https://github.com/linhecheng/cmlphp-demo).然后将本项目放到projxxx/Application下。

[视频教程](http://v.youku.com/v_show/id_XMTQwNTc4MDk2OA==.html)

---

主要的配置文件在 `projxxx/Application/api/Config/api.php中`

查看配置,我们看到在配置中我们配置了V1版本有注册、登录两个接口。

我们来看下其中的注册接口
![](http://o7v4k1oiv.bkt.clouddn.com/apidemo1.png)

我们看到了注释中的接口描述、参数、请求示例、返回成功/失败示例。

请修改`api.php`中相应的`lookup_doc_key`。
打开文档查看地址http://xxx/index.php/api/Bootstrap/doc/key/lookup_doc_key

![](http://o7v4k1oiv.bkt.clouddn.com/apidemo3.png)
我们看到了自动生成的接口文档。很简单吧。动起来吧。

开发过程中的目录及程序接口请参考 [CmlPHP V2.x开发手册](http://doc.cmlphp.com)

