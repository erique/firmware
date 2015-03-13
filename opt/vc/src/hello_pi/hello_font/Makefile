OBJS=main.o
BIN=hello_font.bin

LDFLAGS+=-lvgfont
LDFLAGS+=$(SDKSTAGE)/usr/lib/arm-linux-gnueabihf/libfreetype.a
LDFLAGS+=$(SDKSTAGE)/usr/lib/arm-linux-gnueabihf/libz.a
LDFLAGS+=$(SDKSTAGE)/usr/lib/arm-linux-gnueabihf/libpng.a

include ../Makefile.include

