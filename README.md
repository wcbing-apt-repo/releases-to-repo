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

| 包名 | 软件名 | amd64 | arm64 |
| ---- | ----- | ----- | ----- |
| balena-etcher | [balenaEtcher](https://github.com/balena-io/etcher) | ✅ | |
| bat | [bat](https://github.com/sharkdp/bat) | ✅ | ✅ |
| bottom | [bottom (btm)](https://github.com/ClementTsang/bottom) | ✅ | ✅ |
| boxplayer | [小白羊 BoxPlayer](https://github.com/gaozhangmin/boxplayer) | ✅ | ✅ |
| caddy | [Caddy](https://github.com/caddyserver/caddy) | ✅ | ✅ |
| cc-switch | [CC Switch](https://github.com/farion1231/cc-switch) | ✅ | ✅ |
| cherrystudio | [Cherry Studio](https://github.com/CherryHQ/cherry-studio) | ✅ | ✅ |
| chezmoi | [chezmoi](https://github.com/twpayne/chezmoi) | ✅ | ✅ |
| chsrc | [chsrc](https://github.com/RubyMetric/chsrc) | ✅ | |
| clash-verge | [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) | ✅ | ✅ |
| cloudflared | [Cloudflare Tunnel](https://github.com/cloudflare/cloudflared) | ✅ | ✅ |
| cn.classisland.app | [ClassIsland](https://github.com/ClassIsland/ClassIsland) | ✅ | ✅ |
| code-server | [code-server](https://github.com/coder/code-server) | ✅ | ✅ |
| codium | [VSCodium](https://github.com/VSCodium/vscodium) | ✅ | ✅ |
| cryptomator | [Cryptomator](https://github.com/cryptomator/cryptomator) | ✅ | |
| dbeaver-ce | [DBeaver](https://github.com/dbeaver/dbeaver) | ✅ | ✅ |
| dbx | [DBX](https://github.com/t8y2/dbx) | ✅ | ✅ |
| draw.io | [draw.io](https://github.com/jgraph/drawio-desktop) | ✅ | ✅ |
| du-dust | [Dust](https://github.com/bootandy/dust) | ✅ | |
| dufs | [Dufs](https://github.com/wcbing-deb-packager/dufs-debs)* | ✅ | ✅ |
| easypostman | [EasyPostman](https://github.com/lakernote/easy-postman) | ✅ | ✅ |
| edrlab.thoriumreader | [Thorium Reader](https://github.com/edrlab/thorium-reader) | ✅ | ✅ |
| escrcpy | [Escrcpy](https://github.com/viarotel-org/escrcpy) | ✅ | ✅ |
| fastfetch | [Fastfetch](https://github.com/fastfetch-cli/fastfetch) | ✅ | ✅ |
| flclash | [FlClash](https://github.com/chen08209/FlClash) | ✅ | ✅ |
| foliate | [Foliate](https://github.com/johnfactotum/foliate) | ✅ | ✅ |
| fooyin | [fooyin](https://github.com/fooyin/fooyin) | ✅ | |
| fresco | [fresco](https://github.com/DibbayajyotiRoy/Fresco) | ✅ | |
| fresh-editor | [Fresh](https://github.com/sinelaw/fresh) | ✅ | ✅ |
| frps<br />frpc | [frp](https://github.com/wcbing-deb-packager/frp-debs)* | ✅ | ✅ |
| frpc-desktop | [Frpc-Desktop](https://github.com/luckjiawei/frpc-desktop) | ✅ | ✅ |
| ghost-downloader | [Ghost-Downloader](https://github.com/XiaoYouChR/Ghost-Downloader-3) | ✅ | ✅ |
| grpcurl | [gRPCurl](https://github.com/fullstorydev/grpcurl) | ✅ | ✅ |
| heroic | [Heroic Games Launcher](https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher) | ✅ | |
| hiddify | [Hiddify](https://github.com/hiddify/hiddify-app) | ✅ | |
| himalaya | [Himalaya](https://github.com/wcbing-deb-packager/himalaya-debs)* | ✅ | ✅ |
| hoppscotch | [Hoppscotch](https://github.com/hoppscotch/releases) | ✅ | |
| hugo | [hugo](https://github.com/gohugoio/hugo) | ✅ | ✅ |
| joplin | [Joplin](https://github.com/laurent22/joplin) | ✅ | |
| kazumi | [Kazumi](https://github.com/Predidit/Kazumi) | ✅ | ✅ |
| koodo-reader | [Koodo Reader](https://github.com/koodo-reader/koodo-reader) | ✅ | ✅ |
| kula | [Kula](https://github.com/c0m4r/kula) | ✅ | ✅ |
| lazydocker | [Lazydocker](https://github.com/wcbing-deb-packager/lazydocker-debs)* | ✅ | ✅ |
| lazygit | [Lazygit](https://github.com/wcbing-deb-packager/lazygit-debs)* | ✅ | ✅ |
| localsend | [LocalSend](https://github.com/localsend/localsend) | ✅ | ✅ |
| marktext | [MarkText](https://github.com/marktext/marktext) | ✅ | |
| mihomo | [mihomo](https://github.com/MetaCubeX/mihomo) | ✅ | ✅ |
| mqttx | [MQTTX](https://github.com/emqx/MQTTX) | ✅ | ✅ |
| msedit | [Microsoft Edit](https://github.com/wcbing-deb-packager/msedit-debs)* | ✅ | ✅ |
| musicfree | [MusicFree](https://github.com/maotoumao/MusicFreeDesktop) | ✅ | |
| nautilus-extension-any-terminal | [nautilus-open-any-terminal](https://github.com/Stunkymonkey/nautilus-open-any-terminal) | ✅ | ✅ |
| neovide | [Neovide](https://github.com/wcbing-deb-packager/neovide-debs)* | ✅ | |
| neovim | [Neovim/Nvim](https://github.com/neovim/neovim-releases) | ✅ | |
| netease-cloud-music | [网易云音乐 - Web 版](https://github.com/elysia-best/netease-cloud-music-web) | ✅ | ✅ |
| nexttrace<br />nexttrace-tiny | [NextTrace](https://github.com/nxtrace/nexttrace-debs) | ✅ | ✅ |
| obsidian | [Obsidian](https://github.com/obsidianmd/obsidian-releases) | ✅ | |
| onlyoffice-desktopeditors | [OnlyOffice 桌面编辑器](https://github.com/ONLYOFFICE/DesktopEditors) | ✅ | |
| pandoc | [Pandoc](https://github.com/jgm/pandoc) | ✅ | ✅ |
| pdfsam-basic | [PDFsam Basic](https://github.com/torakiki/pdfsam) | ✅ | |
| peazip | [PeaZip](https://github.com/peazip/PeaZip) | ✅ | |
| powershell | [PowerShell](https://github.com/PowerShell/PowerShell) | ✅ | |
| rayburst | [Rayburst](https://github.com/AnInsomniacy/rayburst) | ✅ | ✅ |
| rclone | [Rclone](https://github.com/rclone/rclone) | ✅ | ✅ |
| reqable | [Reqable](https://github.com/reqable/reqable-app) | ✅ | |
| reaper-installer | [REAPER](https://github.com/Huayuluoshi/reaper-installer) | ✅ | ✅ |
| rustdesk | [RustDesk](https://github.com/rustdesk/rustdesk) | ✅ | ✅ |
| simplenote | [Simplenote](https://github.com/Automattic/simplenote-electron) | ✅ | ✅ |
| siyuan | [思源笔记](https://github.com/siyuan-note/siyuan) | ✅ | ✅ |
| sparkle | [Sparkle](https://github.com/xishang0128/sparkle) | ✅ | ✅ |
| superfile | [superfile](https://github.com/wcbing-deb-packager/superfile-debs)* | ✅ | ✅ |
| systemd-manager-tui | [Systemd manager tui](https://github.com/matheus-git/systemd-manager-tui) | ✅ | ✅ |
| tabby-terminal | [Tabby](https://github.com/Eugeny/tabby) | ✅ | ✅ |
| tinygo | [TinyGo](https://github.com/tinygo-org/tinygo) | ✅ | ✅ |
| tinyrdm | [Tiny RDM](https://github.com/tiny-craft/tiny-rdm) | ✅ | |
| trippy | [Trippy](https://github.com/fujiapple852/trippy) | ✅ | |
| tssh | [trzsz-ssh (tssh)](https://github.com/trzsz/trzsz-ssh) | ✅ | ✅ |
| ulauncher | [Ulauncher](https://github.com/Ulauncher/Ulauncher) | ✅ | ✅ |
| uotantoolbox | [柚坛工具箱 NT](https://github.com/Uotan-Dev/UotanToolboxNT) | ✅ | ✅ |
| v2raya | [v2raya](https://github.com/v2rayA/v2rayA) | ✅ | ✅ |
| v2rayn | [v2rayn](https://github.com/2dust/v2rayN) | ✅ | ✅ |
| venera | [venera](https://github.com/venera-app/venera) | ✅ | ✅ |
| waveterm | [Wave Terminal](https://github.com/wavetermdev/waveterm) | ✅ | ✅ |
| winboat | [WinBoat](https://github.com/winboat-org/winboat) | ✅ | |
| xmcl | [X Minecraft Launcher](https://github.com/Voxelum/x-minecraft-launcher) | ✅ | ✅ |
| yazi | [Yazi](https://github.com/sxyazi/yazi) | ✅ | ✅ |
| yesplaymusic | [YesPlayMusic](https://github.com/qier222/YesPlayMusic) | ✅ | ✅ |
| zyfun | [zyfun[ZyPlayer]](https://github.com/Hiram-Wong/ZyPlayer) | ✅ | ✅ |


> \* 表示由 wcbing 打包

> \* means packaged by wcbing

## 🗃️ 存档或不活跃 - Archived or inactive

| 包名 | 软件名 | amd64 | arm64 |
| ---- | ----- | ----- | ----- |
| bongo-cat | [BongoCat](https://github.com/ayangweb/BongoCat) | ✅ | ✅ |
| filebrowser | [File Browser](https://github.com/wcbing-deb-packager/filebrowser-debs)* | ✅ | ✅ |
| flameshot | [Flameshot](https://github.com/flameshot-org/flameshot) | ✅ | ✅ |
| motrix | [Motrix](https://github.com/agalwood/Motrix) | ✅ | ✅ |
| motrix-next | [Motrix Next](https://github.com/AnInsomniacy/motrix-next) <br>改名为 Rayburst | ✅ | ✅ |
| splayer | [SPlayer](https://github.com/SPlayer-Dev/SPlayer) | ✅ | ✅ |
| sunnycapturer | [SunnyCapturer](https://github.com/XMuli/SunnyCapturer) | ✅ | |
| yolx | [Yolx](https://github.com/uiYzzi/Yolx) | ✅ | |
