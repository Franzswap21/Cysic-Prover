# Cysic-Prover

Recommend Hardware Requirements for Prover Program Installation

CPU: 64-thread CPU
GPU: 2 × 3070/2080 GPUs
Memory: 280 GB
Disk: 100 GB SSD
Bandwidth: 100 KB/s upload/download
Supported Operating Systems: Linux

🎯 Goal:
Run the Prover and complete tasks to earn rewards.
One address can only be used for 1 prover and 1 verifier.

🔗 Access links:

Website: https://testnet.cysic.xyz/m/
Join the Discord to get an invite code: https://discord.gg/cysic

Tutorial
📥 Installation

Setup:
curl -L https://github.com/cysic-labs/phase2_libs/releases/download/v1.0.0/setup_linux.sh > ~/setup_linux.sh && bash ~/setup_linux.sh GANTI ADDDRESS WL

"GANTI ADDRESS WL" langsung copy paste aja ganti pakai address EVM Galxe

Start Verifier:
cd ~/cysic-verifier/ && bash start.sh

Tunggu beberapa menit ada error dlu, klo berhasil outputnya "start sync data from server"

CTRL+C

Kalo belum install screen, install dulu:
apt install screen

```shell
screen -S cysic


shell
cd ~/cysic-verifier/ && bash start.sh`


CTRL A+D, Done, Perlu spek VPS 2 kalo di contabo
