#
# board/renesas/rzt2h-dev/Makefile
#
# Copyright (C) 2023 Renesas Electronics Corporation
#
# SPDX-License-Identifier: GPL-2.0+
#

ifdef CONFIG_SPL_BUILD
obj-y	:= ../rcar-common/gen3-spl.o
else
obj-y	:= myc-rzt2h.o myc-rzt2h_eth.o ../rcar-common/common.o
endif
