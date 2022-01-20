AMREX_HOME ?= /Users/aaronng/Documents/GitHub/amrex

DEBUG	= FALSE
DEBUG	= TRUE

DIM	= 3

COMP    = gnu

USE_MPI   = TRUE
USE_OMP   = FALSE

CXX = g++-11
CC  = gcc-11
FC  = gfortran-11
F90 = gfortran-11

INCLUDE_LOCATIONS += /usr/local/include

include $(AMREX_HOME)/Tools/GNUMake/Make.defs

include ./Make.package
include $(AMREX_HOME)/Src/Base/Make.package

include $(AMREX_HOME)/Tools/GNUMake/Make.rules
