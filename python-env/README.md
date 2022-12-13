<div align = center>

# Python Virtual Enviroment

![python][def]

</div>

Seperti namanya, Virtual Environment adalah sebuah ruang lingkup virtual yang terisolasi dari dependencies utama. Virtual Environment sangat berguna ketika kita membutuhkan dependencies yang berbeda-beda antara project satu dengan lainnya yang berjalan pada satu system operasi yang sama.

## Instalasi

### Untuk dapat menginstalkan, ada beberapa yang di butuhkan:

- python3
- python3-venv

### Langkah-langkah

1. Yang pertama anda harus menginstalkan terlebih dahulu python3-venv

    - ``` > sudo apt install python3-venv ```
2. Lalu buatlah folder baru bebas dengan nama apapun
    - ``` > mkdir python-env ``` # misalnya saya disini pakai nama ini
3. Lalu installkan komponen yang akan di gunakan pada folder tadi
    - ``` > python3 -m venv python-env/ ```
4. Tunggu hingga selesai, lalu coba aktifkan dengan command
    - ``` > source python-env/bin/active ```
5. Untuk menonaktifkan cukup ketikkan perintah
    - ``` > deactive ```

[def]: data:image/png;base64,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