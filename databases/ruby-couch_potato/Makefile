# $OpenBSD: Makefile,v 1.11 2012/09/23 16:57:32 jeremy Exp $

COMMENT =	CouchDB persistence layer written in Ruby

DISTNAME =	couch_potato-0.2.12
REVISION =	5
CATEGORIES =	databases

HOMEPAGE =	https://github.com/langalex/couch_potato/

# MIT
PERMIT_PACKAGE_CDROM = Yes

MODULES =		lang/ruby
BUILD_DEPENDS =		${RUN_DEPENDS}
RUN_DEPENDS =		devel/ruby-activesupport,${MODRUBY_FLAVOR} \
			databases/ruby-couchrest,${MODRUBY_FLAVOR} \
			databases/ruby-validatable,${MODRUBY_FLAVOR}

CONFIGURE_STYLE =	ruby gem

.include <bsd.port.mk>
