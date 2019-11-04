![preview][preview]

## Let Parameter

* Unmutable
* Tidak dapat diubah

```
let country = "Indonesia"
```

Parameter **country** yang memiliki nilai **"Indonesia"** tidak dapat dirubah setelah ditentukan. Anda akan mendapatkan response error jika mencoba memasukan value baru kedalamnya.

```
country = "Australia”
***Cannot assign to value: ‘country’ is a ‘let’ constant
```

## Var Parameter

* Mutable
* Dapat diubah

Parameter **country** yang sudah ditentukan sebelumnya dapat dirubah atau dimasukan value baru kedalamnya dengan *catatan* value tersebut *memiliki tipe data yang sama*.

```
country = "Australia”
***Australia

country = "Singapore”
***Singapore
```

[preview]: banner.png
