<SPAN ID = 'HEAD'/>

<div align="center">
<img src="Images/WCC2024_2.png" width = "12%" /><img src="Images/LING_2.png" width = "25%" /><img src="Images/WCC2024_1.png" width = "12%" />
</div>


<h1 align="center">灵糕中心 (Linggao Hub)</h1>

[github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB) (GitHub)

&emsp;&emsp;**用于跟踪 “Windows 11 预览体验版本 (Canary 频道) 中哪些反馈正在由 Microsoft 调查、处理 / 已做出更改” 的信息枢纽**。由 2021 Windows Insider 最有价值专家 (MVP) · **Ling Gao** 先生管理。

&emsp;&emsp;灵糕中心成立于 2023 年 12 月 12 日，其前身可追溯至 2019 年 5 月 14 日由 Microsoft 社区创建的 “[\[BUG 汇总\] Windows 10 2019 年 5 月更新 (1903_18362) 已知问题与处理进度汇总](https://answers.microsoft.com/zh-hans/insider/forum/all/bug-%E6%B1%87%E6%80%BBwindows-10-2019-%E5%B9%B4-5/252d0d6a-022c-4bf7-9976-55b57590aee2)” 讨论话题。

> [!IMPORTANT]
>
> &emsp;灵糕中心为个人项目，管理者不是 Microsoft 公司员工，不能代表 Microsoft 公司立场、态度。中心无意且无法代替 “反馈中心” (Feedback Hub) 应用的重要作用。中心不提供 Microsoft 产品技术支持服务。中心不接受有关 Windows 11 预览体验版本的反馈，用户应始终通过 “反馈中心” 应用提交。
>
> &emsp;Windows、Windows Insider Program 等是 Microsoft 公司的商标。

&emsp;&emsp;**宗旨**：独立管理、服务用户、信息精准、更新及时

[反馈中心](https://aka.ms/fbh) | [深入了解反馈](https://learn.microsoft.com/zh-cn/windows-insider/feedback) | [Flight Hub](https://learn.microsoft.com/en-us/windows-insider/flight-hub) | Windows 预览体验计划 - [网站](https://www.microsoft.com/zh-cn/windowsinsider) · [博客](https://blogs.windows.com/windows-insider) · [X](https://twitter.com/windowsinsider) · Microsoft 社区 ([中](https://answers.microsoft.com/zh-hans/insider/forum) / [英](https://answers.microsoft.com/en-us/insider/forum))

## ✦ 总览 ✦

&emsp;&emsp;上次更新时间：2024 年 10 月 9 日 12:00 (UTC+8)。访问次数：6030+

&emsp;&emsp;收录反馈 227 个，其中正在调查 8 个 (含[搁置](#3) 2 个)、正在处理 3 个、已修复 216 个。

&emsp;&emsp;反馈更新记录：**今日更新 LG223 - 226**。- Ling 📉 [总览图](https://raw.githubusercontent.com/Lingggao/LGHUB/main/Images/Linggao%20Hub.png) | [反馈更新记录](Documents/Update_Feedback.md) | [平台更新记录](Documents/Update_Platform.md)

|  🎖️ **推 荐**   | [**Microsoft 电脑管家**](https://pcmanager.microsoft.com) 产品 |  [**Microsoft WowTab**](https://wowtab.microsoft.com) 产品   |
| :------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|                | **Windows 预览体验计划 - [信息 & 日志 & 链接](https://answers.microsoft.com/zh-hans/insider/forum/all/windows/2a5add38-c6d9-4c9d-958d-7451f7632b1c)** |                                                              |
| 🏅 **友情推荐** | **[WinDiscover](https://windiscover.com) - 独立 Microsoft 新闻博客** | **关注 [@Microsoft 信仰中心](https://weibo.com/u/3139784387) 微博** |
|                | **[Windows Up-to-Date](https://wutd.crrashh.com) - Windows 实时版本** |                                                              |

|         频道         |              最新版本               | 时间 (UTC+8) |                             公告                             |
| :------------------: | :---------------------------------: | :----------: | :----------------------------------------------------------: |
|        Canary        |                27718                |  2024/10/3  | [aka.ms/wip27718](https://blogs.windows.com/windows-insider/2024/10/02/announcing-windows-11-insider-preview-build-27718-canary-channel) |
|         Dev          |              26120.1930              |   2024/10/5   | [aka.ms/wip-dev-10-4](https://blogs.windows.com/windows-insider/2024/10/04/announcing-windows-11-insider-preview-build-26120-1930-dev-channel) |
|         Beta         | 22635.4300 *(23H2)* |   2024/10/5   | [aka.ms/wip-beta-10-4](https://blogs.windows.com/windows-insider/2024/10/04/announcing-windows-11-insider-preview-build-22635-4300-beta-channel) |
|   Release Preview    | 26100.1882 |  2024/10/1  | [support.microsoft.com](https://support.microsoft.com/help/5043178) |
| General Availability |    **[新]** 26100.2033    |  2024/10/9  | [support.microsoft.com](https://support.microsoft.com/help/5044284) |

<img src="Images/Graph_0.png" width = "93%" />

统计图 - 2024 年 | [1 - 4 月](Images/Graph_2401_2404.png) · [5 - 8 月](Images/Graph_2405_2408.png) · [9 - 12 月](Images/Graph_0.png)

---

> [!NOTE]
>
> &emsp;多数问题是仅有 1 - 2 位 Insiders 反馈的 “偶发性” 问题，而非所有人都会遇到的 “广泛性” 问题。请放心地更新 Windows 11 预览体验版本，不必担心新版使用体验过差。

|      编号       |                             问题                             |   状态   |
| :-------------: | :----------------------------------------------------------: | :------: |
|     **——**      |            [**Canary - 公告已知问题**](#0) **▼**             |  **——**  |
| [LG212](#LG212) | 在 Copilot+ 设备上加入 Canary 频道后，PIN 和生物识别信息将会丢失。 | 正在处理 |
| [LG221](#LG221) |         无法在 “电影和电视” 应用中播放已购买的内容。         | 正在处理 |
| [LG222](#LG222) | 表情符号面板 & 剪贴板历史记录无法在部分窗口内 (如注册表) 打开。 | 正在处理 |
|     **——**      | [**Canary - 公告已知问题**](#0) **▲ \| ▼** [**Canary - 用户反馈问题**](#1) |  **——**  |
| [LG215](#LG215) |       在 Canary 版本中，“设置” 菜单显示版本号为 Dev。        | 正在调查 |
| [LG216](#LG216) |         在以管理员权限运行的应用中无法使用触摸键盘。         | 正在调查 |
| [LG223](#LG223) |          **运行 SFC /scannow 命令时可能显示错误**。          | 正在调查 |
| [LG224](#LG224) |               **Solitaire (纸牌) 游戏崩溃**。                | 正在调查 |
| [LG225](#LG225) |      **文件资源管理器 “...” 二级菜单无法向下方弹出**。       | 正在调查 |
| [LG226](#LG226) |             **剪贴板历史记录可能始终显示为空**。             | 正在调查 |
|     **——**      | [**Canary - 用户反馈问题**](#1) **▲ \| ▼** [**Canary - 归档 (已做出更改 0 - 7 天)**](#2) |  **——**  |
| [LG220](#LG220) |       Windows 更新失败自动回退，显示 0xC1900101 错误。       | 已修复 ✓ |
| [LG202](#LG202) |               表情符号面板可能意外地自动关闭。               | 已修复 ✓ |
| [LG178](#LG178) |          任务管理器设置菜单 Mica (云母) 效果异常。           | 已修复 ✓ |
| [LG207](#LG207) |                   截图工具可能挂起或闪退。                   | 已修复 ✓ |
| [LG211](#LG211) |                      鼠标光标随机卡住。                      | 已修复 ✓ |
| [LG214](#LG214) |         “设置” 菜单最小化时，有时无法从任务栏打开。          | 已修复 ✓ |
| [LG217](#LG217) |           Microsoft Edge (Canary 频道) 频繁崩溃。            | 已修复 ✓ |
| [LG218](#LG218) |                输入法的文本建议可能出现重叠。                | 已修复 ✓ |
| [LG219](#LG219) |          出现覆盖 2/3 桌面且无法移除的白色空窗口。           | 已修复 ✓ |
|     **——**      |     **▲** [**Canary - 归档 (已做出更改 0 - 7 天)**](#2)      |  **——**  |
|     **——**      | **✦** [**Canary - 归档 (已做出更改 >7 天)**](7+.md) **✦ \| ✦** [**Canary - 搁置 (未做出更改)**](#3) **✦** |  **——**  |

[分享反馈线索](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUNjUyUzJLN0JBREZGMzBBVlpVOEVBQkRENy4u) | [反馈平台问题](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAO__Q3sH7RUQ0haOElMVkxOWDE4U1pHQUZWMDhEM1gwSC4u)

<SPAN ID = '0'/>

## ✦ Canary - 公告已知问题 ✦

> [!TIP]
>
> &emsp;记录 [Windows Insider 博客](https://blogs.windows.com/windows-insider)中明确公开的已知问题。

---

<SPAN ID = 'LG212'/>编号：LG212  
日期：2024 年 8 月 16 日  
版本：Canary 27686 - 27718  
**问题**：**在 Copilot+ 设备上加入 Canary 频道后，PIN 和生物识别信息将会丢失**。  
状态：<img src="Images/W.png" width = "9%" />  
Microsoft 官方回复：“如果您使用 Copilot+ 设备从 Dev、Release Preview 或 Retail 频道加入至 Canary 频道，Windows Hello PIN 和生物识别信息将会丢失。您将无法登录系统，显示 0xd0000225 错误和 ‘出错了，您的 PIN 不可用’ 信息。点击 ‘设置我的 PIN’ 选项应当可以重设 PIN。” *(Ling 译)* <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG221'/>编号：LG221  
日期：2024 年 10 月 3 日  
版本：Canary 27718  
**问题**：**无法在 “电影和电视” 应用中播放已购买的内容**。  
状态：<img src="Images/W.png" width = "9%" />  
Microsoft 官方回复：“此问题很快将在未来的版本中得到修复。” *(Ling 译)* <img src="Images/M.png" width = "14%" />

---

<SPAN ID = 'LG222'/>编号：LG222  
日期：2024 年 10 月 3 日  
版本：Canary 27718  
**问题**：**表情符号面板 & 剪贴板历史记录无法在部分窗口内 (如注册表) 打开**。  
状态：<img src="Images/W.png" width = "9%" />

<SPAN ID = '1'/>

## ✦ Canary - 用户反馈问题 ✦

> [!TIP]
>
> &emsp;记录[反馈中心应用](https://aka.ms/fbh)中 Microsoft 明确响应的问题。

---

<SPAN ID = 'LG215'/>编号：LG215  
日期：2024 年 8 月 23 日  
版本：Canary 27686 - 27718  
**问题**：**在 Canary 版本中，“设置” 菜单显示版本号为 Dev**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AArxpls](https://aka.ms/AArxpls)

<img src="Images/LG215.png" width = "50%" />

---

<SPAN ID = 'LG216'/>编号：LG216  
日期：2024 年 8 月 31 日  
版本：Canary 27686 - 27718  
**问题**：**在以管理员权限运行的应用中无法使用触摸键盘**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAs448c](https://aka.ms/AAs448c)

<img src="Images/LG216.png" width = "50%" />

---

<SPAN ID = 'LG223'/>编号：LG223  
日期：2024 年 10 月 9 日  
版本：Canary 27718  
**问题**：**运行 SFC /scannow 命令时可能显示错误**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAso1q0](https://aka.ms/AAso1q0)

---

<SPAN ID = 'LG224'/>编号：LG224  
日期：2024 年 10 月 9 日  
版本：Canary 27718  
**问题**：**Solitaire (纸牌) 游戏崩溃**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAspbva](https://aka.ms/AAspbva)

---

<SPAN ID = 'LG225'/>编号：LG225  
日期：2024 年 10 月 9 日  
版本：Canary 27718  
**问题**：**文件资源管理器 “...” 二级菜单无法向下方弹出**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAspbvg](https://aka.ms/AAspbvg)

<img src="Images/LG225.png" width = "55%" />

---

<SPAN ID = 'LG226'/>编号：LG226  
日期：2024 年 10 月 9 日  
版本：Canary 27718  
**问题**：**剪贴板历史记录可能始终显示为空**。  
状态：<img src="Images/L.png" width = "9%" />  
典型反馈：[aka.ms/AAsohjn](https://aka.ms/AAsohjn)

<SPAN ID = '2'/>

## ✦ Canary - 归档 (已做出更改) ✦

> [!TIP]
>
> &emsp;记录 Microsoft 已做出更改 0 - 7 天的问题 & 超过 14 天无新增赞成票的问题。
>
> &emsp;无特殊情况，问题归档后不再更新。

---

<SPAN ID = 'LG220'/>编号：LG220  
日期：2024 年 9 月 7 日  
版本：Canary 27686 - 27695  
**问题**：**Windows 更新失败自动回退，显示 0xC1900101 错误**。  
状态：Canary 27718 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓

---

<SPAN ID = 'LG202'/>编号：LG202  
日期：2024 年 7 月 25 日  
版本：Canary 26257 - 27695  
**问题**：**表情符号面板可能意外地自动关闭**。  
状态：Canary 27718 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓

---

<SPAN ID = 'LG178'/>编号：LG178  
日期：2024 年 6 月 9 日  
版本：Canary 26231 - 27695  
**问题**：**任务管理器设置菜单 Mica (云母) 效果异常**。  
状态：Canary 27718 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAqsxwz](https://aka.ms/AAqsxwz)

<img src="Images/LG178.png" width = "45%" />

---

<SPAN ID = 'LG207'/>编号：LG207  
日期：2024 年 8 月 3 日  
版本：Canary 26257 - 27695  
**问题**：**截图工具可能挂起或闪退**。  
状态：Canary 27718 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAroi77](https://aka.ms/AAroi77)

---

<SPAN ID = 'LG211'/>编号：LG211  
日期：2024 年 8 月 14 日  
版本：Canary 26257 - 27695  
**问题**：**鼠标光标随机卡住**。  
状态：Canary 27718 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AArterh](https://aka.ms/AArterh)

---

<SPAN ID = 'LG214'/>编号：LG214  
日期：2024 年 8 月 23 日  
版本：Canary 27686 - 27695  
**问题**：**“设置” 菜单最小化时，有时无法从任务栏打开**。  
状态：Canary 27718 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAry4xh](https://aka.ms/AAry4xh)

---

<SPAN ID = 'LG217'/>编号：LG217  
日期：2024 年 9 月 4 日  
版本：Edge Canary  
**问题**：**Microsoft Edge (Canary 频道) 频繁崩溃**。  
状态：Edge Canary - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAs5n7h](https://aka.ms/AAs5n7h)

---

<SPAN ID = 'LG218'/>编号：LG218  
日期：2024 年 9 月 7 日  
版本：Canary 27695  
**问题**：**输入法的文本建议可能出现重叠**。  
状态：Canary 27718 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAs4l8k](https://aka.ms/AAs4l8k)

---

<SPAN ID = 'LG219'/>编号：LG219  
日期：2024 年 9 月 7 日  
版本：Canary 27695  
**问题**：**出现覆盖 2/3 桌面且无法移除的白色空窗口**。  
状态：Canary 27718 - <img src="Images/C_0.png" width = "10%" /> - 已修复 ✓  
典型反馈：[aka.ms/AAs6ojn](https://aka.ms/AAs6ojn)

[Microsoft 已做出更改 >7 天的问题](7+.md)

<SPAN ID = '3'/>

## ✦ Canary - 搁置 (未做出更改) ✦

> [!TIP]
>
> &emsp;“并非所有软件缺陷都要修复。” —— Ron Patton (出自《软件测试》)
>
> &emsp;已收录的反馈也可能因缺少资源、修复风险过大、商业决策调整等长期或永久不予修复。本板块记录 Microsoft 超过 90 天未修复的问题，中心将每间隔 30 天在 Canary 频道最新版本中进行测试。

[Microsoft 超过 90 天未修复的问题](90+.md)

---

[回到顶部](#HEAD)

<img src="https://mirrors.creativecommons.org/presskit/icons/cc.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/by.xlarge.png" width = "3%" /> <img src="https://mirrors.creativecommons.org/presskit/icons/sa.xlarge.png" width = "3%" />

在 “[署名 - 相同方式共享 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.zh-Hans)” 协议 (CC BY-SA 4.0) 之条款下提供。

2023 - 2024, 高楷修 (Ling Gao), 灵糕中心 (Linggao Hub), [github.com/Lingggao/LGHUB](https://github.com/Lingggao/LGHUB)

[字体许可使用授权书](Images/字体许可使用授权书.png) | [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FLingggao%2FLGHUB&count_bg=%23737373&title_bg=%230078D7&icon=microsoft.svg&icon_color=%23FFFFFF&title=LGHUB&edge_flat=false)](https://hits.seeyoufarm.com) (访问次数统计：今日 / 累计)