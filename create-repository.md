<p style="font-size:14px" align="right">
<a href="https://t.me/bangpateng_group" target="_blank">Join our telegram <img src="https://user-images.githubusercontent.com/50621007/183283867-56b4d69f-bc6e-4939-b00a-72aa019d1aea.png" width="30"/></a>
<a href="https://bangpateng.com/" target="_blank">Visit our website <img src="https://user-images.githubusercontent.com/38981255/184068977-2d456b1a-9b50-4b75-a0a7-4909a7c78991.png" width="30"/></a>
</p>

# Tutorial Membuat Repository di Gitopia

1 . Login ke https://gitopia.com/

<p align="center">
  <img height="auto" height="auto" src="https://user-images.githubusercontent.com/38981255/201937434-8cb51337-b53b-435a-a168-fe6de4dcfdcd.JPG">
</p>

2. Connect Via Recovery Exisiting Wallet
3. Masukan Pharse Wallet Kepler/Validator Kalian
4. Buat Password dan Done, Sudah Connect

<p align="center">
  <img height="auto" height="auto" src="https://user-images.githubusercontent.com/38981255/201937686-68dd3dca-db89-413e-aeae-a9f2f9bbd018.jpg">
</p>

5. Create Repository, Buat Nama dan Deskripsi Bebas

## Instal Git Remote
```
curl https://get.gitopia.com | bash
```
## Buat Folder Baru Bebas (Kalo Bisa Samain Kaya Nama Repoaitory Kalian
```
mkdir nama-repositori
```
```
cd nama-repositori
```
`repository` ganti dengan nama folder kalian bebas

## Lalu Next Step Paste Paste Saja

<p align="center">
  <img height="auto" height="auto" src="https://user-images.githubusercontent.com/38981255/201942175-c6952a60-9f01-4319-8908-253d2e355fe4.jpg">
</p>

```
echo "# hello-world" >> README.md
git init
git add README.md
git commit -m "initial commit"
```
## Push Repository kalian

1 . Balik Lagi ke Website https://gitopia.com/

<p align="center">
  <img height="auto" height="auto" src="https://user-images.githubusercontent.com/38981255/201938703-06a4dedf-919d-40ab-a388-c1d452ebedb0.JPG">
</p>

2 . Klik Profil dan Klik Download

<p align="center">
  <img height="auto" height="auto" src="https://user-images.githubusercontent.com/38981255/201938897-6b6b970d-e9dd-449e-b873-e19e72e04b14.jpg">
</p>

3 . Masukan File di Dalam Vps Terminal Kalian (Jika kalian Menggunakan Software Mobaxterms, Drag Saja File Wallet Yang Sudah Kalian Download Tadi ke Folder nama-repository kalian)

## Add Path Wallet
```
export GITOPIA_WALLET=/root/bangpateng/bangpateng.json
```
`/root/bangpateng/bangpateng.json` ganti Dengan Variable Penempatan Wallet json kalian

bangpateng = adalah nama repository saya dan file json saya taruh di dalam folder repository saya yang ada di vps (paham lah, kalo kaga yaa kebangetan ente)

<p align="center">
  <img height="auto" height="auto" src="https://user-images.githubusercontent.com/38981255/201940398-7bae505c-102e-4dfd-8e59-1e94b3395b9f.JPG">
</p>

Copy Command Push Milik kalian Yang Ada di Dasboard Web Kalian, Seperti Contoh di atas : 

Contoh Command Seperti Ini : 

```
git remote add origin gitopia://Bang-Pateng/Testnet
git push -u origin master
```

<p align="center">
  <img height="auto" height="auto" src="https://user-images.githubusercontent.com/38981255/201939228-aec98a31-9cd3-42e5-8715-8e70ffad05ed.JPG">
</p>

Jika Berhasil Anda Akan Melihat Gambar di Atas.

<p align="center">
  <img height="auto" height="auto" src="https://user-images.githubusercontent.com/38981255/201940941-52400c4a-6da1-4dbb-ab7e-f8301a352a94.jpg">
</p>

Balik Ke dasboard dan Refresh Liat Repository Kalian Sudah Jadi, Silahkan Edit Sesuka Hati

**Created : Bang_Pateng**
