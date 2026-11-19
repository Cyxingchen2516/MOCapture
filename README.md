# MOCapture

《心灵终结 3.3.6》（Mental Omega 3.3.6）的客户端插件。

## 功能

- 选中的工程师自动寻找最近的可占领建筑
- 选中的步兵自动进驻建筑
- 两个热键：
  - `Ctrl + E`：各自找离自己最近的建筑，目标互不重复
  - `Ctrl + R`：全部前往同一栋（离队伍中心最近的）

## 配置

```ini
[Capture]
Enable=1
HotkeyA=Ctrl+E
HotkeyB=Ctrl+R
EngineerTypes=   ; 额外补充工程师类型 ID（内置已含 ENGINEER/SENGINEER/YENGINEER/FENGINEER）
Log=1
```
## 安装

1. 需要先安装 [Syringe](https://github.com/Ares-Developers/Syringe)（心灵终结自带）。
2. 把本目录下的文件放进游戏根目录（`gamemd.exe` 所在目录）。
3. 启动游戏即可。删除文件即卸载。

## 说明

- 纯客户端插件：不修改游戏模拟数据、不发送指令，联机时对方无需安装。
