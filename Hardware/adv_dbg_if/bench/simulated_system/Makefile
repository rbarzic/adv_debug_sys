TOP:=$(shell cd ../../../..; pwd)

VCD_EXTRA_MODULE=
EXTRA_V_SRC=


IVERILOG_OPTS =  -g2005 -DIVERILOG=1
IVERILOG_OPTS += -DTB=tb_nanorv32
IVERILOG_OPTS += $(VCD_EXTRA_MODULE) -f   file_list.txt $(EXTRA_V_SRC)



compile:
	iverilog  -Wall -W no-timescale  $(IVERILOG_OPTS) -o testbench.exe
