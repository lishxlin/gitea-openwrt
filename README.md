# gitea-openwrt
Gitea on openwrt(armv7)

---

This is gitea 1.17.3, with SQLite support.

## How to use

1.

```
$ cd path/to/your/openwrt-sdk-root/packages
```

2.

```
$ git clone https://github.com/lishxlin/gitea-openwrt.git
```

## Architecture

> If your Openwrt device is armv7 and you want have the best stable experiences, you will do is just follow the offical instruction to download the gitea for armv6.

This Makefile and Release ipk are aim for Armv7l, because this ipk build is for my router, and my router's architecture is armv7l.

If you want build for another architecture, you can just simply edit the Makefile to add support for your target architecture.

## Why issue is closed?
__DON'T MAKE ANY PR,THANKS__

This repo only have a Makefile, I don't want put times on it, only I will do is to update the Makefile when upstream gitea is update, and I will only use stable release.

If you have issue on building the gitea and you're sure your toolchain is working perfactly, go to gitea offical's repo and create an issue.

If you have any problem on toolchain, I suggest you firstly go to your sdk provider's repo to create an issue, and then consider the advice above.

## English grammer error?

Sorry, my english is poor.
