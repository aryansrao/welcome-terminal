# welcome-terminal

A shell script that greets you with a proper welcome screen every time you open a terminal — system info, a clean layout, and a better start to the session than a blinking cursor. Works on both Linux and macOS.

## Install

```bash
git clone https://github.com/aryansrao/welcome-terminal
cd welcome-terminal
./setup.sh
```

The installer copies the script to `~/.local/bin/welcome.sh`, wires it into your shell startup, and also registers a `sysinfo` command for calling the summary on demand. Run `./setup.sh` again to uninstall cleanly.

## What it shows

Hostname, OS and kernel, uptime, and a quick system summary — the `whoami`-and-where-am-I information you would otherwise type three commands to get.

## Stack

Shell script · Linux · macOS

---

Built by [Aryan S Rao](https://github.com/aryansrao). Issues and pull requests are welcome.
