SPK_NAME = borgbackup
SPK_VERS = 1.1.9
SPK_REV = 5
SPK_ICON = src/$(SPK_NAME).png

BUILD_DEPENDS = cross/python3 cross/setuptools cross/pip cross/wheel
BUILD_DEPENDS += cross/$(SPK_NAME)
DEPENDS = cross/bash cross/acl cross/attr
WHEELS = src/requirements.txt
SPK_DEPENDS = "python3>=3.7.7"

MAINTAINER = SynoCommunity
DESCRIPTION = Deduplicating backup program with compression and authenticated encryption.
RELOAD_UI = no
DISPLAY_NAME = Borg
STARTABLE = no
CHANGELOG = Update to 1.1.9

HOMEPAGE = https://borgbackup.readthedocs.io
LICENSE  = BSD-3-Clause

SERVICE_SETUP = src/service-setup.sh
SPK_LINKS = /usr/local/bin/borg:env/bin/borg /usr/local/bin/borgmatic:env/bin/borgmatic

include ../../mk/spksrc.spk.mk
