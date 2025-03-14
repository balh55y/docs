---
# This is the icon of the page
icon: state
# This control sidebar order
order: 37
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

# Terabox


## refresh token

[**Click here to log in**](https://www.terabox.com/) to obtain a refresh token

![terabox](/img/drivers/terabox/terabox1.png)

## Add method

![terabox](/img/drivers/terabox/terabox2.png)



#### Note: The default root file path is /

- If you don't want to write to the root directory **/** you want to write to other directories
- Mount other single subdirectories, put a picture for reference
   - <img src="/img/drivers/terabox/terabox3.png" alt="Demo" style="zoom:50%;" />




### The default download method used

```mermaid
---
title: Which download method is used by default?
---
flowchart TB
    style a1 fill:#bbf,stroke:#f66,stroke-width:2px,color:#fff
    style a2 fill:#ff7575,stroke:#333,stroke-width:4px
    subgraph ide1 [ ]
    a1
    end
    a1[302]:::someclass====|default|a2[user equipment]
    classDef someclass fill:#f96
    c1[local proxy]-.alternative.->a2[user equipment]
    b1[Download proxy URL]-.alternative.->a2[user equipment]
    click a1 "../drivers/common.html#webdav-policy"
    click b1 "../drivers/common.html#webdav-policy"
    click c1 "../drivers/common.html#webdav-policy"
```
