CFLAGS += -I../libarchive -I../libarchive_fe

LDFLAGS += -L../libarchive -L../libarchive_fe

PROG = bsdcpio

SRCS = cpio.c cmdline.c

DPADD = ../libarchive/libarchive.a ../libarchive_fe/libarchive_fe.a

LDADD = -larchive -larchive_fe -lz -lbz2 -llzma

.include <bsd.prog.mk>
