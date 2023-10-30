```
Name : Geyser & Floodgate Spigot
Author : NaoCloud Team
Level : Very Easy
Estimated : 2-3 Minutes
```
# Geyser Mc Proxy & Floodgate [Spigot]
Geyser adalah suatu proxy berupa plugin untuk java agar player bedrock bisa main di server java! <br>
## Geyser Version
Geyser terdiri dari banyak jenis plugin untuk masing masing software!<br>
| Geyser Spigot (paper,purpur,spigot,bukkit) <br>
| Geyser Velocity (Velocity (Proxy))<br>
| Geyser Waterfall / Bungee (Waterfall / Bungee (proxy))<br>
| Geyser Mod (Fabric / Sponge)<br>
| Geyser Standalone<br>
<br>
## Geyser Installation
Cara Install sangat simple sekali! Kamu hanya naruh 2 plugin yaitu Geyser dan Floodgate untuk menjalankannya dan kamu hanya otak atik config satu saja yaitu bagian port!<br>
## Link Download 
Download stable on website [Stable](https://geysermc.org/download)

Download from build dev (advanced) [Geyser](https://ci.opencollab.dev/job/GeyserMC/job/Geyser/job/master/)

Download from build dev (advanced) [Floodgate](https://ci.opencollab.dev/job/GeyserMC/job/Floodgate/job/master/)
## Setup Process
1. Buka [Panel](https://home.cloud.naotao.my.id/) <br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/a91aeefa-bb9f-4e6c-a285-00a7d41979ca)
2. silakan login ke akun anda!<br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/4866c6eb-189d-47ec-81eb-4b0d8db2b71c)
3. Ditampilan server click **Manage Server** <br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/1c6235e4-5553-4cab-b685-08dd397a7ca5)
4. Tampilan Awal terdapat banyak tab. Klik Tab File Manager!<br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/fac96547-554c-4377-8a24-9c12349eb6d6)
5. Ada banyak sekali file! Pilih file Plugins!<br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/22e18181-d4ad-41e0-aeda-5f519f66702f)
6. Download Process! Buka website [Geyser](https://geysermc.org/download)<br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/30d8c5d8-264d-4289-a824-32224ae84809)
7. Tekan tab paper/spigot dan tekan button Download geyser dan Download Floodgate!<br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/931658f0-89dc-4a2c-82fd-228d1887face)
8. Jika sudah, Kembali ke panel kamu bisa drag file yang kamu download ke dalam folder Plugins!<br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/86977be1-2fc8-46ec-a846-011fe7c23189)
9. Jika sudah, kembali ke tab console dan restart servernya!<br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/fb21b26d-cf75-4901-96bd-280d47bd4ddc)
10. Nah jika sudah restart saatnya kamu setting di folder Geyser-spigotnya!<br>
11. Kembali di langkah 4 dan 5<br>
12. Akan ada folder geyser dan floodgate! Pentingkan Geyser.<br>
13. Buka folder geyser-spigot<br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/34d74f97-21ca-4c31-9c8a-57548b2254ca)
14. Buka file config.yml<br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/f0bb2f35-4361-4810-afcb-b6d1771d5fbb)
15. Bagian config seperti dibawah ini :<br>
```yaml
bedrock:
  # The IP address that will listen for connections.
  # Generally, you should only uncomment and change this if you want to limit what IPs can connect to your server.
  #address: 0.0.0.0
  # The port that will listen for connections
  port: 19132
  # Some hosting services change your Java port everytime you start the server and require the same port to be used for Bedrock.
  # This option makes the Bedrock port the same as the Java port every time you start the server.
  # This option is for the plugin version only.
  clone-remote-port: false
```
16. Ubah di bagian port menjadi port yang kamu pake dihosting. Ditutorial kali ini memakai `10001` maka aku ganti menjadi `10001` bergitu juga kamu menaruh dengan angka port yang sesuai dengan hosting.<br>
17. Jika sudah save changes<br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/8d90d907-4fd4-43c6-891a-e7a8518ac1a2)
18. Ulangi langkah 9 dan tada geyser telah di setup!<br>

## Finish
### Add Server
Nah, kan sudah di setup cara untuk add server nya adalah <br>
1. Buka Minecraft<br>
2. Play > Server > Add server<br>
3. Dengan format masukin nama server<br>
4. Ip server yang ada di hosting seperti sg1.naohost.my.id<br>
5. Masukan port yang kamu set di panel. Tadi ditutorial kita set di port `10001` maka  masukan port `10001` dan juga untuk kalian yang set portnya yang lain<br>
6. Dan save!<br>

### Crack
Agar untuk crack player bisa masuk cara setnya gampang!<br>
1. Ke panel anda dan pergi ke tab File Manager<br>
2. Cari file bernama server.properties<br>
![image](https://github.com/Naotaostudio/Naocloud-Wiki/assets/138988574/69c78208-5a01-4c20-a81b-4e391946c1b5)
3. cari `online-mode: true` seperti dibawah <br>
```yaml
use-native-transport=true
max-players=20
online-mode=true
```
4. Ubah menjadi `true` jadi `false`<br>
5. Save changes dan selesai!<br>
<br>
Dan itulah tutorial setup Geyser dengan tingkatan yang mudah! Masih ada tutorial lainnya dan juga masi ada Geyser Proxied.<br>
Stay Tune!<br>










