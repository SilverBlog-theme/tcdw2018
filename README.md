# SilverBlog tcdw2018 Theme

tcdw 2018 年风格的个人博客主题

![预览画面](https://i.loli.net/2018/06/02/5b1254453e35f.png)

## 使用说明

### 手机菜单项目图标

你需要在菜单项里指定 `mobile_prefix` 字段，以便为手机菜单项目增加前缀（Font Awesome 4 图标）。

```json
[
    {
        "mobile_prefix": "<i class=\"fas fa-fw fa-user\"></i>",
        "title": "关于 & 留言",
        "name": "about"
    },
    {
        "mobile_prefix": "<i class=\"fas fa-fw fa-archive\"></i>",
        "title": "归档",
        "name": "archive"
    },
    {
        "mobile_prefix": "<i class=\"fas fa-fw fa-link\"></i>",
        "title": "链接",
        "name": "links"
    }
]
```

### 首页头图

你需要在主题的 `config.json` 指定头图地址（`Cover_Image`）。

```json
{
    "Cover_Image": ""
}
```

## 源文件

[请见这里](https://gitlab.com/silverblog-theme-dev/tcdw2018)

## 许可证

MIT
