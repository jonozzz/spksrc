PKG_NAME = nv-codec-headers
PKG_EXT = tar.gz
PKG_DOWNLOAD_METHOD = git
PKG_GIT_HASH = 96a6db0
PKG_DIST_SITE = https://github.com/FFmpeg/nv-codec-headers.git
PKG_DIST_FILE = $(PKG_NAME)-git$(PKG_GIT_HASH).$(PKG_EXT)
PKG_DIR = $(PKG_NAME)-git$(PKG_GIT_HASH)

DEPENDS =

HOMEPAGE = https://git.videolan.org/?p=ffmpeg/nv-codec-headers.git
COMMENT  = "FFmpeg version of headers required to interface with Nvidias codec APIs.."
LICENSE  = AGPLv3

CONFIGURE_TARGET = nop
COMPILE_TARGET = myInstall
INSTALL_TARGET = nop

include ../../mk/spksrc.cross-cc.mk

.PHONY: myInstall
myInstall:
	$(RUN) $(MAKE) install PREFIX=$(STAGING_INSTALL_PREFIX) PREFIXX=
