TOP = ../..
include $(TOP)/configure/CONFIG

include $(TOP)/gsl_flags.mak

LIBRARY_IOC += gslSupport
DBD += gslSupport.dbd

gslSupport_SRCS += line_of_best_fit.c

gslSupport_LIBS += gsl
gslSupport_LIBS += $(EPICS_BASE_IOC_LIBS)

include $(TOP)/configure/RULES
