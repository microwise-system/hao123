# 网址大全

## 注意!

由于 github pages 屏蔽了百度spider的抓取，为了更好的SEO, 换做了 gitcafe 的 pages 服务, 不要在`gh-pages`上提交代码，提交到 `gitcafe-pages` 分支上，然后 push 到 gitcafe. 例如 `git push gitcafe gitcafe-pages`, 如果 push 不上去，联系高辉.

## 安装

已将安装 ruby

* gem install github-pages

## 网站使用 jekyll

本地预览

    jekyll serve

## 如何添加在线网站

在 `_data/sites.yml` 中添加一个条目, `name` 是现实名称，`url` 是网址。

```yml
- name: 天津区域中心
  url: http://tj.smart-museum.cn:66
```
