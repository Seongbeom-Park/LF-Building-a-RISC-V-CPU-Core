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

<details>
  <summary>3. Decode logic</summary>
  <img src="images/decode_logic/Base_instruction_formats_showing_immediate_variants.png">
  <img src="images/decode_logic/Instruction_types_from_opcode_6-2___instr_6-2__.png">
  <img src="images/decode_logic/imm.png">
  <img src="images/decode_logic/Instruction_decode_table__with_needed_instructions_circled.png">
</details>

<details>
  <summary>4. Register file read</summary>
  <img src="images/register_file_read/The_provided_register_file_instantiation__before_you_modify_it_.png">
</details>

5. ALU
6. Register file write
7. DMem
