# $NetBSD: Makefile,v 1.3 2020/09/20 04:41:37 mef Exp $

R_PKGNAME=	lintr
R_PKGVER=	2.0.1
CATEGORIES=	devel

MAINTAINER=	pkgsrc-users@NetBSD.org
COMMENT=	'Linter' for R Code
LICENSE=	mit	# + file LICENSE

DEPENDS+=	R-crayon>=1.3.4:../../devel/R-crayon
DEPENDS+=	R-rex>=1.1.2:../../devel/R-rex
DEPENDS+=	R-testthat>=2.2.1:../../devel/R-testthat
DEPENDS+=	R-rstudioapi>=0.2:../../math/R-rstudioapi
DEPENDS+=	R-knitr>=1.23:../../print/R-knitr
DEPENDS+=	R-digest>=0.6.20:../../security/R-digest
DEPENDS+=	R-jsonlite>=1.6:../../textproc/R-jsonlite
DEPENDS+=	R-xml2>=1.0.0:../../textproc/R-xml2
DEPENDS+=	R-httr>=1.2.1:../../www/R-httr
DEPENDS+=	R-cyclocomp-[0-9]*:../../devel/R-cyclocomp
DEPENDS+=	R-stringdist-[0-9]*:../../math/R-stringdist
DEPENDS+=	R-xmlparsedata-[0-9]*:../../textproc/R-xmlparsedata

TEST_DEPENDS+=	R-testthat-[0-9]*:../../devel/R-testthat
TEST_DEPENDS+=	R-mockery-[0-9]*:../../devel/R-mockery

USE_LANGUAGES=	# none

.include "../../math/R/Makefile.extension"
.include "../../mk/bsd.pkg.mk"
