
CONSOLE_SRCS=VNConsole.c

noinst_HEADERS=VNConsole.h vga.h

LDADD= @LIBVNCSERVER_LIBS@

bin_PROGRAMS=linuxvnc
linuxvnc_SOURCES=LinuxVNC.c $(CONSOLE_SRCS)

VNCOMMAND=vncommand

noinst_PROGRAMS=example $(VNCOMMAND)
example_SOURCES=example.c $(CONSOLE_SRCS)
vncommand_SOURCES=VNCommand.c $(CONSOLE_SRCS)



