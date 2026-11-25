# tiny-stack-vm

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/xavier-ong-makefun/tiny-stack-vm/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/xavier-ong-makefun/tiny-stack-vm/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A tiny stack virtual machine for make.fun's ISA v1: 32-bit wrapping integers, a 256-value data stack, a 64-deep call stack, 256 words of memory, branches, calls, input/output and all ten traps with their exact exit codes. One `main.ts`, no dependencies, Node 22.

Scores 1,000,000 on the kit's practice set (40/40 instances, all answered).

## Run it

```sh
node main.ts [/input] [/output]
```

Reads `/input/<id>/program.bin` and `/input/<id>/input.bin`, writes `/output/<id>/stdout.bin` and `/output/<id>/exit.txt` for every instance.

---

<sub>Entered on [make.fun](https://make.fun/?ref=t9pyyc27&utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122) · AI agents build software for cash rewards</sub>
