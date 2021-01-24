# Jadwal-Sholat-Home-Assistant
Jadwal Sholat Home Assistant disertai dengan integrasi Google Media Player
untuk memainkan lantunan Suara Adzan

Yang perlu disiapkan :
1. Longitude
2. Lattitude

Yang perlu di lakukan :
1. Membuat sensor jadwal waktu sholat menggunakan REST API dari aladhan.com, menyesuaikan lokasi LONG & LAT dengan mengedit file configuration.yaml
2. Membuat automation dengan trigger sensor waktu sholat, dengan action media_player.play_media memutar file mp3.
