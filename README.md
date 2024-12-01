### @selxyzz/instagram-dl

## Apa Itu? 
- @selxyzz/instagram-dl Adalah Sebuah Module Yang Menawarkan Untuk Mendownload Video Instagram 
- Sebuah Module Yang Berbasis Online Agar Memudah Kan Dalam Mendownload Instagram Video

---

## Berapa Request Nya? 
- Batas Request Untuk Instagram Adalah 1000 Request / Month, Jika Sudah Melebihi Batas Maka Tidak Akan Bekerja Lagi. 
# *Mengapa Begitu?*
- Itu Adalah Max Request Dari Token Nya, Jika Sudah Habis 1000 Request Maka Akan Di Reset Setelah Bulan Depan. 
---

## Bagaimana Meng-install Nya? 
- Anda Bisa Menginstall Module Ini Dengan Cmd Ini:
```bash
npm install @selxyzz/instagram-dl
```
- Bagaimana Menggunakan Nya Pada Bot Anda?
- Anda Cukup Menggunakan Cmd Ini Pada Bot Anda: 
```js
(async () => {
const { instagram-dl } = require('@selxyzz/instagram-dl') 
const download = await instagram-dl('https://www.instagram.com/reel/DDCEjsAy0du/?igsh=MTlhbndpYzU5OWtxeg==') 
console.log(download
})()
```
---

## Contributors
- [`Selxyz`](https://wa.me/6282181938329) 
---