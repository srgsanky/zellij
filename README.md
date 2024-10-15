# Zellij config

```bash
git clone https://github.com/srgsanky/zellij ~/.config/zellij
```

## Quicklinks

1. Layout <https://zellij.dev/documentation/creating-a-layout>

### Plugins

#### zjstatus

```bash
git clone https://github.com/dj95/zjstatus.git ~/.zellij/plugins/zjstatus

cd ~/.zellij/plugins/zjstatus/
rustup target add wasm32-wasip1
cargo build --release
```

Open zellij and click on the text at the bottom using mouse to accept the permissions request with
y. <https://github.com/dj95/zjstatus/wiki/2-%E2%80%90-Permissions>

Configuration <https://github.com/dj95/zjstatus/wiki/3-%E2%80%90-Configuration>

## Troubleshooting

Find `zellij.log` location in Mac using `find /private/var/folders -name zellij.log 2>/dev/null`

<https://github.com/zellij-org/zellij/discussions/3679>
