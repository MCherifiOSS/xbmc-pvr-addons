#
# Makefile for the NextPVR add-on for XBMC PVR
#
# See the README for copyright information and
# how to reach the author.
#

ADDONBINNAME    = Kodi_NextPVR
ADDONNAME       = pvr.nextpvr
LIBNAME         = libnextpvr-addon
lib_LTLIBRARIES = libnextpvr-addon.la

LIBS            = @abs_top_srcdir@/lib/tinyxml/libtinyxml.la

include ../Makefile.include.am

INCLUDES+=-Isrc

libnextpvr_addon_la_SOURCES = src/client.cpp \
                                  src/pvrclient-nextpvr.cpp \
                                  src/Socket.cpp \
                                  src/uri.cpp \
                                  src/md5.cpp \
                                  src/liveshift.cpp \
                                  src/RingBuffer.cpp \
                                  src/DialogRecordPref.cpp
libnextpvr_addon_la_LDFLAGS = @TARGET_LDFLAGS@
