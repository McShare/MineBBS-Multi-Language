# MineBBS-Multi-Language

为MineBBS更完善的国际化多语言发展做一份贡献吧~

这里是MineBBS论坛程序的语言文件，包括导航边栏、提醒通知等绝大部分功能性文字，甚至包括了后台管理的文字（不含主题、版块、标题、内容）。

为这些部分提供人性化的翻译虽然不能解决国际友人浏览内容的问题，但是可以让他们在使用论坛时减少阻涩感，更加的自然。

我们建议 Fork 后进行修改，然后以 Pull requests 的方式进行贡献。

你可以在现有语言文件上进行翻译、修正，也可以在issue中提出新建语言文件（我会创建过来上传）。

期待你的帮助！

## 目前的语言翻译进度：

[![github](https://img.shields.io/badge/简体中文-89%25-red)](https://github.com/McShare/MineBBS-Multi-Language/blob/main/language-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%EF%BC%88zh-CHS%EF%BC%89.xml)：界面基本翻译完成，可能存在细节错漏，后台部分语言未翻译

[![github](https://img.shields.io/badge/繁體中文-68%25-green)](https://github.com/McShare/MineBBS-Multi-Language/blob/main/language-%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87%EF%BC%88zh-CHT%EF%BC%89.xml) ：界面大体翻译完成，可能存在部分漏译，后台语言未翻译

[![github](https://img.shields.io/badge/English-97%25-blue)](https://github.com/McShare/MineBBS-Multi-Language/blob/main/language-English-(EN).xml)：界面基本完成，可能存在细节漏译，后台语言基本完成

[![github](https://img.shields.io/badge/العربية-33%25-yellow)](https://github.com/McShare/MineBBS-Multi-Language/blob/main/language-alyrbi%D8%A9%EF%BC%88AR%EF%BC%89.xml)：界面部分翻译完成，存在大量漏译，后台语言未翻译 

[![github](https://img.shields.io/badge/Русский-27%25-white)](https://github.com/McShare/MineBBS-Multi-Language/blob/main/language-Russkij-(RU).xml)：界面部分翻译完成，存在大量漏译，后台语言未翻译

## 翻译建议：

一个完整的字段代码是这样的：

`<phrase title="3_months_ago" addon_id="XF" version_id="1010010" version_string="1.1.0 Alpha"><![CDATA[3 個月前]]></phrase>`

其中`title`为字段id，`addon_id`为所属组件名称，两个`version`为版本，请**不要对这些内容进行更改**。

可翻译的部分是`CDATA[3 個月前]`中括号内的内容，在例中即为`3 個月前`。

部分词语的`CDATA[]`中可能为空，即本语言还没有这个词语的翻译，可以进行填写。

**由于语言文件较大，共有一万两千多行，所以不必全部翻译，请大家利用搜索，找到对应词语进行翻译**

**可以在网站上调整到对应的语言，然后根据未翻译的部分进行搜索翻译，这样会更有针对性效率更高，避免翻译大量不必要的词语**
