all : flash

TARGET:=blink

include ../../ch32v003fun/ch32v003fun.mk

flash : ${TARGET}.bin
	scp $< c720w:tmp/
clean : cv_clean


