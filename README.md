![octra!!!!!](https://github.com/user-attachments/assets/2a138e98-cf87-40ed-b64f-902876dc0b17)

```md
```bash title="Install Rust"
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env



# -ocs01-test
# just testing out the functionalities of octra!

 step 1 :  `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env `

```step 2 : git clone https://github.com/octra-labs/ocs01-test.git
cd ocs01-test
cargo build --release


```step 3 : # copy contract interface
cp EI/exec_interface.json .


```step 4 :hover your mouse to the main folder.
> right click and create a new file.
> name it **"wallet.json"** and paste this .


 ** {
    "priv": "your octra private key (the one w B64)",
    "addr": "your octra address",
    "rpc": "https://octra.network"
    } **

```step 5 :go back to your terminal, type in **"nano wallet.json"**
> edit it to your respective details.
> then Ctrl + O to save, press Enter, then Ctrl X.

```step 6 : ./target/release/ocs01-test

```step 7 : insert **"3"** to claim your test token, then you can proceed to play w any number of your choice.


