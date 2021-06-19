# [Nandgame](https://nandgame.com/) Leaderboard

| Level | Least Components | Least Gates | Notes |
| - | - | - | - |
| RELAY_NAND_GATE | | [-/2](D/RELAY_NAND_GATE.md) | |
| INV | [1/1](D/INV_COMP.md) | [1/1](D/INV_GATE.md) | |
| AND | [2/2](D/AND_COMP.md) | [2/2](D/AND_GATE.md) | |
| OR | [3/3](D/OR_COMP.md) | [3/3](D/OR_GATE.md) | |
| XOR | [3/6](D/XOR_COMP.md) | [4/4](D/XOR_GATE.md) | |
| HALFADD | [2/6](D/HALFADD_COMP.md) | [5/5](D/HALFADD_GATE.md) | |
| FULLADD | [3/13](D/FULLADD_COMP.md) | [9/9](D/FULLADD_GATE.md) | |
| ADD2 | [2/18](D/ADD2_COMP.md) | [2/18](D/ADD2_GATE.md) | |
| INC | [2/145](D/INC_COMP.md) | [2/145](D/INC_GATE.md) | This is the first level where gates can't be optimal because of locked components. |
| SUB | [3/161](D/SUB_COMP.md) | [3/161](D/SUB_GATE.md) | |
| ISZERO | [4/10](D/ISZERO_COMP.md) | [4/10](D/ISZERO_GATE.md) | [2/4](D/ISZERO_CHEAT.md) cheating solution(not correct for other inputting order) |
| SIGN | [0/0](D/SIGN_COMP.md) | [0/0](D/SIGN_GATE.md) | |
| MULTIPLEXER | [3/10](D/MULTIPLEXER_COMP.md) | [4/4](D/MULTIPLEXER_GATE.md) | |
| DEMUX | [2/6](D/DEMUX_COMP.md) | [3/4](D/DEMUX_GATE.md) | |
| LATCH | [1/4](D/LATCH_COMP.md) | [1/4](D/LATCH_GATE.md) | |
| DFF | [4/11](D/DFF_COMP.md) | [9/9](D/DFF_GATE.md) | |
| DFF2 | [2/18](D/DFF2_COMP.md) | [15/15](D/DFF2_GATE.md) | |
| COUNTER | [4/330](D/DFF2_COMP.md) | [7/277](D/DFF2_GATE.md) | Using update order, which is not studied enough. |
| RAM | [4/308](D/RAM_COMP.md) | [10/203](D/RAM_GATE.md) | |
| ALU_PRESET | [3/144](D/ALU_PRESET_COMP.md) | [3/144](D/ALU_PRESET_GATE.md) | |
| ALU | [6/672](D/ALU_COMP.md) | [7/608](D/ALU_GATE.md) | |
| CONDITION | [7/61](D/CONDITION_COMP.md) | [8/56](D/CONDITION_GATE.md) | You may find someone claim 20-gate solution since the old counting rule use gate count of 4-bit ISZERO as the one of 16-bit, while new counting rule multiplies it by 4 and add 6. |
| CPU_STATE | [3/240+51968](D/CPU_STATE_COMP.md) | [3/240+51968](D/CPU_STATE_GATE.md) | |
| INSTRUCTON_DECODER | [4/130](D/CPU_STATE_COMP.md) | [15/90](D/CPU_STATE_GATE.md) | |
| EXECUTION_ENGINE | [6/1122+51968](D/EXECUTION_ENGINE_COMP.md) | [6/1122+51968](D/EXECUTION_ENGINE_GATE.md) | |
| CPU2 | [3/1399+51968](D/CPU2_COMP.md) | [3/1399+51968](D/CPU2_GATE.md) | |
| CMOS_NAND | | [-/1](D/CMOS_NAND_GATE.md) | Likely a bug. Contacted author but no response so far. |
