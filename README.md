# icons

个人图标库（私有）。

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

4 个 JSON 的直链：

```
https://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@raw.githubusercontent.com/baynidn/icons/main/Icon/Area.json
https://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@raw.githubusercontent.com/baynidn/icons/main/Icon/App.json
https://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@raw.githubusercontent.com/baynidn/icons/main/Icon/Proxy.json
https://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@raw.githubusercontent.com/baynidn/icons/main/Icon/Emby.json
```

本仓库是私有的，在 Surge / Quantumult X 等应用里引用时，需要在域名前拼上 token：

```
https://<你的token>@raw.githubusercontent.com/baynidn/icons/main/Icon/Area.json
```

把 `<你的token>` 换成你自己的 GitHub PAT（需要 `repo` 权限）即可。

## 图标来源

整理自 [Koolson/Qure](https://github.com/Koolson/Qure) 的 `IconSet/Color`（2026-10-02）。
