![octra!!!!!](https://github.com/user-attachments/assets/2a138e98-cf87-40ed-b64f-902876dc0b17)

 # octra ocs-01 test setup guide.
 
**step 1**

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env
```

**step 2**

```bash
git clone https://github.com/octra-labs/ocs01-test.git
cd ocs01-test
cargo build --release
```

**step 3**
```bash
 # copy contract interface
cp EI/exec_interface.json .**

```

**step 4**
> hover your mouse to the main folder.
> right click and create a new file.
> name it "wallet.json" and paste this .

```bash
{
"priv": "your octra private key (the one w B64)",
"addr": "your octra address",
"rpc": "https://octra.network"
}
```

