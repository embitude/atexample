AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic -O2
include_HEADERS = atexample.h

lib_LTLIBRARIES = libatexample.la
libatexample_la_SOURCES  = atexamplelib.c
libatexample_la_LDFLAGS= -version-info 1:0:0

bin_PROGRAMS = atexample
atexample_SOURCES = atexample.c
atexample_LDADD = libatexample.la
