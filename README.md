# Ini mau ngapain?
Kita mau bikin database lyric dari berbagai audio quran yang bisa didownload di https://quranicaudio.com.

# Gimana caranya?
Baca kebawah, gabung telegram, kenalan, abis itu pilih [tugas](https://github.com/quran-lyric/lyrics/issues) yang mau dikerjakan. Komen ditugasnya (issue), nanti Admin akan invite dan assign issue ke Anda.

# Diskusi
Join grup Telegram https://t.me/joinchat/DRy3Ag3E9MmXrFqBpi1w0w

# Lyric Database

- Audio quran dari https://quranicaudio.com
- Text quran copy dari https://quran.com
- Format lyric pakai LRC https://en.wikipedia.org/wiki/LRC_(file_format)
- Baris Quran ikut ke mushaf madinah http://quran.ksu.edu.sa

# Cara ngecek hasil lyric

## Mac
- Download https://itunes.apple.com/us/app/lyricsx/id1254743014?mt=12 (FREE)
- Download sample audio nya (http://download.quranicaudio.com/quran/mishaari_raashid_al_3afaasee/001.mp3)
- Download sample lirik (https://github.com/quran-lyric/lyrics/blob/master/mishaari_raashid_al_3afaasee/001.lrc)
- Jalankan lyricsx dan itunes
- Puter audio dari itunes
- Drop sample lyric ke lyricsx

![Lyricsx](https://github.com/rawaludin/i/raw/master/mac-lyricsx.png)


## Windows
- Download [MiniLyrics] (http://www.crintsoft.com/MiniLyrics_download.htm) (FREE)
- Install MiniLyrics
- Install plugin sesuai player yang ada. (support: Windows Media Player, iTunes, Winamp, dll.)
- Download sample audio nya (http://download.quranicaudio.com/quran/mishaari_raashid_al_3afaasee/001.mp3)
- Download sample lirik (https://github.com/quran-lyric/lyrics/blob/master/mishaari_raashid_al_3afaasee/001.lrc)
- Jalankan Windows Media Player. (MiniLyrics akan otomatis berjalan)
- Puter audio dari Windows Media Player
- Setting MiniLyrics agar bisa droppable lyric. View > Uncheck: Hide Background on Lost Focus
- Drag & Drop sample lyric ke MiniLyrics

*Notes: Tampilan Penanda Ayat akan terbalik di MiniLyrics (buka kurung akan menjadi tutup kurung, dan sebaliknya)*

### Screenshot

![MiniLyrics](https://raw.githubusercontent.com/aragen/aragen.github.io/master/minilyrics-1.jpg)

## Linux
1. Install OSD-Lyric

	Untuk arch linux, bisa langsung pakai pacman

	```bash
	sudo pacman -S osdlyrics
	```
	Untuk Ubuntu versi artful-ardvark ke atas harus compile sendiri. Info lebih lengkap bisa kunjungi halaman [github](https://github.com/osdlyrics/osdlyrics) mereka. Untuk singkatnya bisa seperti ini:

	```bash
	sudo apt install libappindicator-dev libdbus-glib-1-dev intltool libnotify-dev python-dbus python-pycurl python-chardet
	git clone https://github.com/osdlyrics/osdlyrics.git
	cd osdlyrics
	sudo ./autogen.sh
	sudo make
	sudo make install
	```

2. Download audionya, misal: http://download.quranicaudio.com/quran/mishaari_raashid_al_3afaasee/001.mp3
3. Download file liriknya, misal: https://github.com/quran-lyric/lyrics/blob/master/mishaari_raashid_al_3afaasee/001.lrc
4. Pastikan file lirik dan audio-nya namanya sama dan berada di satu folder.
5. Mainkan audio dengan audio player favorit.
6. Lalu buka osdlyrics.

### Screenshot

Menggunakan VLC di Arch Linux (Xfce)

![VLC-OSDLYRICS](https://raw.githubusercontent.com/ibnujakaria/ibnujakaria.github.io/master/images/Screenshot_2018-05-04_14-41-32.png)

Menggunakan Rhythmbox di Ubuntu 17.10

![rythmbox di ubuntu](https://raw.githubusercontent.com/ibnujakaria/ibnujakaria.github.io/master/images/Screenshot%20from%202018-05-04%2016-33-09.png)
