# $NetBSD: Makefile,v 1.24 2020/08/31 18:13:01 wiz Exp $

DISTNAME=	Kwiki-Search-0.12
PKGNAME=	p5-${DISTNAME}
PKGREVISION=	13
CATEGORIES=	www perl5
MASTER_SITES=	${MASTER_SITE_PERL_CPAN:=Kwiki/}

MAINTAINER=	pkgsrc-users@NetBSD.org
#HOMEPAGE=	http://www.kwiki.org/
COMMENT=	Kwiki search plugin

DEPENDS+=	p5-Kwiki>=0.34:../../www/p5-Kwiki

PERL5_PACKLIST=		auto/Kwiki/Search/.packlist

MAKE_ENV+=	PERL_USE_UNSAFE_INC=1

.include "../../lang/perl5/module.mk"
.include "../../mk/bsd.pkg.mk"
