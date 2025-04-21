快速入门使用官方教程vimtutor，在网上零散找了一些教程后，会发现还是官方教程最适用，只需要一点英语基础。

直接在VScode中使用vim插件，从而使用vim模式进行打字。

然而有一个问题就是在中文输入法常常造成困扰，常规模式下，英文字母应该是对应指令的，可是会被认为成拼音的一部分。

通过网络搜索以及有人给出过方案，修改配置文件，Linux下可以使用以下指令
IBUS
```
"vim.autoSwitchInputMethod.enable": true,
"vim.autoSwitchInputMethod.defaultIM": "xkb:us::eng",
"vim.autoSwitchInputMethod.obtainIMCmd": "/usr/bin/ibus engine",
"vim.autoSwitchInputMethod.switchIMCmd": "/usr/bin/ibus engine {im}"
```
fcitx5(注意不是fcitx)
```
"vim.autoSwitchInputMethod.enable": true,
"vim.autoSwitchInputMethod.defaultIM": "1",
"vim.autoSwitchInputMethod.obtainIMCmd": "/usr/bin/fcitx5-remote",
"vim.autoSwitchInputMethod.switchIMCmd": "/usr/bin/fcitx5-remote -t {im}"
```
其他系统可参照[这里](https://github.com/daipeihust/im-select#installation)