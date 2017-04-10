---
order: 6
iframe: true
title:
  zh-CN: 顶部公告
  en-US: Banner
---

## zh-CN

页面顶部通告形式，默认有图标且`type` 为 'warning'。

## en-US

Display Alert as a banner at top of page.

````jsx
import { Alert } from 'antd';

ReactDOM.render(
  <div>
    <Alert message="Warning text" banner />
    <br />
    <Alert message="Very long warning text warning text text text text text text text" banner closable />
  </div>
, mountNode);
````