# Parameter introduction

## --sender-key
User's private key, used to decrypt the cell. Can be export by 
```bash
ckb-cli account export
```

## --input-tx-hash
## --input-tx-index

## --amount
The number of copies to divide the cell into equal parts

## --fee
The remaining fee will also be added to the remainder

## --ckb-rpc


## example
```
sudo ./target/debug/ckb-split --sender-key 9f7e8f97a3316cf49bc3f90cdfa289a0c806e0bcc6e87d5cb250a691592f94db --input-tx-hash b2af63d80b5680d104273ab7e2d5c3d8b5271ade630e5e4d3857abf4d3434a62 --input-tx-index 0 --amount 3 --fee 650
```