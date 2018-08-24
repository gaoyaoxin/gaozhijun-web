---
title: "调教 Jekyll 博客"
tags:
  - jekyll
  
comments: true  
toc: true
toc_label: 本页内容
---

Jekyll 带来了巨大的便利，使用的过程也充满着乐趣，遂决定把调教过程记录下来，备忘的同时，也给其他朋友提供一些参考。


## 启用 Disqus

1. 在 Disqus 中

```yaml
provider               : "disqus" " 
  disqus:
    shortname            : "gaozhijun"
```


## 强制Jekyll运行环境为production

Jekyll本地运行时默认环境为Development，有一些插件需要在production环境下运行，如果需要使用production环境运行，可以按照如下命令运行。

```bash
JEKYLL_ENV=production bdle exec jekyll serve
```

## Favicon

想来一个酷酷的Favicon，发现这个在线工具不错： [favicon.io](https://www.favicon.io)