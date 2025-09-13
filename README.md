# tmux.conf
デフォルトでは、tmux はユーザ毎の設定として ~/.tmux.conf を探します。しかし、~/.config/tmux/tmux.conf も使用可能です (このパスはハードコードされていて、$XDG_CONFIG_HOME は無視されます)。グローバルな設定ファイルは /etc/tmux.conf を使用できます。しかし、デフォルトでは Arch のパッケージはこのファイルを同梱していません。

tmux.confとはtmuxの設定ファイルのことで、.tmux.confと書く人もいます。
設定ファイルの置く場所は

~/.tmux.conf
or

~/.config/tmux/tmux.conf
です。

可能な限りホームディレクトリを綺麗にして置きたいので私は後者に配置してます。

