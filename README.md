## Update Note
The original code is forked from klever1988. 
Now try to add ttyd and wireguard onto r2s-mini firmware. 

The following is what I have added. 
```bash
          ### try to add wireguard
          CONFIG_PACKAGE_kmod-wireguard=y
          CONFIG_PACKAGE_luci-app-wireguard=y
          CONFIG_PACKAGE_luci-proto-wireguard=y
          CONFIG_PACKAGE_luci-i18n-wireguard-zh-cn=y
          CONFIG_PACKAGE_wireguard=y
          CONFIG_PACKAGE_wireguard-tools=y
          
          # try to add ttyd
          CONFIG_PACKAGE_luci-app-ttyd=y
          CONFIG_PACKAGE_luci-i18n-ttyd-zh-cn=y
          CONFIG_PACKAGE_ttyd=y
          
          # for storage
          CONFIG_PACKAGE_mount-utils=y
          CONFIG_PACKAGE_TAR_BZIP2=y
          CONFIG_PACKAGE_TAR_GZIP=y
          CONFIG_PACKAGE_TAR_XZ=y
          CONFIG_PACKAGE_TAR_ZSTD=y
          CONFIG_PACKAGE_usbutils=y


