# G5200 utils
My utils for SHARP Brian PW-G5200.

## Apply Backlight
[system-backlight@.service](https://www.freedesktop.org/software/systemd/man/systemd-backlight@.service.html) is not works for me in G5200.

This is just a workaround.

### Dependencies

* `bash`
* `getopt`
* `systemd`

### Install

```bash
git clone https://github.com/yanorei32/g5200utils
./apply-backlight install --main-brightness 5 --sub-brightness 0
```

### How it works
It loads configuration from `/etc/apply-backlight/config`.

