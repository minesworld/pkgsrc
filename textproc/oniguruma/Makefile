# $NetBSD: Makefile,v 1.18 2020/10/07 21:27:17 kim Exp $

DISTNAME=	onig-6.9.6-rc1
PKGNAME=	${DISTNAME:S/onig/oniguruma/:S/-rev/pl/:S/-rc/rc/}
CATEGORIES=	textproc devel
MASTER_SITES=	${MASTER_SITE_GITHUB:=kkos/}
GITHUB_PROJECT=	oniguruma
GITHUB_RELEASE=	v${DISTNAME:S/onig-//:S/-/_/}

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://github.com/kkos/oniguruma
COMMENT=	Regular expressions library
LICENSE=	2-clause-bsd

WRKSRC=		${WRKDIR}/${DISTNAME:C/-rev..*//:C/-rc..*//}

USE_LIBTOOL=		yes
GNU_CONFIGURE=		yes

CONFIGURE_ARGS+=	--enable-binary-compatible-posix-api=yes

PKGCONFIG_OVERRIDE=	oniguruma.pc.in
TEST_TARGET=		check

.include "../../mk/bsd.pkg.mk"
