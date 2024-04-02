# Author: crifan
# Date: 2012-05-16
#
# -----------------------------------------------------------------
#  generate output from DocBook sources
#  this is entry makefile for docbook
# -----------------------------------------------------------------
# run this makefile under src directory:
# [office]
# pwd = /home/CLi/develop/docbook/books/xxx/src
# [home]
# pwd = /cygdrive/e/Dev_Root/docbook/dev/books/xxx/src

################################################################################
# Project Settings
################################################################################

# also means main source file name
PROJECT_NAME = bluetooth_intro
SUB_SRC_FILES = \
    preface.xml \
    ch01_bt_basic.xml \
    ch02_bt_arch_profile.xml \
    ch03_bt_implementation.xml \
    ch04_bt_usage.xml \
    ch05_bt_dev.xml \
    ch06_bt_ble.xml \
    reference.xml
    

DOCBOOK_MAKEFILE_ROOT = ../../../config
################################################################################
# Include docbook makefile
################################################################################
include $(DOCBOOK_MAKEFILE_ROOT)/docbook.mk