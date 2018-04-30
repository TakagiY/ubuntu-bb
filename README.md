# install

```
cd /usr/share/plymouth/themes
```

Clone this.

```
sudo git clone https://github.com/TakagiY/ubuntu-bb.git
```

Install.

```
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/ubuntu-bb/ubuntu-bb.plymouth 100
```

Then select defalut theme.

```
sudo update-alternatives --config default.plymouth
```

Update the initramfs image.

```
sudo update-initramfs -u
```
