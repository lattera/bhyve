# $FreeBSD$

KMOD=		dtraceall
SRCS=		dtraceall.c opt_compat.h

CFLAGS+=	-I${.CURDIR}/../../..

.if !defined(KERNBUILDDIR)
.if ${MACHINE_ARCH} == "amd64"
opt_compat.h:
	echo "#define COMPAT_FREEBSD32 1" >> ${.TARGET}
.endif
.endif

.include <bsd.kmod.mk>
