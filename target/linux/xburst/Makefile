#
# Copyright (C) 2009-2011 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

ARCH:=mipsel
BOARD:=xburst
BOARDNAME:=Ingenic XBurst
FEATURES:=jffs2 targz ubifs audio broken
SUBTARGETS:=qi_lb60 n516 n526 id800wt

LINUX_VERSION:=3.8.12

DEVICE_TYPE=other

include $(INCLUDE_DIR)/target.mk

define Target/Description
	Build firmware images for XBurst JZ47x0 based boards.
endef

$(eval $(call BuildTarget))
