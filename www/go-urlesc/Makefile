# $NetBSD: Makefile,v 1.19 2020/09/03 07:29:34 bsiegert Exp $

DISTNAME=	urlesc-0.0.0.20170810
PKGNAME=	go-${DISTNAME}
PKGREVISION=	18
MASTER_SITES=	${MASTER_SITE_GITHUB:=PuerkitoBio/}
CATEGORIES=	www
GITHUB_PROJECT=	urlesc
GITHUB_TAG=	de5bf2ad457846296e2031421a34e2568e304e35

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://github.com/PuerkitoBio/urlesc
COMMENT=	Proper URL escaping as per RFC3986
LICENSE=	modified-bsd

GO_DIST_BASE=	urlesc-${GITHUB_TAG}
GO_SRCPATH=	github.com/PuerkitoBio/urlesc

.include "../../lang/go/go-package.mk"
.include "../../mk/bsd.pkg.mk"
