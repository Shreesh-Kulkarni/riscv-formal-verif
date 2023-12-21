
riscv-formal proofs for picorv32
================================

Quickstart guide:

First install Yosys, SBY, and the solvers. See the 
[SBY Installation Guide](https://yosyshq.readthedocs.io/projects/sby/en/latest/install.html)
for instructions. 
No need to download the core, the top module is already included in this folder. 
Select what checks you want to perform in the checks.cfg file(refer checks folder for type of checks as there are multiple extensions involved in this core) and just generate the formal checks and run them by using the following command(after git clone):

```
make check -j$(nproc)
```

