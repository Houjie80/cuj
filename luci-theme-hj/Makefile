#
# Copyright (C) 2019-2024 The Sirpdboy Team <herboy2008@gmail.com>    
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk
THEME_NAME:hj
THEME_TITLE:=hj Theme
PKG_NAME:=luci-theme-$(THEME_NAME)
LUCI_TITLE:=hj Theme by houjie
LUCI_DEPENDS:=
PKG_VERSION:=1.0.7
PKG_RELEASE:=11032024

define Package/luci-theme-$(THEME_NAME)/postinst
#!/bin/sh

rm -Rf /var/luci-modulecache
rm -Rf /var/luci-indexcache
exit 0

endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
