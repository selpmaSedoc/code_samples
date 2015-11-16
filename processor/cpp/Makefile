CC=g++
CFLAGS=-g -Wall -std=c++11

DINC=
DLIB=
DSRC=src/
DOUT=bin/

SLIB=
SSRC=$(DSRC)bitpack.cpp
TARGET=$(DOUT)parse

#INCS=$(foreach d,$(DINC),-I$(d))
#LIBS=$(foreach s,$(SLIB),$(DLIB)$(s))

all:
	$(CC) $(CFLAGS) -o $(TARGET) $(SSRC) $(LIBS) $(INCS)

.PHONY: clean
clean:
	rm -f *~ $(TARGET)

