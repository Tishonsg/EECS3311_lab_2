INCLUDE_PATH =  -I"C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL\library\time\spec\include"
SHELL = /bin/sh
CC = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/mingw/bin/gcc"
CPP = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/mingw/bin/gcc"
CFLAGS = -O0 -pipe -imacros eif_config.mingw.h -D_WIN32_WINNT=0x0500 -DWINVER=0x0500 -D_UNICODE -DUNICODE -DWIN32_LEAN_AND_MEAN   -DEIF_IEEE_BEHAVIOR -DWORKBENCH -I"C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/studio/spec/win64/include" -I. $(INCLUDE_PATH)
CPPFLAGS = -O0 -pipe -imacros eif_config.mingw.h -D_WIN32_WINNT=0x0500 -DWINVER=0x0500 -D_UNICODE -DUNICODE -DWIN32_LEAN_AND_MEAN   -DWORKBENCH -I"C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/studio/spec/win64/include" -I. $(INCLUDE_PATH)
LDFLAGS = 
CCLDFLAGS =   -mconsole
LDSHAREDFLAGS =  
EIFLIB = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/studio/spec/win64/lib/mingw/wkbench.a"
EIFTEMPLATES = C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/studio/config/win64/templates
LIBS = 
MAKE = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/msys/1.0/bin/make.exe"
AR = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/mingw/bin/ar"
LD = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/mingw/bin/ld"
MKDEP =   --
MV = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/msys/1.0/bin/cp"
CP = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/msys/1.0/bin/cp"
RANLIB = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/mingw/bin/ranlib.exe"
RM = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/msys/1.0/bin/rm" -f
FILE_EXIST = 
RMDIR = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/msys/1.0/bin/rd"
X2C = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/studio/spec/win64/bin/x2c.exe"
SHAREDLINK = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/mingw/bin/dllwrap"
SHAREDLIBS = -luser32 -lws2_32 -ladvapi32 -lgdi32 -lshell32 -lmsimg32 -lcomdlg32 -luuid -lole32 -loleaut32 -lcomctl32 -lmpr -lshlwapi -lwinspool -lstdc++ 
SHARED_SUFFIX = .dll
COMMAND_MAKEFILE = 
START_TEST = if [ ! -f finished ] ; then 
END_TEST = ; fi 
CREATE_TEST = "C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/msys/1.0/bin/touch" finished
PATH := C:\Program Files\Eiffel Software\EiffelStudio 17.05 GPL/gcc/win64/mingw/libexec/gcc/mingw32/3.4.2;C:\ProgramData\Oracle\Java\javapath;C:\MinGW\bin;C:\MinGW\libexec\gcc\x86_64-pc-mingw32\5.1.0;C:\Program Files\Java\jdk1.8.0_60\bin;C:\WINDOWS\system32;C:\WINDOWS;C:\WINDOWS\System32\Wbem;C:\WINDOWS\System32\WindowsPowerShell\v1.0\;C:\Program Files (x86)\Microchip\xc32\v1.40\bin;C:\Program Files (x86)\Windows Live\Shared;C:\Program Files\Git\cmd;C:\Program Files\Git\mingw64\bin;C:\Program Files\Git\usr\bin;C:\Users\Saad\AppData\Local\Microsoft\WindowsApps;C:\Users\Saad\AppData\Local\atom\bin;%USERPROFILE%\AppData\Local\Microsoft\WindowsApps; 
SYSTEM_IN_DYNAMIC_LIB = peg_solitaire.dll 

.SUFFIXES:.cpp .o 

.c.o:
	$(CC) $(CFLAGS) -c $<

.cpp.o:
	$(CPP) $(CPPFLAGS) -c $<

OBJECTS = big_file_C2_c.o 

OLDOBJECTS =  ty1015.o ty1015d.o ty1016.o ty1016d.o ar1017.o ar1017d.o ba994.o \
	ba994d.o go993.o go993d.o pl992.o pl992d.o es997.o es997d.o es996.o \
	es996d.o es995.o es995d.o oc991.o oc991d.o un990.o un990d.o da1010.o \
	da1010d.o ti1008.o ti1008d.o da1001.o da1001d.o da1006.o da1006d.o \
	da1013.o da1013d.o ab1002.o ab1002d.o da1004.o da1004d.o da1009.o \
	da1009d.o ti1000.o ti1000d.o ti1007.o ti1007d.o da999.o da999d.o \
	du998.o du998d.o da1012.o da1012d.o da1003.o da1003d.o fi1005.o \
	fi1005d.o da1011.o da1011d.o in1014.o in1014d.o 

all::  Cobj2.o

Cobj2.o: $(OBJECTS) Makefile
	$(RM) $@
	$(LD) -r -o $@ $(OBJECTS)
	$(CREATE_TEST)
	$(RM) $(OBJECTS)


clean: local_clean
clobber: local_clobber

local_clean::
	$(RM) core finished *.o

local_clobber:: local_clean
	$(RM) Makefile

