# Orbit

Orbit is the network and communications platform of [YunZheng LAB](https://yunzheng.space/) (AS204921): anycast DNS, a public resolver, an edge for your sites, and hosted voice, video, chat, mail and phone systems for organisations. Free for non-commercial use.

**Website:** [orbit.yunzheng.space](https://orbit.yunzheng.space/) · **Console:** [dash.yunzheng.space](https://dash.yunzheng.space/) · **Docs:** [orbit.yunzheng.space/docs](https://orbit.yunzheng.space/docs/) · **API:** [OpenAPI](https://dash.yunzheng.space/api/v1/openapi.json)

[中文](#中文)

## Products

DNS hosting and Shield (the edge in front of your sites) are described on the [Orbit home page](https://orbit.yunzheng.space/).

| Product | What it is |
|---|---|
| [Public Resolver](https://orbit.yunzheng.space/public-resolver/) | Free anycast public DNS: 177.177.83.83 resolves everything, 177.177.83.84 filters ads and malware, 177.177.83.64 adds DNS64. DoH, DoT and DoQ. No query logs. |
| [RPKI](https://orbit.yunzheng.space/rpki/) | Hosted RPKI for networks with their own addresses: create ROAs in a console, publish to our repository, feed routers via RTR. Free: one CA, 50 ROAs. |
| [Verify](https://orbit.yunzheng.space/verify/) | A CAPTCHA alternative for web forms: invisible for most visitors, one click only when risk is high, no cookies or tracking. Free for non-commercial sites. |
| [Link](https://orbit.yunzheng.space/link/) | A connector on the origin makes one outbound connection to the Orbit edge; Shield serves the site through it. No inbound ports, no public address. |
| [Pages](https://orbit.yunzheng.space/pages/) | Upload a folder; it is served from every location we run, on your own hostname, with a certificate and Shield’s edge rules. Free for up to two projects. |
| [Realtime](https://orbit.yunzheng.space/realtime/) | Voice and video rooms carried on the Orbit network. Join by link with nothing to install, or put a room inside your own page with one script tag. |
| [Stream](https://orbit.yunzheng.space/stream/) | Publish a live broadcast over RTMPS from the software you already use; viewers watch over HLS, delivered from the same edge that serves every Orbit site. |
| [VOD](https://orbit.yunzheng.space/vod/) | Upload a video once. It is transcoded on our own nodes into a ladder of qualities and served from vod.yunzheng.space, on the same edge as every Orbit site. |
| [Talk](https://orbit.yunzheng.space/talk/) | Add chat to a product or a broadcast with one script tag. Conversations keep history; live chat keeps the last few hundred lines. Free to start. |
| [Mail](https://orbit.yunzheng.space/mail/) | Mailboxes, groups and aliases on your own domain, a complete web mailbox for everyone in the organisation, and one console to run it. Free for personal use. |
| [Meet](https://orbit.yunzheng.space/meet/) | Video meetings in the browser: waiting room, screen sharing, captions, breakout rooms, polls and recordings, with organisation policies in one console. |
| [V-Gate](https://orbit.yunzheng.space/vgate/) | A hosted phone system for your organisation: extensions, IVR menus, ring groups, queues, business hours and voicemail, answered in a browser or on desk phones. |

## Apps built on Orbit

| App | What it is |
|---|---|
| [YunZheng Voice](https://yunzheng.space/service/voice) | A phone in your browser: calls on your extension, voicemail, call history, forwarding and queue sign-in, plus a free number that rings all your devices. |
| [YunZheng Meet](https://yunzheng.space/service/meet) | Free online meetings in your browser: no download, guests join from a link. Waiting room, screen sharing, live captions, breakout rooms, polls and cloud recording. |
| [YunZheng Mail](https://yunzheng.space/service/mail) | Web mail on your own domain: conversations, labels, filters, undo send, snooze, search, shared mailboxes and groups. Free for personal use. |

## For developers

- [Orbit API](https://orbit.yunzheng.space/docs/api/): one REST API for everything the console does, with an OpenAPI document generated from the server's own route table.
- [orbit-vgate-examples](https://github.com/yunzheng2006/orbit-vgate-examples): runnable examples for the phone system API (list extensions, import them from CSV, export call logs, Voice numbers).

## Compared with

YunZheng Voice: [Google Voice](https://yunzheng.space/service/voice/google-voice-alternative) · [RingCentral](https://yunzheng.space/service/voice/ringcentral-alternative) · [Zoom Phone](https://yunzheng.space/service/voice/zoom-phone-alternative) · [Microsoft Teams Phone](https://yunzheng.space/service/voice/teams-phone-alternative) · [FreePBX](https://yunzheng.space/service/voice/freepbx-alternative) · [Asterisk](https://yunzheng.space/service/voice/asterisk-alternative) · [FreeSWITCH](https://yunzheng.space/service/voice/freeswitch-alternative)

YunZheng Meet: [Zoom](https://yunzheng.space/service/meet/zoom-alternative) · [Google Meet](https://yunzheng.space/service/meet/google-meet-alternative)

---

## 中文

Orbit 是 [芸峥实验室 YunZheng LAB](https://yunzheng.space/zh/)(AS204921)的网络与通信平台:anycast DNS、公共解析、站点边缘网络,以及面向组织的语音、视频、聊天、邮箱与电话系统。非商业用途免费。

**官网:** [orbit.yunzheng.space/zh](https://orbit.yunzheng.space/zh/) · **控制台:** [dash.yunzheng.space](https://dash.yunzheng.space/) · **文档:** [orbit.yunzheng.space/zh/docs](https://orbit.yunzheng.space/zh/docs/)

### 产品

DNS 托管与 Shield(站点前的边缘网络)见 [Orbit 首页](https://orbit.yunzheng.space/zh/)。

| 产品 | 简介 |
|---|---|
| [Public Resolver](https://orbit.yunzheng.space/zh/public-resolver/) | 免费 anycast 公共 DNS:177.177.83.83 不过滤,177.177.83.84 过滤广告与恶意域名,177.177.83.64 提供 DNS64。支持 DoH / DoT / DoQ,不记录查询。 |
| [RPKI](https://orbit.yunzheng.space/zh/rpki/) | 面向自有地址段网络的 RPKI 托管服务:控制台创建 ROA,经我们的仓库发布,RTR 端点直接为路由器供数。免费额度为 1 个证书颁发机构、50 条 ROA。 |
| [Verify](https://orbit.yunzheng.space/zh/verify/) | Orbit Verify:表单验证码的替代方案。大多数访客无感通过,风险分较高时才弹出一次点击,不设 cookie、不追踪,非商业用途免费。 |
| [Link](https://orbit.yunzheng.space/zh/link/) | 在源站运行一个连接器,主动向 Orbit 边缘建立一条出站连接;Shield 通过它回源。源站无需开放入站端口,也不需要公网地址。 |
| [Pages](https://orbit.yunzheng.space/zh/pages/) | 上传一个目录,即可由我们所有节点分发,跑在你自己的域名上,自带证书与 Shield 同一套规则。最多 2 个项目免费,另有边缘缓存与全节点复制两档可选。 |
| [Realtime](https://orbit.yunzheng.space/zh/realtime/) | 跑在 Orbit 网络上的语音与视频房间。用一条链接加入,不需要安装任何东西;也可以用一行 script 标签把房间放进你自己的页面。 |
| [Stream](https://orbit.yunzheng.space/zh/stream/) | 用你已经在用的推流软件通过 RTMPS(加密版 RTMP)推送直播,观众在浏览器里通过 HLS 观看,由分发 Orbit 全部站点的同一张边缘网络送达。 |
| [VOD](https://orbit.yunzheng.space/zh/vod/) | 上传一次视频。它在我们自己的节点上转码成一套清晰度梯度,由承载全部 Orbit 站点的同一张边缘网络,从 vod.yunzheng.space 分发。 |
| [Talk](https://orbit.yunzheng.space/zh/talk/) | 一个 script 标签给产品或直播加上聊天。普通会话保留历史,直播聊天只留最近几百条。免费起步:两个会话、二十人同时在线。 |
| [Mail](https://orbit.yunzheng.space/zh/mail/) | 在你自己的域名上开通邮箱、群组与别名,组织里每个人都有完整的网页邮箱,一个控制台统一管理。个人使用免费。 |
| [Meet](https://orbit.yunzheng.space/zh/meet/) | 浏览器里的视频会议:等候室、共享屏幕、实时字幕、分组讨论室、投票与录制,组织级策略在一个控制台里设置。 |
| [V-Gate](https://orbit.yunzheng.space/zh/vgate/) | 托管的企业电话系统:分机、IVR 语音菜单、振铃组、队列、营业时间、语音信箱与录音,在浏览器或桌面话机上接听。 |

### 基于 Orbit 的应用

| 应用 | 简介 |
|---|---|
| [YunZheng 语音](https://yunzheng.space/service/voice.zh) | 浏览器里的电话：用分机拨打、接听来电、语音信箱、通话记录、呼叫转移与队列签入，外加一个同时呼叫你所有设备的免费号码。 |
| [YunZheng 会议](https://yunzheng.space/service/meet.zh) | 免费的网页在线会议：无需下载，来宾凭链接加入。等候室、屏幕共享、实时字幕、分组讨论、投票与云端录制。 |
| [YunZheng 邮箱](https://yunzheng.space/service/mail.zh) | 使用你自己域名的网页邮箱：会话、标签、过滤器、撤销发送、延后、搜索、共享信箱与邮件组。个人使用免费。 |

---

Text and names in this repository: © 2026 YunZheng LAB. The names Orbit and YunZheng and their logos are not licensed for reuse.
