# $FreeBSD$

PORTNAME=	simplecov
PORTVERSION=	0.15.1
PORTREVISION=	1
CATEGORIES=	devel rubygems
MASTER_SITES=	RG

MAINTAINER=	ruby@FreeBSD.org
COMMENT=	Powerful configuration library and automatic merging of coverage across test suites

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/MIT-LICENSE

RUN_DEPENDS=	rubygem-docile>=1.1.0:devel/rubygem-docile \
		rubygem-json>=1.8:devel/rubygem-json \
		rubygem-simplecov-html>=0.10.0:textproc/rubygem-simplecov-html

NO_ARCH=	yes
USE_RUBY=	yes
USES=		gem

.include <bsd.port.mk>
