# .NET-GhostWebshell

虚拟WebShell及内存马系列，来源自.NET安全矩阵星球，介绍.NET FrameWork 2.0及以上版本如何实现虚拟Webshell，这种高级的隐匿手法实现的WebShell适用范围很广具备很强的通用性，而且也是在渗透阶段外网打点后维持权限的一种不错的方法，优点在于当主机不重启的情况下删除内存注入文件后依然有效，攻击者通过自定义访问URL执行虚拟Webshell造成防守方溯源难度更大难以排查。笔者最近参考多方资料后，整理了如下课程，喜欢的朋友可关注我们的```知识星球```及```dot.Net安全矩阵```公众号，让我们一起探讨.NET安全。

---
# .NET安全矩阵星球

dotNet安全矩阵星球从创建以来一直聚焦于.NET领域的安全攻防技术，定位于高质量安全攻防星球社区，也得到了许多师傅们的支持和信任，通过星球深度连接入圈的师傅们，一起推动.NET安全高质量的向前发展。星球汇聚了各行业安全攻防技术大咖，并且每日分享.NET安全技术干货以及交流解答各类技术等问题，社区中发布很多高质量的.NET安全资源，可以说市面上很少见，都是干货。其中主题包括```.NET Tricks、漏洞分析、内存马、代码审计、预编译、反序列化、webshell免杀、命令执行、C#工具库```等等，后续还会倾力打造专刊、视频等配套学习资源，循序渐进的方式引导加深安全攻防技术提高以及岗位内推等等服务

![](zsxq2.jpg)

---
# .NET安全矩阵公众号

[ dotNet安全矩阵 ] —聚焦于微软.NET安全技术，曾原创连载 .NET十大反序列化漏洞课程 , 关注基于.NET衍生出的各种红蓝攻防对抗技术、分享内容不限于 .NET代码审计、 最新的.NET漏洞分析、反序列化漏洞研究、有趣的.NET安全Trick、.NET开源软件分享、. NET生态等热点话题，愿你能在这里学到实在的干货，共同推动.NET安全氛围卷起来

![](gzh.jpg)

---
# 更新日志

- 2022-09-27 
  - [.NET 实现虚拟WebShell第3课之IAuthorizationFilter](https://mp.weixin.qq.com/s?__biz=MzUyOTc3NTQ5MA==&mid=2247486460&idx=1&sn=b20b3bdfd4ba34c5ad554b548494b66d&chksm=fa5aa511cd2d2c076da72fecf29fb4ee3df64e5d851eba69b25c0d5f4a906387a8600aa7309c&token=135931015&lang=zh_CN#rd)
- 2022-09-09 
  - [.NET 实现虚拟WebShell第2课之AuthenticationFilter](https://mp.weixin.qq.com/s?__biz=MzUyOTc3NTQ5MA==&mid=2247486267&idx=1&sn=5a61d57a877f84bc3edc26c74803252a&chksm=fa5aa5d6cd2d2cc04e6c00e0ff1cfd02e6277381f2060a8572a9aaa61ef46b3bff37f174b677&token=263427717&lang=zh_CN#rd)
- 2022-08-24
  - [.NET 实现虚拟WebShell第1课之VirtualFile](https://mp.weixin.qq.com/s?__biz=MzUyOTc3NTQ5MA==&mid=2247486075&idx=1&sn=b7ee2d8f83784a41aaa5c33aaca30752&chksm=fa5aa496cd2d2d809e99ef12185356ecdd02a590458a0d146b5019123274f9688d606bc3510d&token=263427717&lang=zh_CN#rd)
