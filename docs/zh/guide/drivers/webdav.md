---
# This is the icon of the page
icon: state
# This control sidebar order
order: 35
# A page can have multiple categories
category:
  - Guide
# A page can have multiple tags
tag:
  - Storage
  - Guide
# this page is sticky in article list
sticky: true
# this page will appear in starred articles
star: true
---

# WebDAV

## 地址

WebDAV 根地址

## 用户名

用户名

## 密码

密码

## 根文件夹路径

要挂载的文件夹路径，与加入地址相同

## OneDrive/SharePoint

选择 vendor 为 sharepoint，支持国际版/世纪互联。

你可以通过[这个工具](https://alist.nn.ci/tool/onedrive/webdav.html)获取 WebdAV 根地址，如果要挂载指定的目录，在后面拼接即可。

用户名为 OneDrive 账号邮箱，密码即为 OneDrive 账号密码。



### 默认使用的下载方式


```mermaid
---
title: 默认使用的那种下载方式？
---
flowchart TB
    style c1 fill:#bbf,stroke:#f66,stroke-width:2px,color:#fff
    style a2 fill:#ff7575,stroke:#333,stroke-width:4px
    subgraph ide1 [ ]
    c1
    end
    c1[本机代理]:::someclass==默认==>a2[用户设备]
    classDef someclass fill:#f96
    b1[代理URL]-.备选.->a2[用户设备]
    click b1 "../drivers/common.html#webdav-策略"
    click c1 "../drivers/common.html#webdav-策略"
```
