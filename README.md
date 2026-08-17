# tt-multi-cfg

语音多开助手远程配置。改 `cfg.json` 即可更新公告、开关、版本。

客户端请 GET 下面任一地址：

- `https://cdn.jsdelivr.net/gh/alttab8520/tt-multi-cfg@main/cfg.json`
- `https://raw.githubusercontent.com/alttab8520/tt-multi-cfg/main/cfg.json`

字段：

- `announcement` 公告
- `enabled` 远程停服，`false` 时客户端应提示并退出
- `latest_version` / `need_update` / `update_message` 版本
- `download_url` / `download_url_backup` 下载页
