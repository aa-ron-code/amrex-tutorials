AMREX_HOME ?= /Users/aaronng/Documents/GitHub/amrex


DEBUG	= FALSE
DEBUG	= TRUE

DIM	= 3

COMP    = gcc

USE_MPI   = FALSE
USE_OMP   = FALSE
USE_CUDA  = FALSE
USE_HIP   = FALSE

#INCLUDE_LOCATIONS += /Library/Developer/CommandLineTools/SDKs/MacOSX10.15.sdk/usr/include

include $(AMREX_HOME)/Tools/GNUMake/Make.defs

include ./Make.package
include $(AMREX_HOME)/Src/Base/Make.package

CXXFLAGS += -isystem /Library/Developer/CommandLineTools/SDKs/MacOSX10.15.sdk/usr/include
include $(AMREX_HOME)/Tools/GNUMake/Make.rules

