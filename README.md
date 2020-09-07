# lsoc

Overlay for the List of Open Cameras.

![screenshot](scrot.png)

## Install

Dependencies: `go`, `gtk3`, `v4l2`, Linux.

```sh
# Optionally add this to shellrc.
export PATH="$PATH:${GOBIN:-$GOPATH/bin}"

go install github.com/diamondburned/lsoc
```

## Usage

```sh
# Optionally install the default config.json.
cp config.json ~/.config/lsoc.config.json

lsoc [-c ~/.config/lsoc.config.json]
```
