#
# A Makefile for ATTRIB
# (c) osFree project,
#

PROJ = attrib
TRGT = $(PROJ).exe
DESC = Changes file attributes
#defines object file names in format $(p)objname$(e)
srcfiles = $(p)attrib$(e)
# defines additional options for C compiler
ADD_COPT = -i=$(MYDIR)..$(SEP)include
UNI2H = 0

!include $(%ROOT)tools/mk/appsdual.mk

.c: $(MYPATH)..
