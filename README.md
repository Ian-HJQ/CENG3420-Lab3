# CENG3420 - Lab 3: RISC-V Little Computer (RISC-V LC)

## Lab 3-1 

1. Get RISC-V LC
- `$ git clone https://github.com/baichen318/ceng3420.git`
- `$ cd ceng3420`
- `$ git checkout lab3.1`

2. Compile
- `$ make`

3. Run the RISC-V LC
- `$ ./riscv-lc <uop> <*.bin>` RISCV-LC can execute successfully if you have implemented it.

4. Benchmarks
Verify your codes with these benchmarks (inside the benchmarks directory)
- `isa.bin`
- `count10.bin`
- `swap.bin`

6. Verification
- `isa.bin` → `a3 = -18/0xffffffee` and `MEMORY[0x84 + 16] = 0xffffffee`
- `count10.bin` → `t2 = 55/0x00000037`
- `swap.bin` → `NUM1` changes from `0xabcd` to `0x1234` and `NUM2` changes from `0x1234` to `0xabcd`

#### Tasks:
- Implement all control signals in uop.
- Fill x with the correct 0 or 1.
- Implement the code that x0 is hard-wired to zero in riscv-lc.c.

More info: https://www.cse.cuhk.edu.hk/~byu/CENG3420/2022Spring/slides/lab3-1.pdf

## Lab 3-2

1. Get RISC-V LC
- `$ git clone https://github.com/baichen318/ceng3420.git`
- `$ cd ceng3420`
- `$ git checkout lab3.2`

2. Compile (Linux/MacOS environment is suggested)
- `$ make`

3. Run the RISC-V LC
- `$ ./riscv-lc <uop> <*.bin>` RISCV-LC can execute successfully if you have implemented it.

4. Benchmarks
Verify your codes with these benchmarks (inside the benchmarks directory)
- `isa.bin`
- `count10.bin`
- `swap.bin`

6. Verification
- `isa.bin` → `a3 = -18/0xffffffee` and `MEMORY[0x84 + 16] = 0xffffffee`
- `count10.bin` → `t2 = 55/0x00000037`
- `swap.bin` → `NUM1` changes from `0xabcd` to `0x1234` and `NUM2` changes from `0x1234` to `0xabcd`

#### Tasks:

In `riscv-lc.c`,
- Finish `cycle_memory`
- Finish `latch_datapath_values`

These unimplemented codes are commented with `Lab3-2 assignment`

More Info: https://www.cse.cuhk.edu.hk/~byu/CENG3420/2022Spring/slides/lab3-2.pdf

## Lab 3-3

1. Get RISC-V LC
- `$ git clone https://github.com/baichen318/ceng3420.git`
- `$ cd ceng3420`
- `$ git checkout lab3.3`

2. Compile
- `$ make`

3. Run the RISC-V LC
- `$ ./riscv-lc <uop> <*.bin>` RISCV-LC can execute successfully if you have implemented it.

4. Benchmarks
Verify your codes with these benchmarks (inside the benchmarks directory)
- `isa.bin`
- `count10.bin`
- `swap.bin`

6. Verification
- `isa.bin` → `a3 = -18/0xffffffee` and `MEMORY[0x84 + 16] = 0xffffffee`
- `count10.bin` → `t2 = 55/0x00000037`
- `swap.bin` → `NUM1` changes from `0xabcd` to `0x1234` and `NUM2` changes from `0x1234` to `0xabcd`

#### Tasks:

In `riscv-lc.c`,
- Finish `eval_bus_drivers`
- Finish `drive_bus`

These unimplemented codes are commented with `Lab3-3 assignment`

More Info: https://www.cse.cuhk.edu.hk/~byu/CENG3420/2022Spring/slides/lab3-3.pdf
