![octra!!!!!](https://github.com/user-attachments/assets/2a138e98-cf87-40ed-b64f-902876dc0b17)

 # octra ocs-01 test setup guide.
 
**step 1 :install rust**

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env
```

**step 2: build from source**

```bash
git clone https://github.com/octra-labs/ocs01-test.git
cd ocs01-test
cargo build --release
```


