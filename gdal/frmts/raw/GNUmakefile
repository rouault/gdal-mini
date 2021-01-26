include ../../GDALmake.opt

OBJ	=	ehdrdataset.o envidataset.o gtxdataset.o ntv2dataset.o roipacdataset.o

CXXFLAGS        :=      $(WARN_EFFCPLUSPLUS)  $(CXXFLAGS)

default:	$(OBJ:.o=.$(OBJ_EXT))

clean:
	rm -f *.o $(O_OBJ)

install-obj:	$(O_OBJ:.o=.$(OBJ_EXT))

$(OBJ) $(O_OBJ): ../../gcore/rawdataset.h

install:
