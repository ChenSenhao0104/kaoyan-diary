public文件夹是 Hugo 生成出来的静态网站输出目录

**不要手动去改 `public/` 里面的东西。**

你真正应该改的是：

- `content/`
- `layouts/`
- `static/`
- `hugo.toml` 或 `config/`

`public/` 只是结果，不是源文件目录。Hugo 官方目录结构里也是这么区分的。