TOP=../..

include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

#==================================================
# build a support library

LIBRARY_IOC += GammaSPCe

# xxxRecord.h will be created from xxxRecord.dbd
#DBDINC += xxxRecord
# install GammaSPCe.dbd into <top>/dbd
DBD += GammaSPCe.dbd

GammaSPCe_LIBS += stream
GammaSPCe_LIBS += asyn
GammaSPCe_LIBS += $(EPICS_BASE_IOC_LIBS)

#===========================


include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

