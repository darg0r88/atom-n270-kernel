# Extreme Optimized Kernel for Intel Atom N270

This repository builds a highly optimized Linux kernel (based on v5.4 LTS) specifically tuned for the Intel Atom N270 (Bonnell architecture).

## Key Features
- **Processor Optimization:** `-march=bonnell -O3`
- **Low Latency:** `CONFIG_PREEMPT`, `HZ=1000`
- **Minimal Footprint:** Stripped debug info and unused drivers.
- **Security:** Reduced mitigations for maximum performance on older hardware.

Builds are automated via GitHub Actions.
