# Created by: Joe Maloney <jmaloney@ixsystems.com>
# $FreeBSD$

PORTNAME=	personacrypt
PORTVERSION=	%%CHGVERSION%%
CATEGORIES=	sysutils

MAINTAINER=	jmaloney@ixsystems.com
COMMENT=	Home directory encryption on external devices

LICENSE=	BSD2CLAUSE

RUN_DEPENDS=	pefs-kmod>=0:sysutils/pefs-kmod

WRKSRC_SUBDIR=  src-sh
USES=		pkgconfig tar:xz
MAKE_ARGS=	PREFIX=${STAGEDIR}${PREFIX}

USE_GITHUB=	yes
GH_ACCOUNT=	trueos
GH_PROJECT=	personacrypt
GH_TAGNAME=	%%GHTAG%%

.include <bsd.port.mk>
