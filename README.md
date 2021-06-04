# [Building a RISC-V CPU Core](https://learning.edx.org/course/course-v1:LinuxFoundationX+LFD111x+1T2021/home)
Build a RISC-V CPU core with TL-Verilog

## How to start
### Install makerchip IDE
```bash
pip3 install makerchip-app
```
### Run makerchip IDE
```bash
makerchip riscv.tlv
```

## Implementation plan
![RISC-V_CPU_Block_Diagram](images/RISC-V_CPU_Block_Diagram.png)

<details>
  <summary>1. PC logic</summary>
  <img src="images/pc_logic/Initial_PC_logic.png">
</details>

<details>
  <summary>2. Fetch</summary>
  <img src="images/fetch/Instruction_memory_hookup.png">
</details>

3. Decode logic
4. Register file read
5. ALU
6. Register file write
7. DMem
