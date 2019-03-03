# runc

- `root` (main.go) - for container state - should be in tmpfs but starts in `/run/runc` by default

- `log` (main.go) - for log location is defaulted to /dev/null