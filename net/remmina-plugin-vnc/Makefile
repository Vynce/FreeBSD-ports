# Created by: Alexander Logvinov <avl@FreeBSD.org>
# $FreeBSD$

PKGNAMESUFFIX=	-vnc

COMMENT=	Remmina plugin for VNC protocol

LIB_DEPENDS=	libgnutls.so:security/gnutls \
		libgcrypt.so:security/libgcrypt \
		libvncserver.so:net/libvncserver

USES=		jpeg
USE_GNOME+=	cairo

MASTERDIR=	${.CURDIR}/../remmina-plugins

.include "${MASTERDIR}/Makefile"
