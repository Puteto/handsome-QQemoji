# Handsome-QQemoji

---

**QQ原生表情包，png 格式静态图片，适用于 [ihewro](https://www.ihewro.com/) 开发的 Handsome Typecho 主题。**

Demo:

![Demo](http://cdn.anleo.top/img/2022-12/1671007125.png)

*QQ表情版权归腾讯公司所有，此分享仅供学习交流使用，严禁将此用于商业活动！*

## 表情概况

当前收集有 **193 个**表情，包含 **188 个**QQ表情和 **5 个** 旗帜emoji。

表情以 PC 版本的 QQ（版本号：9.6.7）为参考，并加入了 Android 版 QQ（版本号：V8.9.13）部分特殊表情和其他版本的 QQ 的个别表情。

表情源文件（除旗帜 emoji 外）均被调整为 **56×56** 大小的 png 图片。图片命名方式采用以 PC 版 QQ 的快捷输入的英文代码命名为主，QQ 未采用英文代码的，表情名称在 4 个字以内的采用拼音全拼命名，4 个字及以上的采用拼音音节首字母简写命名。（ *方便查找，快捷使用和导入 Minecraft 等其他用途*）

表情默认顺序参考 PC 版 QQ 默认顺序，后期可自行通过`OwO.json`文件修改。

## 使用方法

**Handsome 主题**：

1. 将 Github 文件 zip 打包下载，解压；
2. 将`OwO.json`文件到`Handsome`主题目录下的`/usr/OwO.json`替换，或者自行将文件中的"QQ"部分复制粘贴到合适位置。
3. 将`qqemoji`文件夹整体导入至Handsome主题目录下的`/assets/img/emotion/`中。
4. 此时若直接更新缓存使用的话会显得表情过大，需要正常显示的话可以继续进行如下操作：
5. 找到Handsome主题目录下的`/assets/css/origin/`目录，打开`function.min.css`查找`twemoji`，在`.OwO .OwO-body .OwO-twemoji .OwO-item{max-width:39px;box-sizing:border-box}`处照葫芦画瓢，在`.OwO-twemoji `后加个`.OwO-qqemoji `，或者重新插入新的样式；另一处`.emotion-twemoji{height:18px}`也同理，我选择添加新的`.emotion-qqemoji{height:20px}`，选择合适的大小。
6. 同目录下的`owo.min.css`文件同理，自行添加`.OwO-qqemoji`和`.emotion-qqemoji`。这样表情就变成了合适的大小。

## 其他

- 详情参见 [本人博客](https://b.anleo.top/index.php/archives/21/)；
- Minecraft  ItemsAdder 表情导入参见博客文章内；
- 该项目会不定期更新。