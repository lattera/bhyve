# $FreeBSD$

.PATH: ${.CURDIR}/../../../../geom/part

KMOD=	geom_part_ldm
SRCS=	g_part_ldm.c

SRCS+=	bus_if.h device_if.h g_part_if.h

MFILES=	kern/bus_if.m kern/device_if.m geom/part/g_part_if.m

.include <bsd.kmod.mk>
