# simple usb automount

Really simple usb storage device auto mounter.

Mounts your usb devices automatically when you insert them at `/usb/<device>`.
For example: `/dev/sdb3` will be mounted at `/usb/sdb3`.

Does not come with the bloat desktop managers come with.

### Install

##### Arch Linux

```bash
git clone https://aur.archlinux.org/simple-usb-automount.git
cd simple-usb-automount
makepkg -i
```

##### Other distros

```bash
sudo ./install
```

### Remove

##### Arch Linux

```bash
sudo pacman -R simple-usb-automount
```

##### Other distros

```bash
sudo ./remove
```

### License

MIT

