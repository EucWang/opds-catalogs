# OPDS书源整理

```
 整理日期： 2026年6月5日
 电子书阅读器： 随阅/Handy Reader
 官方网站： https://handyreader.top
```

## arxiv
- URL：
  - http://arxiv.maplepop.com/catalog/（非官方OPDS代理）
  - https://export.arxiv.org/api/query（此为官方API，非OPDS格式，如用于OPDS客户端会解析失败）

- 描述：书库丰富（学术预印本），但限速严重，不适合频繁访问。仅使用第一个URL可作为OPDS源；第二个URL需单独调用API，不能直接作为OPDS订阅。

## manybooks

- URL：https://manybooks.net/opds

- 描述：宣称50K+电子书，种类丰富，无访问限制。偶有不稳定， 需做好容错处理。

## wikisource

- URL（修正）：https://{lang}.wikisource.org（例如 https://en.wikisource.org）

- 描述：维基文库资源，但常被人机验证（Cloudflare）拦截，且有访问限制。实际内容以元数据和原始文本为主，直接通过OPDS获取全文可能需要额外解析。

## gutenberg

- URL：https://www.gutenberg.org/ebooks/search.opds/

- 描述：75K+ 免费电子书，部分书籍下载时会失败。

## gallica

- URL：https://gallica.bnf.fr/opds

- 描述：法国国家图书馆的数字资源，资源极其丰富（法语为主），可匿名访问。无已知限制，适合法语用户或学术用途。

## standardebooks

- URL：https://standardebooks.org/opds/all

- 描述：高质量排版电子书。需要授权或捐款才能获取完整OPDS源。

## theanarchistlibrary

- URL：https://theanarchistlibrary.org/opds

- 描述：专门收录无政府主义相关书籍（政治、哲学等），主题针对性极强。不适用于普通大众用户。内容合法，但需注意审核政策。


## flibusta

- URL：http://flibusta.is/opds

- 描述：俄语电子书库，内容丰富，但存在版权风险。在俄罗斯已被ISP封禁。部分地区可能无法直接访问。

## openedition

- URL：https://opds.openedition.org/

- 描述：开放学术图书平台，资源质量高。时常会触发限速或人机验证。稳定性波动较大。


## wolnelektury

- URL：https://wolnelektury.pl/opds/

- 描述：波兰语数字图书馆，资源以波兰文学经典为主。


## rus（lib.rus.ec）

- URL：https://lib.rus.ec/opds（状态存疑）

- 描述：曾为大型俄语电子书库，可能已失效或需特殊网络环境

## unglue

- URL：https://www.unglue.it/api/opds/

- 描述：拥有 25k+ 本免费电子书，访问速度快，资源以知识共享（CC）协议为主。

## ebooksgratuits

- URL：https://www.ebooksgratuits.com/opds/

- 描述：法语免费电子书站，书库数量较少（约几百本），但质量较高。OPDS稳定，适合作为法语补充源。

## textos

- URL：https://textos.info/opds

- 描述：西班牙语数字图书馆，藏书约 3,500 本。资源以经典文学为主，OPDS接口正常。

## wenyuange

- URL：https://wenyuange.org/opds/

- 描述：中文电子书库，宣称藏书 24K+（约2.4万本）。中文公共版权书籍为主，OPDS响应速度尚可，适合中文用户。