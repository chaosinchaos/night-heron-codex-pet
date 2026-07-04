# Night Heron Codex Pet

一只夜鹭风格的 Codex 自定义宠物。

它包含完整的 Codex pet spritesheet，可以在 Codex Desktop 的宠物功能里使用。

## Preview

宠物文件在 `night-heron/` 文件夹里：

```text
night-heron/
  pet.json
  spritesheet.png
  spritesheet.webp
```

Codex 当前优先使用 `spritesheet.png`。`spritesheet.webp` 也保留在仓库里，方便以后需要更小体积版本时使用。

## Install

1. 点击 GitHub 页面右上角绿色的 `Code` 按钮。
2. 选择 `Download ZIP`。
3. 解压下载的 zip 文件。
4. 找到里面的 `night-heron` 文件夹。
5. 把 `night-heron` 文件夹复制到你的 Codex pets 目录：

```text
~/.codex/pets/
```

最终文件结构应该是：

```text
~/.codex/pets/night-heron/pet.json
~/.codex/pets/night-heron/spritesheet.png
```

6. 完全退出并重启 Codex Desktop。
7. 打开 `Settings → Pets`，选择「夜鹭」。

## If It Does Not Show Up

如果设置页里没有出现「夜鹭」，可以手动指定当前宠物。

打开：

```text
~/.codex/config.toml
```

在 `[desktop]` 下面添加：

```toml
selected-avatar-id = "custom:night-heron"
```

然后重启 Codex Desktop。

## Notes

- 只需要复制 `night-heron` 这个文件夹，不要把整个仓库文件夹直接放进 `~/.codex/pets/`。
- 正确路径是 `~/.codex/pets/night-heron/pet.json`。
- 如果路径变成 `~/.codex/pets/night-heron-codex-pet-main/night-heron/pet.json`，Codex 可能识别不到。
