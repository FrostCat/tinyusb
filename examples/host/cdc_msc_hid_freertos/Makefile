RTOS = freertos
include ../../build_system/make/make.mk

INC += \
	src \
	$(TOP)/hw \

# Example source
EXAMPLE_SOURCE = \
  src/cdc_app.c \
  src/hid_app.c \
  src/main.c \
  src/msc_app.c \

SRC_C += $(addprefix $(CURRENT_PATH)/, $(EXAMPLE_SOURCE))

include ../../build_system/make/rules.mk
