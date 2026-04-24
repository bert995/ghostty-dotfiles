# ghostty-dotfiles

个人 [Ghostty](https://ghostty.org) 配置，方便换机器时一键还原。

## 字体

使用 **Maple Mono NF CN**（Nerd Font 中文版）。新机器需先装字体：

```sh
# 从 GitHub Release 下载 MapleMono-NF-CN 系列 ttf
# https://github.com/subframe7536/maple-font/releases
# 解压后把 ttf 拖进"字体册.app"安装（只装用户级，不要同时装系统级，否则会渲染漂移）
```

## 安装

```sh
git clone git@github.com:<your-user>/ghostty-dotfiles.git ~/ghostty-dotfiles
mkdir -p ~/.config/ghostty
ln -sf ~/ghostty-dotfiles/config ~/.config/ghostty/config
```

改配置直接编辑 `~/ghostty-dotfiles/config`，Ghostty 里 `Cmd+Shift+,` 重新加载。

## 注意事项

- `working-directory` 写死成 `/Users/bytedance/bert995`，换机器记得改。
- 字体别同时装进 `~/Library/Fonts` 和 `/Library/Fonts`，macOS 选字会不稳。
