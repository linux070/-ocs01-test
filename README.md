![octra!!!!!](https://github.com/user-attachments/assets/2a138e98-cf87-40ed-b64f-902876dc0b17)
 # -ocs01-test
 # just testing out the functionalities of octra!

# Installation & Setup Guide

This guide walks you through installing Rust and building the project from source.

---

## Step 1: Install Rust (if not installed)

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env


Step 2: Clone and Build from Source
git clone https://github.com/octra-labs/ocs01-test.git
cd ocs01-test
cargo build --release

Step 3: Setup Contract Interface
# Copy contract interface
cp EI/exec_interface.json .
