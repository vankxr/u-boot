# SPDX-License-Identifier: GPL-2.0

obj-y	:= board.o
obj-y	+= ../../xilinx/common/board.o

obj-$(CONFIG_SPL_BUILD) += ps7_init_gpl.o

# Suppress "warning: function declaration isn't a prototype"
CFLAGS_REMOVE_ps7_init_gpl.o := -Wstrict-prototypes
