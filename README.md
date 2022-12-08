# Inery-Taks-2
Create Token

## Membuat ABI dan WASM

```
cline get code inery.token -c token.wasm -a token.abi --wasm
```

## Buka Wallet

```
cline wallet unlock -n (nama walletmu)
```

## Membuat Token

```
cline push action inery.token create '["(nama akunmu)", "(suplai token).0000 (Kode token)" , "creating my first tokens"]' -p (nama akunmu)
```
Contoh (Saya beri nama ganteng)
```
cline push action inery.token create '["ganteng", "500000.0000 GTNG" , "creating my first tokens"]' -p ganteng
```

## Issue Token Baru

```
cline push action inery.token issue '["(nama akunmu)", "(suplai token).0000 (Kode token)", "Issuing some (Kode token) token"]' -p (nama akunmu)
```
Contoh (Saya beri nama ganteng)
```
cline push action inery.token issue '["ganteng", "500000.0000 GTNG", "Issuing some GTNG token"]' -p ganteng
````

