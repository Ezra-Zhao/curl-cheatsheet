# curl 命令速查表 · curl Cheatsheet

> 🌍 [Español](README.es.md) · [Português](README.pt.md)

一份**一页纸**的 curl 命令速查表：29 条真实可用的命令，每个条目只讲三件事——**它是干什么的、一条能直接复制粘贴的命令、适用场景标签**。不编造参数，不拼凑语法。

## 面向谁

后端开发者、运维工程师、API 联调工程师，以及每天跟 HTTP API 打交道的你。如果你调接口还在靠图形工具一个个点，这张表能让你在终端里三秒发出一个请求。

## 怎么用

1. 直接看 **[CHEATSHEET.md](CHEATSHEET.md)** ——速查表正文，英文命令全球开发者都无压力。
2. 先验证环境：curl 几乎所有系统自带，跑 `curl --version` 确认（7.68+ 即可覆盖本表全部命令）。
3. 把示例里的 `https://example.com` 换成你的目标地址，每个条目亲手敲一遍，一小时就顺手了。

## 收录了什么

| 分类 | 内容 |
|---|---|
| 🌐 基础请求 | GET / POST / PUT / DELETE / PATCH / HEAD（6 条） |
| 🔑 请求头与认证 | 自定义头、Bearer Token、Basic Auth、User-Agent（4 条） |
| 📤 发送数据 | JSON、URL 编码、multipart 文件上传（3 条） |
| 📥 响应处理 | 看响应头、存文件、静默模式、耗时统计（5 条） |
| 🐞 调试 | -v 详情、trace、HTTP 版本、跳过证书 ⚠️（4 条） |
| ⬇️ 下载与限速 | 断点续传、限速、失败重试（3 条） |
| 🍪 Cookie 与会话 | 存 cookie / 带 cookie 访问（2 条） |
| 🔀 代理 | HTTP 代理、SOCKS5 代理（2 条） |

所有命令均为真实 curl 语法（已用 curl 8.5.0 实测验证），官方文档见 https://curl.se/docs/。

## 为什么是这 29 条

- **覆盖 API 联调全流程**：从发请求、带认证、传数据，到看响应、调问题、做下载，一张表走完日常 95% 的场景。
- **每条都能直接跑**：没有"示意性"伪命令，复制粘贴、换个 URL 就能用；危险选项（如 `-k` 跳过证书验证）明确标 ⚠️ 仅限调试环境。

## 欢迎 PR

发现命令写错了、参数过时了、翻译不到位——欢迎提 Pull Request。新增条目请保持统一格式（功能 / 命令 / 标签），**提交前请用真实 curl 跑一遍验证**。

## 📚 更多速查表

同一作者的其他速查表，同样有中/西/葡三语版本：

- [FFmpeg 命令速查表](https://github.com/Ezra-Zhao/ffmpeg-cheatsheet) — 28 条音视频处理命令
- [Git 实战速查表](https://github.com/Ezra-Zhao/git-cheatsheet) — 30 条日常+救命命令
- [Docker 命令速查表](https://github.com/Ezra-Zhao/docker-cheatsheet) — 28 条容器命令
- [正则表达式速查表](https://github.com/Ezra-Zhao/regex-cheatsheet) — 30 条实战正则模式
- [jq 命令速查表](https://github.com/Ezra-Zhao/jq-cheatsheet) — 30 条 JSON 处理 filter
- [终端神器速查表](https://github.com/Ezra-Zhao/terminal-superpowers-cheatsheet) — 14 个终端效率工具
- [Adobe 免费替代速查表](https://github.com/Ezra-Zhao/adobe-free-alternatives-cheatsheet) — 16 个 Adobe 免费替代品
- [退订省钱速查表](https://github.com/Ezra-Zhao/desubscribe-cheatsheet) — 10 组退订替代，年省约 $1,260

## License

MIT © 2026 Guangyi Zhao，详见 [LICENSE](LICENSE)。
