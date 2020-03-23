#

PROJECT_NAME := iocnx_gateway

export AMAZON_FREERTOS_PATH := $(PROJECT_ROOT)/amazon-freertos

PROJECT := $(PROJECT_ROOT)/iocnx/gateway

export IDF_PATH := $(PROJECT)/esp-idf

EXTRA_COMPONENT_DIRS := $(PROJECT)/esp32/aws_demos/application_code/espressif_code \
                        $(PROJECT)/esp32/components

EXTRA_COMPONENT_DIRS += $(PROJECT)/esp32/components/freertos_tcpip

CFLAGS+=-Wno-unused-function -Wno-unused-variable
include $(IDF_PATH)/make/project.mk
