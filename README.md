# Owncloud-Docker-Compose-Deploy
Deploy Owncloud Storage Server dengan Docker Compose

Buat directori baru 
. mkdir <directory-owncloud-compose>
. cd <directory-owncloud-compose>

Buat file docker compose (isi sesuai dengan kebutuhan atau template yang ada), lalu save
. nano compose.yml

Buat .env untuk dokcker composenya (isi sesuai dengan kebutuhan atau template yang ada), lalu save
. nano  .env

Jalankan dengan perintah seperti dibawah
. docker compose up -d 

Lalu coba akses <ip-address-vm>:<port-owncloud>
![image](https://github.com/eprilian/Owncloud-Docker-Compose-Deploy/assets/57064161/b361dc0f-a53a-4a64-9497-344f2ae045fe)

Proses deploy sudah selesai
