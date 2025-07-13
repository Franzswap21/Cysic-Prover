# Cysic-Prover

Recommend Hardware Requirements for Prover Program Installation

- CPU: 64-thread CPU
- GPU: 2 × 3070/2080 GPUs
- Memory: 280 GB
- Disk: 100 GB SSD
- Bandwidth: 100 KB/s upload/download
- Supported Operating Systems: Linux
- You’ll need **VPS 2 specs** if you're using Contabo.

🎯 Goal:
Run the Prover and complete tasks to earn rewards.
One address can only be used for 1 prover and 1 verifier.

🔗 Access links:

- Website: https://testnet.cysic.xyz/m/
- Join the Discord to get an invite code: https://discord.gg/cysic

🔗 Tutorial
📥 Installation

**Update Cysic Verifier to New Version 👋**

```bash
sudo rm -rf cysic-verifier/data/cysic-verifier.db
```

Then attach to the screen session:

```bash
screen -r cysic
```

Press `CTRL + C` to stop the process.

Now run the setup script:

```bash
curl -L https://github.com/cysic-labs/phase2_libs/releases/download/v1.0.0/setup_linux.sh > ~/setup_linux.sh && bash ~/setup_linux.sh PASTE_ADDRESS_WL
```

Paste the same reward address you used

Then:

```bash
cd ~/cysic-verifier/ && bash start.sh
```

Detach from the screen using `CTRL + A, then D`.

✅ If successful, the output should show "Sync"

✅ Should look like this if Output Running

<img width="1080" height="368" alt="image" src="https://github.com/user-attachments/assets/88a88b11-bb38-4301-8ad7-1e74d9bb43f2" />

❌ Should look like this if Output Error

<img width="948" height="1280" alt="image" src="https://github.com/user-attachments/assets/45bb7cc1-4477-4cc2-96fe-968428e00e98" />


