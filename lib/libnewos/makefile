# main libnewos
MY_TARGET := $(LIBS_BUILD_DIR)/libnewos.so
MY_STATIC_TARGET := $(LIBS_BUILD_DIR)/libnewos.a

MY_TARGETDIR := $(LIBS_BUILD_DIR)/libnewos
MY_SRCDIR := $(LIBS_DIR)/libnewos
MY_SRCS := \

MY_INCLUDES := $(STDINCLUDE)
MY_CFLAGS := $(USER_CFLAGS)
MY_LINKSCRIPT := $(LIBS_LDSCRIPT)

# include sub makefiles
include $(addsuffix /makefile, $(addprefix $(MY_SRCDIR)/, \
	system \
	system/arch/$(ARCH) \
))

include templates/lib.mk

