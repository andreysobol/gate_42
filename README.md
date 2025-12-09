# Gate 42

Early access gate for 42 NFT holders

# Installation

```
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

# Running the Snapshot

```
python3 nft_holder_snapshot.py --block %BLOCK_NUMBER% --network testnet --rpc https://gateway.tenderly.co/public/sepolia
```

# Generating Signatures

```
python batch_signature_maker.py --chainid %1 or 11155111% --contract %WHITELIST_CONTRACT% --json-file %SNAPSHOT% --private-key %PK% --output %RESULT%
```