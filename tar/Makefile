CFLAGS += -I../libarchive -I../libarchive_fe

LDFLAGS += -L../libarchive -L../libarchive_fe

PROG = bsdtar

SRCS = bsdtar.c  cmdline.c  creation_set.c  read.c  subst.c  util.c  write.c

DPADD += ../libarchive/libarchive.a ../libarchive_fe/libarchive_fe.a

LDADD += -larchive -larchive_fe -lz -lbz2 -llzma

.include <bsd.prog.mk>
