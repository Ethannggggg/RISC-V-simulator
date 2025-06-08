# /***************************************************************/
# /*                                                             */
# /*                  RISCV-LC Assembler                         */
# /*                                                             */
# /*                     CEG3420 Lab2                            */
# /*                 cbai@cse.cuhk.edu.hk                        */
# /*           The Chinese University of Hong Kong               */
# /*                                                             */
# /***************************************************************/

CC := gcc
SRC := $(wildcard *.c)
TGT := asm
OPT := -Wall -std=c99 -Wno-return-type -O3 # -Werror
VAL := tools/validate.sh

.default: all

all: $(TGT)

$(TGT): $(SRC)
	$(CC) $(OPT) $^ -o $@

validate: $(TGT)
	bash $(VAL)

.PHONY: clean
clean:
	del /f asm *.bin
