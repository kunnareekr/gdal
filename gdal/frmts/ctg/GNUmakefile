
include ../../GDALmake.opt

OBJ	=	ctgdataset.o

CPPFLAGS	:=	 $(CPPFLAGS) $(XTRA_OPT)

default:	$(OBJ:.o=.$(OBJ_EXT))

clean:
	rm -f *.o

all:	$(OBJ:.o=.$(OBJ_EXT))

install-obj:	$(O_OBJ:.o=.$(OBJ_EXT))
