# Created by: ijliao
# $FreeBSD$

PORTNAME=	PDFLib
PORTVERSION=	0.14
PORTREVISION=	1
CATEGORIES=	print perl5
MASTER_SITES=	CPAN
PKGNAMEPREFIX=	p5-

MAINTAINER=	perl@FreeBSD.org
COMMENT=	More OO interface to pdflib_pl.pm

BUILD_DEPENDS=	pdflib-perl>=0:print/pdflib-perl
RUN_DEPENDS:=	${BUILD_DEPENDS}

USES=		perl5
USE_PERL5=	configure
NO_BUILD=	yes

.include <bsd.port.mk>
