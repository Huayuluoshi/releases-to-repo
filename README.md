# Git Releases to APT repo

为通过类似 Github Releases 渠道分发 deb 软件包的软件构建的一个 APT 仓库。这是 [wcbing APT Repo](https://github.com/wcbing/wcbing-apt-repo) 的一部分，也可单独使用。

> “wcbing APT Repo”包含更多软件，同时为中国地区用户提供了提供了“转发至 Github 代理”服务。

An APT repository built for software that distributes deb packages through a Github Releases-like channel. This is part of the [wcbing APT Repo](https://github.com/wcbing/wcbing-apt-repo) and is available separately.

> The 'wcbing APT Repo' includes more software and provides a "forward to Github proxy" service for users in China.


## 如何使用 - How to use

For Debian 11+ / Ubuntu 22.04+:

```sh
curl -s https://raw.githubusercontent.com/wcbing-apt-repo/releases-to-repo/refs/heads/master/releases-to-repo.sources | sudo tee /etc/apt/sources.list.d/releases-to-repo.sources
sudo apt update
```


## ⏲️ 定时检测 - Scheduled detection

| 软件名 | 包名 | amd64 | arm64 |
| ----- | ---- | ----- | ----- |
| [balenaEtcher](https://github.com/balena-io/etcher) | balena-etcher | ✅ | |
| [bat](https://github.com/sharkdp/bat) | bat | ✅ | ✅ |
| [BongoCat](https://github.com/ayangweb/BongoCat) | bongo-cat | ✅ | ✅ |
| [bottom (btm)](https://github.com/ClementTsang/bottom) | bottom | ✅ | ✅ |
| [小白羊 BoxPlayer](https://github.com/gaozhangmin/boxplayer) | boxplayer | ✅ | ✅ |
| [Caddy](https://github.com/caddyserver/caddy) | caddy | ✅ | ✅ |
| [Cherry Studio](https://github.com/CherryHQ/cherry-studio) | cherrystudio | ✅ | ✅ |
| [chezmoi](https://github.com/twpayne/chezmoi) | chezmoi | ✅ | ✅ |
| [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) | clash-verge | ✅ | ✅ |
| [Cloudflare Tunnel](https://github.com/cloudflare/cloudflared) | cloudflared | ✅ | ✅ |
| [ClassIsland](https://github.com/ClassIsland/ClassIsland) | cn.classisland.app | ✅ | ✅ |
| [code-server](https://github.com/coder/code-server) | code-server | ✅ | ✅ |
| [VSCodium](https://github.com/VSCodium/vscodium) | codium | ✅ | ✅ |
| [Cryptomator](https://github.com/cryptomator/cryptomator) | cryptomator | ✅ | |
| [DBeaver](https://github.com/dbeaver/dbeaver) | dbeaver-ce | ✅ | |
| [draw.io](https://github.com/jgraph/drawio-desktop) | draw.io | ✅ | ✅ |
| [Dust](https://github.com/bootandy/dust) | du-dust | ✅ | |
| [Dufs](https://github.com/wcbing-apt-repo/dufs-debs)* | dufs | ✅ | ✅ |
| [EasyPostman](https://github.com/lakernote/EasyPostman) | easypostman | ✅ | ✅ |
| [Thorium Reader](https://github.com/edrlab/thorium-reader) | edrlab.thoriumreader | ✅ | ✅ |
| [Fastfetch](https://github.com/fastfetch-cli/fastfetch) | fastfetch | ✅ | ✅ |
| [File Browser](https://github.com/wcbing-apt-repo/filebrowser-debs)* | filebrowser | ✅ | ✅ |
| [Flameshot](https://github.com/flameshot-org/flameshot) | flameshot | ✅ | |
| [FlClash](https://github.com/chen08209/FlClash) | flclash | ✅ | ✅ |
| [Foliate](https://github.com/johnfactotum/foliate) | foliate | ✅ | ✅ |
| [fooyin](https://github.com/fooyin/fooyin) | fooyin | ✅ | |
| [Fresh](https://github.com/sinelaw/fresh) | fresh-editor | ✅ | ✅ |
| [frp](https://github.com/wcbing-apt-repo/frp-debs)* | frps<br />frpc | ✅ | ✅ |
| [Frpc-Desktop](https://github.com/luckjiawei/frpc-desktop) | frpc-desktop | ✅ | ✅ |
| [Ghost-Downloader](https://github.com/XiaoYouChR/Ghost-Downloader-3) | ghost-downloader | ✅ | ✅ |
| [gRPCurl](https://github.com/fullstorydev/grpcurl) | grpcurl | ✅ | ✅ |
| [Hiddify](https://github.com/hiddify/hiddify-app) | hiddify | ✅ | |
| [Himalaya](https://github.com/wcbing-apt-repo/himalaya-debs)* | himalaya | ✅ | ✅ |
| [Hoppscotch](https://github.com/hoppscotch/releases) | hoppscotch | ✅ | |
| [hugo](https://github.com/gohugoio/hugo) | hugo | ✅ | ✅ |
| [Joplin](https://github.com/laurent22/joplin) | joplin | ✅ | |
| [Koodo Reader](https://github.com/koodo-reader/koodo-reader) | koodo-reader | ✅ | ✅ |
| [Kula](https://github.com/c0m4r/kula) | kula | ✅ | ✅ |
| [Lazydocker](https://github.com/wcbing-apt-repo/lazydocker-debs)* | lazydocker | ✅ | ✅ |
| [Lazygit](https://github.com/wcbing-apt-repo/lazygit-debs)* | lazygit | ✅ | ✅ |
| [LocalSend](https://github.com/localsend/localsend) | localsend | ✅ | ✅ |
| [mihomo](https://github.com/MetaCubeX/mihomo) | mihomo | ✅ | ✅ |
| [Motrix Next](https://github.com/AnInsomniacy/motrix-next) | motrix-next | ✅ | ✅ |
| [MQTTX](https://github.com/emqx/MQTTX) | mqttx | ✅ | ✅ |
| [Microsoft Edit](https://github.com/wcbing-apt-repo/msedit-debs)* | msedit | ✅ | ✅ |
| [MusicFree](https://github.com/maotoumao/MusicFreeDesktop) | musicfree | ✅ | |
| [nautilus-open-any-terminal](https://github.com/Stunkymonkey/nautilus-open-any-terminal) | nautilus-extension-any-terminal | ✅ | ✅ |
| [Neovide](https://github.com/wcbing-apt-repo/neovide-debs)* | neovide | ✅ | |
| [Neovim/Nvim](https://github.com/neovim/neovim-releases) | neovim | ✅ | |
| [网易云音乐 - Web 版](https://github.com/elysia-best/netease-cloud-music-web) | netease-cloud-music | ✅ | ✅ |
| [NextTrace](https://github.com/nxtrace/nexttrace-debs) | nexttrace<br />nexttrace-tiny | ✅ | ✅ |
| [Obsidian](https://github.com/obsidianmd/obsidian-releases) | obsidian | ✅ | |
| [OnlyOffice 桌面编辑器](https://github.com/ONLYOFFICE/DesktopEditors) | onlyoffice-desktopeditors | ✅ | |
| [Pandoc](https://github.com/jgm/pandoc) | pandoc | ✅ | ✅ |
| [PDFsam Basic](https://github.com/torakiki/pdfsam) | pdfsam-basic | ✅ | |
| [PeaZip](https://github.com/peazip/PeaZip) | peazip | ✅ | |
| [PowerShell](https://github.com/PowerShell/PowerShell) | powershell | ✅ | |
| [Rclone](https://github.com/rclone/rclone) | rclone | ✅ | ✅ |
| [RustDesk](https://github.com/rustdesk/rustdesk) | rustdesk | ✅ | ✅ |
| [Simplenote](https://github.com/Automattic/simplenote-electron) | simplenote | ✅ | ✅ |
| [思源笔记](https://github.com/siyuan-note/siyuan) | siyuan | ✅ | ✅ |
| [Sparkle](https://github.com/xishang0128/sparkle) | sparkle | ✅ | ✅ |
| [SPlayer](https://github.com/imsyy/SPlayer) | splayer | ✅ | ✅ |
| [superfile](https://github.com/wcbing-apt-repo/superfile-debs)* | superfile | ✅ | ✅ |
| [Systemd manager tui](https://github.com/matheus-git/systemd-manager-tui) | systemd-manager-tui | ✅ | ✅ |
| [Tabby](https://github.com/Eugeny/tabby) | tabby-terminal | ✅ | ✅ |
| [TinyGo](https://github.com/tinygo-org/tinygo) | tinygo | ✅ | ✅ |
| [Tiny RDM](https://github.com/tiny-craft/tiny-rdm) | tinyrdm | ✅ | |
| [Trippy](https://github.com/fujiapple852/trippy) | trippy | ✅ | |
| [Ulauncher](https://github.com/Ulauncher/Ulauncher) | ulauncher | ✅ | ✅ |
| [柚坛工具箱 NT](https://github.com/Uotan-Dev/UotanToolboxNT) | uotantoolbox | ✅ | ✅ |
| [venera](https://github.com/venera-app/venera) | venera | ✅ | ✅ |
| [Wave Terminal](https://github.com/wavetermdev/waveterm) | waveterm | ✅ | ✅ |
| [WinBoat](https://github.com/TibixDev/winboat) | winboat | ✅ | |
| [X Minecraft Launcher](https://github.com/Voxelum/x-minecraft-launcher) | xmcl | ✅ | ✅ |
| [Yazi](https://github.com/sxyazi/yazi) | yazi | ✅ | ✅ |
| [YesPlayMusic](https://github.com/qier222/YesPlayMusic) | yesplaymusic | ✅ | ✅ |
| [zyfun[ZyPlayer]](https://github.com/Hiram-Wong/ZyPlayer) | zyfun | ✅ | ✅ |


> \* 表示由 wcbing-apt-repo 打包

> \* means packed by wcbing-apt-repo

## 🗃️ 存档或不活跃 - Archived or inactive

| 软件名 | 包名 | amd64 | arm64 |
| ----- | --- | ----- | ----- |
| [Flameshot](https://github.com/flameshot-org/flameshot) | flameshot | | ✅ |
| [MarkText](https://github.com/marktext/marktext) | marktext | ✅ | |
| [Motrix](https://github.com/agalwood/Motrix) | motrix | ✅ | ✅ |
| [SunnyCapturer](https://github.com/XMuli/SunnyCapturer) | sunnycapturer | ✅ | |
| [Yolx](https://github.com/uiYzzi/Yolx) | yolx | ✅ | |
