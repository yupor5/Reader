## 书源配置说明：

[必填] 标题：书源名（随意自定义，不要重复）

[必填] HOST: 书源Host地址（不要带最后的斜杠&#39;/&#39;）

[必填] 搜索URL: 搜索书籍的地址，关键字段用 %s 代替，支持GET/POST，暂不支持ssl(即仅开放https的站点)

[必填] 书籍名称 xpath：用于在搜索结果页面，解析书籍名称的xpath

[必填] 书籍主页 xpath：用于在搜索结果页面，解析书籍主页(章节列表页)URL的xpath

[选填] 作者名称 xpath：用于在搜索结果页面，解析作者名称的xpath，可以不填

[必填] 章节标题 xpath：解析小说主页章节名称的xpath

[必填] 章节URL xpath：解析每章节地址的xpath

[必填] 章节内容 xpath：解析每章小说主文本的xpath

[必填] 完结状态位置：用于判断书籍是否已经完结的配置，"搜索页"(如果不会配置，可以选择"无")



## 书籍配置样例：

下载 [bs.json](https://github.com/binbyu/Reader/blob/master/bs.json) 文件, (点击raw，然后右键保存即可。如果raw打不开，可以手动拷贝文件内容，保存到本地文件)

然后进入书源配置页面，选择"导入"即可使用

## 免责声明：

Reader为我个人开发的一款绿色、开源、免费的阅读器软件，主要用于小说阅读，为广大网络文学爱好者提供一种方便、快捷舒适的阅读体验。同时为广大软件开发者、爱好者提供学习参考。所有版权归作者所有。

对于在线书源功能，获取的内容均为第三方网络文学网站公开信息，不会对该网站进行大量和快速请求（每个章节URL只会请求一次，然后缓存到本地文件，只会缓存当前阅读相邻章节）、不会进行暴力破解、无病毒入侵。

当您搜索一本书的时，阅读器会将该书的书名以关键词的形式提交到各个第三方网络文学网站。各第三方网站返回的内容与阅读器无关，阅读器对其概不负责，亦不承担任何法律责任。任何通过使用阅读器链接到的第三方网页均系他人制作或提供，您可能从第三方网页上获得其他服务，阅读器对其合法性概不负责，亦不承担任何法律责任。第三方搜索引擎结果根据您提交的书名自动搜索获得并提供试读，不代表本阅读器赞成或被搜索链接到的第三方网页上的内容或立场。您应该对使用搜索引擎的结果自行承担风险。

不做任何形式的保证：不保证第三方搜索引擎的搜索结果满足您的要求，不保证搜索服务不中断，不保证搜索结果的安全性、正确性、及时性、合法性。 因网络状况、通讯线路、第三方网站等任何原因而导致您不能正常使用阅读，阅读器不承担任何法律责任。阅读器尊重并保护所有使用阅读器用户的个人隐私权。

所有小说书籍版权归小说作者所有。

所有书源归第三方书源网站所有。

建议和鼓励大家直接至第三方书源网站直接阅读小说。

您在使用该软件进行阅读时，代表您已经接受上述协议。
