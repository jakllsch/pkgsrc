# $NetBSD: Makefile,v 1.9 2020/12/04 20:45:28 nia Exp $

PLUGIN=		enigma

MAINTAINER=	taca@NetBSD.org
COMMENT=	Enigma Plugin for Roundcube
PKGREVISION=	1
LICENSE=	gnu-gpl-v3

DEPENDS+=	${PHP_PKG_PREFIX}-pear-Crypt_GPG>=1.4.3:../../security/pear-Crypt_GPG

REPLACE_PHP=	${PLUGIN_DIR}/import_keys.sh

.include "../../mail/roundcube/plugins.mk"
.include "../../lang/python/application.mk"
.include "../../mk/bsd.pkg.mk"
