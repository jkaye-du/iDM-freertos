#

PROJECT_NAME := iocnx_gateway

export AMAZON_FREERTOS_PATH := $(PROJECT_ROOT)/amazon-freertos

export PROJECT_PATH := $(PROJECT_ROOT)/iocnx/gateway

export IDF_PATH := $(PROJECT_PATH)/esp-idf

EXTRA_COMPONENT_DIRS := $(PROJECT_PATH)/esp32/aws_demos/application_code/espressif_code \
                        $(PROJECT_PATH)/esp32/components

EXTRA_COMPONENT_DIRS += $(PROJECT_PATH)/esp32/components/freertos_tcpip

CFLAGS+=-Wno-unused-function -Wno-unused-variable
include $(IDF_PATH)/make/project.mk
