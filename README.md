# Evan Pet

Evan 是一个自定义 Codex v2 动画宠物。

## 文件结构

```text
evan/
├── pet.json
└── spritesheet.webp
```

安装时请复制整个 `evan` 文件夹，不要只复制其中的单个文件。

## macOS 安装方法

1. 下载或克隆本仓库。
2. 打开 Finder，按下 `Command + Shift + G`。
3. 输入 `~/.codex/pets` 并按回车。
4. 将整个 `evan` 文件夹复制到该目录。

安装后的路径应为：

```text
~/.codex/pets/evan/pet.json
~/.codex/pets/evan/spritesheet.webp
```

也可以使用终端安装：

```bash
mkdir -p ~/.codex/pets
cp -R ./evan ~/.codex/pets/
```

## Windows 安装方法

1. 下载或克隆本仓库。
2. 打开文件资源管理器。
3. 在地址栏输入 `%USERPROFILE%\.codex\pets` 并按回车。
4. 如果 `pets` 文件夹不存在，请新建该文件夹。
5. 将整个 `evan` 文件夹复制进去。

安装后的路径应为：

```text
%USERPROFILE%\.codex\pets\evan\pet.json
%USERPROFILE%\.codex\pets\evan\spritesheet.webp
```

也可以使用 PowerShell 安装：

```powershell
New-Item -ItemType Directory -Force "$env:USERPROFILE\.codex\pets" | Out-Null
Copy-Item -Recurse -Force ".\evan" "$env:USERPROFILE\.codex\pets\evan"
```

## 在 Codex 中启用 Evan

1. 打开 ChatGPT/Codex 桌面应用。
2. 进入 **Settings → Pets**。
3. 点击 **Refresh**。
4. 在自定义宠物列表中选择 **Evan**。
5. 如果没有立即显示，请完全退出并重新打开桌面应用。

输入 `/pet`，或从命令菜单中选择 **Show pet**，即可显示桌面宠物。

## 动画内容

- 安静待机、眨眼和呼吸
- 向左、向右移动
- 挥手问候
- 亲吻动作
- 等待用户输入
- 平稳的思考动作
- 任务完成后挥手
- 16 个指针视线方向

自定义宠物文件保存在本机，不会自动同步到其他设备。
