#
# Makefile
#
# Makefile for Poco EchoServer
#

include $(POCO_BASE)/build/rules/global

objects = EchoServer

target         = EchoServer
target_version = 1
target_libs    = PocoUtil PocoJSON PocoNet PocoXML PocoFoundation

include $(POCO_BASE)/build/rules/exec

ifdef POCO_UNBUNDLED
        SYSLIBS += -lz -lpcre -lexpat
endif

