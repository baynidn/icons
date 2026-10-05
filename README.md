# icons

整理自 [Koolson/Qure](https://github.com/Koolson/Qure) 的 `IconSet/Color`（2026-10-02）。


## 目录结构

```
Icon/
  Area/          53 个 · 国家/地区旗帜
  Area.json
  App/           68 个 · 应用图标
  App.json
  Proxy/         46 个 · 代理 / 网络相关图标
  Proxy.json
  Emby/           8 个 · Emby 相关图标
  Emby.json
```

## JSON 说明

每个文件夹配一个同名 JSON，格式如下：

```json
{
  "name": "Area",
  "description": "Area 图标 · ...",
  "icons": [
    { "name": "CN", "url": "https://raw.githubusercontent.com/baynidn/icons/main/Icon/Area/CN.png" }
  ]
}
```

`name` 是图标名（不带后缀），`url` 是该图标的直链地址。

## 使用方法

本仓库是公开的，直接引用直链即可，无需 token。

Area.json（地区图标，53 个）：

```
https://raw.githubusercontent.com/baynidn/icons/main/Icon/Area.json
```

App.json（应用图标，68 个）：

```
https://raw.githubusercontent.com/baynidn/icons/main/Icon/App.json
```

Proxy.json（代理图标，46 个）：

```
https://raw.githubusercontent.com/baynidn/icons/main/Icon/Proxy.json
```

Emby.json（Emby 图标，8 个）：

```
https://raw.githubusercontent.com/baynidn/icons/main/Icon/Emby.json
```

单个图标示例：

```
https://raw.githubusercontent.com/baynidn/icons/main/Icon/Proxy/Proxy.png
```


