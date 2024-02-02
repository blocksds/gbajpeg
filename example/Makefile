# SPDX-License-Identifier: CC0-1.0
#
# SPDX-FileContributor: Antonio Niño Díaz, 2023

BLOCKSDS	?= /opt/blocksds/core
BLOCKSDSEXT	?= /opt/blocksds/external

# User config

NAME		:= gbajpeg
GAME_TITLE	:= gbajpeg example

NITROFSDIR	:= nitrofs

# Libraries

LIBS		:= -lgbajpeg -lnds9 -lc
LIBDIRS		:= $(BLOCKSDS)/libs/libnds \
		   $(BLOCKSDSEXT)/gbajpeg

include $(BLOCKSDS)/sys/default_makefiles/rom_arm9/Makefile
