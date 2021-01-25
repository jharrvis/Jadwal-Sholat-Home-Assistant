# Home Assistant
# Jadwal Sholat (Islamic Praying Times)

Sensor Jadwal Sholat untuk Home Assistant dan Automation integrasi Google Smart Speaker Media Player
untuk memainkan lantunan Suara Adzan sesuai jadwal sholat.

Yang perlu disiapkan :
1. Longitude
2. Lattitude

Yang perlu di lakukan :
1. Membuat sensor jadwal waktu sholat menggunakan REST API dari aladhan.com, menyesuaikan lokasi LONG & LAT dengan mengedit file configuration.yaml
2. Membuat automation dengan trigger sensor waktu sholat, dengan action media_player.play_media memutar file mp3.

Credits :
Ref : https://community.home-assistant.io/t/hanafi-islamic-prayer-time/147440/10
REST API : https://aladhan.com/prayer-times-api
Mp3 Suara Adzan : http://praytimes.org/audio/
