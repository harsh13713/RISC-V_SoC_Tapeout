# Week0 - Tools Installation

## Tools Installed
- Yosys
- Icarus Verilog
- GTKWave


## Commands Used
```bash
sudo apt update
sudo apt-get upgrade -y
```

### Yosys
```bash
git clone https://github.com/YosysHQ/yosys.git
cd yosys
make config-gcc
make -j$(nproc)
sudo make install
yosys -V
```
<img width="822" height="475" alt="Screenshot from 2025-09-19 21-29-06" src="https://github.com/user-attachments/assets/cddeb006-0684-4d20-997f-8d36dd1f5da8" />

### Icarus Verilog
```bash
sudo apt-get install -y iverilog
iverilog -V
```
<img width="743" height="506" alt="Screenshot from 2025-09-19 21-57-53" src="https://github.com/user-attachments/assets/35fe8c64-5fd4-49cd-9754-9413482fba94" />
<img width="735" height="619" alt="Screenshot from 2025-09-19 21-58-10" src="https://github.com/user-attachments/assets/ef3e4781-880b-4726-804d-cf35be19438d" />
<img width="703" height="284" alt="Screenshot from 2025-09-19 21-57-18" src="https://github.com/user-attachments/assets/5732468a-7d52-4ed3-bb21-1c4ffce74e38" />

### GTKWave
```bash
sudo apt-get install -y gtkwave
gtkwave --version
```
<img width="703" height="284" alt="Screenshot from 2025-09-19 21-57-18" src="https://github.com/user-attachments/assets/6bbc9e55-1b61-41ce-a475-53e423e61b51" />





















