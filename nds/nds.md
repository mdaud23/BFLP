# New Delivery System
New Delivery System adalah aplikasi
yang digunakan di unit kerja untuk
keperluan pelayanan nasabah dan
operasional unit kerja.

Aplikasi yg dipakai CS dan teller: brinet web, bds, brinets express

<!> pindah2 aplikasi mengurangi efisiensi, produktivitas, dan fokus dari CS dan Teller

key take away: C, Python, Bash, Git, Jira, Bitbucket, Jira, Bamboo, Openshift, GCP, AWS, dan beberapa tool DevOps lainnya

minimal ngarti how to do work bawahan gitu, cara ngawasinnya, dll kalo BFLP

NDS sudah widely used di cabang dan unit kerja, tapi masih banyak problem, terutama di jaringan dan middleware

<!> tantangan di uker adalah ga pernah Ijo koneksi, ada uker yang pakai satelit itu masalahnya di bandwidth. Kalo koneksi internet lancar di bengkulu

NDS ga bisa login kalo IP belum didaftarin

login di NDS bisa pakai data dari CS Teller, juga PN

<!> Penjagaan NDS apalagi si yang mesti diimprove

NDS bisa dibuka di intranet uker, atau kalo ada VPN bisa dari rumah. VPN tapi cukup strict

Setiap transaksi Error Correction harus didampingi supervisor

## Pre-requisite NDS
![pre-requisite](pre_requisite.png)

## Step Instalasi AgentPring
![tahapan](tahapan.png)

## Catatan Hari Ke-2
NDS diampu oleh Outlet Delivery Platform 

NDS is very important, dengan potensi transaksi 1600 T per bulan di unit kerja

Kekuatan kita di ekonomi yg dibawah rata2 (masyarakat kecil atau menengah ke bawah)

Banyak hal menarik yg ditemukan pada kantor cabang di daerah2 kecil

ODP terdiri dari 1 project, 3 Vendor, 9 Team, 18 Aplikasi

Harapannya, NDS teh superapp yg ada di unit kerja

Urgensi pindah ke NDS

Akan ada kesulitan dan chaos saat perpindahan teknologi

End-user tidak peduli soal permasalahan IT, yang penting aman, nyaman, cepat

End-user ga tau kalo aplikasinya dah di pinggir jurang, jadi ya mesti tangan besi

Setiap Kantor Cabang ada IT 1 atau 2 orang

NDS lambat, padahal bisa jadi salah jaringan

<!> openshift kemahalan license-nya

SDLC di ODP pakai Agile: Plan -> Design -> Develop -> Test -> Deploy -> Review -> Launch

Agile cocok ketika menguji ide. Mulai dari MVP dulu, lalu lempar ke pasar, dapet feedback then ada pengembangan lagi. Bayesian ya

Sprint Plan, Stand-up Meeting about kerjaan kemarin dan hari ini, Sprint Review, Sprint Retro, 

## Customer Service Essential Features
1. Account Opening
2. CIF Maintenance -> Pengkinian Data
3. Penerbitan Kartu Debit
4. 

Kadang, customer experience itu against security

EDM data lake pakai Kafka

## Approval
Ada permasalahan pasti di lapangan

Password Sharing is not good

Pakai BriStar untuk approve

## Legacy
Kalo ada problem speak-up, jangan diem2 aj

<!> Permasalahan terkiat user against Security (risk)
