# $NetBSD: Makefile,v 1.6 2020/12/04 20:45:28 nia Exp $

PLUGIN=		zipdownload

MAINTAINER=	taca@NetBSD.org
COMMENT=	Roundcube Webmail ZipDownload plugin
PKGREVISION=	1
LICENSE=	gnu-gpl-v3

DEPENDS+=	${PHP_PKG_PREFIX}-zip>=5.4.0:../../archivers/php-zip

.include "../../mail/roundcube/plugins.mk"
.include "../../lang/python/application.mk"
.include "../../mk/bsd.pkg.mk"
