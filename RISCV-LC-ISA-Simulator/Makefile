# /***************************************************************/
# /*                                                             */
# /*                  RISCV-LC Assembler                         */
# /*                                                             */
# /*                     CEG3420 Lab2                            */
# /*                 cbai@cse.cuhk.edu.hk                        */
# /*           The Chinese University of Hong Kong               */
# /*                                                             */
# /***************************************************************/

CC = gcc
SRC := $(wildcard *.c)
TGT := sim
OPT := -Wall -std=c99 -Wno-return-type -O3 # -Werror

.default: all

all: $(TGT)

$(TGT): $(SRC)
	$(CC) $(OPT) $^ -o $@

.PHONY: clean
clean:
	del /f sim *.bin
