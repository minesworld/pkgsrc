# $NetBSD: Makefile,v 1.40 2020/08/18 17:57:52 leot Exp $

DISTNAME=	kblackbox-${KAPPSVER}
PKGREVISION=	2
CATEGORIES=	games

HOMEPAGE=	https://kde.org/applications/games/kblackbox/
COMMENT=	Find the balls hidden in the black box by shooting laser beams
LICENSE=	gnu-gpl-v2 AND gnu-fdl-v1.2

.include "../../meta-pkgs/kde/applications.mk"

BUILD_DEPENDS+=	kdoctools>=5.19.0:../../devel/kdoctools

USE_TOOLS+=	msgmerge

.include "../../games/libkdegames/buildlink3.mk"
.include "../../graphics/hicolor-icon-theme/buildlink3.mk"
.include "../../sysutils/desktop-file-utils/desktopdb.mk"
.include "../../x11/qt5-qtbase/buildlink3.mk"
.include "../../mk/bsd.pkg.mk"
