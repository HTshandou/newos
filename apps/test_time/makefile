# app makefile

MY_TARGETDIR := $(APPS_BUILD_DIR)/test_time
MY_SRCDIR := $(APPS_DIR)/test_time
MY_TARGET :=  $(MY_TARGETDIR)/test_time
ifeq ($(call FINDINLIST,$(MY_TARGET),$(ALL)),1)


MY_SRCS := \
	test_time.c


MY_INCLUDES := $(STDINCLUDE)
MY_CFLAGS := $(USER_CFLAGS)
MY_LIBS := -lc -lnewos -lsupc++
MY_LIBPATHS :=
MY_DEPS :=
MY_GLUE := $(APPSGLUE)

include templates/app.mk

endif


