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

## Kirim Token ke Inery

```
cline push action inery.token transfer '["(nama akunmu)", "inery", "(jumlah yg di tf).0000 FEBY", "Here Is my (jumlah yg di tf) (Kode token) token for you mate "]' -p (nama akunmu)
```
Contoh (Saya beri nama ganteng)
```
cline push action inery.token transfer '["ganteng", "inery", "100.0000 GTNG", "Here Is my 100 GTNG token for you mate "]' -p ganteng
```

## Transfer ke 10 orang berbeda

Untuk 10 orang ini kalian bisa melihat nama aku penerima di Explorer Master Node Inery

![image](https://user-images.githubusercontent.com/91402307/206368462-9829d8c8-30df-49f7-8bd5-8220901da056.png)

```
cline push action inery.token transfer '["(nama akunmu)", "(nama penerima)", "(jumlah yg di tf).0000 (Kode token)", "Here Is my (jumlah yg di tf) (Kode token) token for you mate "]' -p (nama akunmu)
```
Contoh (Saya beri nama ganteng)
```
cline push action inery.token transfer '["ganteng", "1atau2", "100.0000 GTNG", "Here Is my 100 GTNG token for you mate "]' -p ganteng
```

# Terima Kasih (Thank You)
