<div align = center>

# **Open Flow**

![img](https://miro.medium.com/max/640/1*7_6fSZPtUM1_a0Z5qqUmrw.webp)

</div>

OpenFlow adalah, salah satu jenis dari APIs (Application Protocol Interfaces) dalam jaringan SDN yang digunakan untuk mengontrol/mengatur traffic flows pada switch dalam sebuah jaringan

Berikut rekam jejak proses development **Open-Flow**

<div align = center>

![img](https://miro.medium.com/max/640/1*NkcPs2KUD6YFjQCSCk2JAQ.webp)

</div>

Protokol OpenFlow telah berkembang sejak dimulai nya proses standarisasi oleh **Open Network Foundation (ONF)**, yaitu sebuah organisasi yang berfokus dalam pengembangan protokol OpenFlow, dari versi 1.0–1.5.

Sebelumnya disinggung kalau OpenFlow itu adalah salah satu jenis dari APIs, nah OpenFlow sendiri adalah southbound interface, dimana interface yang memungkinkan terjadinya komunikasi antara layer controller dan data plane pada arsitektur SDN.

<div align = center>

![cek](https://miro.medium.com/max/564/1*kKzcbfsabj8qlJt2Y_fnxA.webp)

</div>

Mungkin dari kalian banyak yang mengira bahwa “ OpenFlow itu adalah Software Defined Network (SDN)” nah sekarang hilangkan mindset itu, yang perlu kalian pahami adalah “OpenFlow merupakan komponen dalam arsitektur SDN” . Dalam beberapa tahun terakhir, OpenFlow telah melatar belakangi ide penelitian dalam eksplorasi dunia akademik jaringan untuk implementasi referensi standar SDN dimana teknologi ini menjadikan pergerakan momentumnya berperan cukup besar dalam industri saat ini.

Agar OpenFlow dapat bekerja sesuai dengan tujuan dan fungsinya, OpenFlow mempunya 2 komponen penting yaitu OpenFlow Controller dan OpenFlow Switch. Bisa kita lihat gambar dibawah yang mengambarkan bagian- bagian dari OpenFlow.

<div align = center>

![img2](https://miro.medium.com/max/640/1*wzCCXh-u2Etd4na0jizdpw.webp)

</div>

# Getting Started

Sebelum anda mencobanya, silahkan ikuti beberapa langkah-langkah yang penulis anjurkan :

1. [Mininet](/mininet/README.md)
2. [Python-Venv](/python-env/README.md)
3. [Ryu](/ryu/README.md)

# Refrence

- <https://medium.com/core-network-laboratory-tech-page/berkenalan-dengan-openflow-3caca9194e51>
- <http://mininet.org/>
- <https://docs.python.org/3/library/venv.html>
- <https://ryu.readthedocs.io/en/latest/getting_started.html>
