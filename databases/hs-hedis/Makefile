# Created by:	martin@sugioarto.com
# $FreeBSD$

PORTNAME=	hedis
PORTVERSION=	0.10.1
PORTREVISION=	3
CATEGORIES=	databases haskell

MAINTAINER=	haskell@FreeBSD.org
COMMENT=	Client library for the Redis datastore

LICENSE=	BSD3CLAUSE

DEPRECATED=		Haskell libraries are getting pushed out of the ports tree. If you are using this port for development, consider switching to cabal sandboxes (old way), cabal new-build (new way), or use devel/stack. If you believe this port shouldn't be removed, contact haskell@FreeBSD.org
EXPIRATION_DATE=	2019-04-14

USE_CABAL=	async bytestring-lexing errors HTTP mtl network network-uri \
		resource-pool scanner unordered-containers vector

.include "${.CURDIR}/../../lang/ghc/bsd.cabal.mk"
.include <bsd.port.mk>
