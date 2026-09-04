# KleoPadre Homebrew Tap

## WispWire

Установка:

```bash
brew install kleopadre/tap/wispwire
wispwire doctor
```

Команда `brew install kleopadre/tap/wispwire` устанавливает WispWire, Python
runtime-зависимости и Wireshark CLI (`tshark`, `dumpcap`, `mergecap`).

На macOS для live-захвата может понадобиться системное разрешение BPF. Если
`wispwire doctor` сообщает, что `dumpcap` не вернул интерфейсы, установите
официальный пакет прав Wireshark:

```bash
brew install --cask wireshark-chmodbpf
```

WispWire — CLI/TUI-приложение. Оно не устанавливает daemon и не использует
`brew services`.
