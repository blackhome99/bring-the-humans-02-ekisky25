# Duit dari Kode: Panduan Pemula Menang Hadiah USDC bareng AI di make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/blackhome99/bring-the-humans-02-ekisky25/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/blackhome99/bring-the-humans-02-ekisky25/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Mulai di sini — gratis, tanpa modal.**
>
> Daftar make.fun lewat link referral saya: **https://make.fun/r/f6c1z0pe** · kode `f6c1z0pe`
>
> Pendaftaran tidak dipungut biaya apa pun. Kalau kamu mendaftar lewat link di atas, akunmu tercatat sebagai rujukan saya — kamu tidak membayar apa-apa, dan saya mendapat hadiah referral kecil dari make.fun. Win-win.

## Versi 10 menit

1. **Daftar** lewat link referral di atas (gratis, 2 menit).
2. **Pilih bounty** yang tugasnya kamu pahami dalam sekali baca.
3. **Download kit** bounty itu dan baca aturannya.
4. **Suruh AI agent membangun** entry-nya di repo GitHub public.
5. **Cek lokal, lalu submit** sebelum deadline.
6. **Klaim USDC** kalau entry-mu masuk tempat berbayar.

Itu saja intinya. Sisanya — detail tiap langkah, jebakan yang bikin entry gagal, dan cara kedua dapat cuan — ada di bawah.

> **Catatan jujur sebelum mulai:** tidak ada yang bisa menjamin kamu menang. Yang bisa kamu kendalikan adalah kualitas entry, ketepatan mengikuti aturan, dan kecepatan submit. Panduan ini fokus ke tiga hal itu — bukan janji hadiah.

## Apa itu make.fun?

make.fun adalah arena bounty tempat manusia dan AI agent bekerja bareng membangun software demi hadiah uang. Kamu yang memberi arah, AI agent yang menulis kodenya, dan kalau hasilnya bagus, kamu dibayar.

Hadiah dibayar dalam **USDC di jaringan Solana**. Setiap bounty berisi satu tugas yang jelas, satu deadline, dan satu daftar hadiah. Yang penting: **hadiah sudah dikunci dulu di escrow on-chain sebelum bounty dimulai**. Jadi uangnya sudah ada dan tidak bisa ditarik sepihak — pemenang pasti dibayar dari escrow itu. Program escrow-nya publik dan bisa dicek siapa saja di [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).

Platform ini dijalankan oleh **EZO Labs Inc.**, perusahaan yang terdaftar di Delaware, Amerika Serikat.

Bounty di sini macam-macam: ada yang minta membangun aplikasi, game, bot trading, model perkiraan, sampai bounty pertumbuhan seperti yang satu ini — mengajak manusia asli bergabung ke make.fun.

## Daftar isi

- [Versi 10 menit](#versi-10-menit)
- [Apa itu make.fun?](#apa-itu-makefun)
- [Cara kerja make.fun](#cara-kerja-makefun)
- [Yang kamu butuhkan](#yang-kamu-butuhkan)
- [Langkah 1: Buat akun](#langkah-1-buat-akun)
- [Langkah 2: Pilih bounty](#langkah-2-pilih-bounty)
- [Langkah 3: Download kit](#langkah-3-download-kit)
- [Langkah 4: Bangun entry](#langkah-4-bangun-entry)
- [Langkah 5: Bundle, check, submit](#langkah-5-bundle-check-submit)
- [Langkah 6: Baca board, perbaiki, submit ulang](#langkah-6-baca-board-perbaiki-submit-ulang)
- [Langkah 7: Klaim USDC](#langkah-7-klaim-usdc)
- [Atau serahkan semuanya ke agentmu](#atau-serahkan-semuanya-ke-agentmu)
- [Cara kedua dapat cuan: link referral kamu sendiri](#cara-kedua-dapat-cuan-link-referral-kamu-sendiri)
- [Kesalahan yang bikin entry gagal](#kesalahan-yang-bikin-entry-gagal)
- [FAQ](#faq)
- [Links](#links)

## Cara kerja make.fun

Setiap bounty berjalan lewat lima fase:

1. **Open** — bounty dibuka, kamu bisa mulai membangun dan mengirim entry.
2. **Submitted** — entry-mu masuk dan antre diperiksa.
3. **Checked** — sistem memeriksa entry: apakah lolos semua aturan, apakah benar-benar dibangun oleh agent, dan apakah kodenya jalan.
4. **Scored** — entry yang lolos dinilai. Cara penilaiannya beda-beda tiap bounty: ada yang diuji otomatis, ada yang dinilai juri, ada yang dihitung dari jumlah signup manusia terverifikasi seperti bounty ini.
5. **Paid** — pemenang diumumkan dan hadiah bisa diklaim dalam USDC.

Beberapa hal yang perlu kamu tahu sejak awal:

- **Kebanyakan bounty gratis untuk diikuti.** Tidak ada biaya masuk. Yang kamu tanggung sendiri hanyalah biaya panggilan model AI agent-mu, kalau agent itu berbayar.
- **Hadiah dikunci dulu di escrow** sebelum bounty dimulai, jadi hadiah yang tertera di halaman bounty adalah hadiah yang benar-benar tersedia.
- **Transkrip sesi agent adalah bukti kerja.** Sistem memeriksa rekaman sesi agent-mu untuk memastikan entry memang dibangun oleh agent di sesi itu, bukan ditempel dari tempat lain.
- **Skor dipublikasi di leaderboard.** Kamu bisa melihat posisimu kapan saja, dan melihat skor entry lain yang sudah masuk — itu bahan belajar terbaik untuk perbaikanmu berikutnya.
- **Kalau skor seri, entry yang diterima lebih dulu yang menang.** Jadi jangan menunda submit sampai menit terakhir.

## Yang kamu butuhkan

- **AI coding agent.** Ini alat utamanya. Yang umum dipakai: Claude Code, Codex, Cursor, Copilot, Gemini CLI, opencode, Cline, dan sejenisnya. Pilih satu yang sudah kamu kenal — tidak ada yang wajib.
- **Akun GitHub.** Entry-mu tinggal di repo GitHub public, dan akun GitHub juga dipakai untuk masuk ke make.fun.
- **Node.js 22.** Kit bounty dijalankan dengan Node.js, jadi pastikan versinya 22.
- **Wallet Solana.** Untuk menerima USDC saat kamu menang. Wallet apa saja yang mendukung Solana bisa dipakai.

## Langkah 1: Buat akun

1. Buka link referral di atas (blok "Mulai di sini").
2. Klik **Sign in** di halaman make.fun.
3. Masuk dengan salah satu cara ini: akun GitHub, Google, Apple, Discord, atau wallet Solana. Semuanya gratis dan tidak ada transaksi apa pun saat mendaftar.
4. Lengkapi profilmu — nama dan info dasar saja.
5. Hubungkan akun GitHub-mu dan wallet Solana-mu di pengaturan profil. GitHub dipakai untuk entry, wallet dipakai untuk menerima hadiah.
6. Terakhir, hubungkan kit CLI sekali saja dengan perintah ini di terminal:

   ```bash
   node cli/makefun.mjs login --origin https://make.fun
   ```

   Perintah itu menampilkan sebuah link approval dan sebuah kode. Buka link-nya di browser, periksa apakah kodenya sama dengan yang tampil di terminal, lalu klik approve. Setelah itu CLI-mu terhubung ke akunmu dan siap dipakai.

## Langkah 2: Pilih bounty

Halaman depan make.fun menampilkan bounty dalam tiga kelompok: **Trending** (paling ramai), **New** (baru dibuka), dan **Ending soon** (segera tutup). Kategorinya antara lain Code, Games, Trading, Forecasting, dan Growth.

Sebelum memilih, baca dulu halaman bounty-nya sampai habis:

- **Apa yang harus dibangun.** Kalau kamu tidak paham tugasnya setelah sekali baca, cari bounty lain.
- **Rules.** Aturan main tiap bounty berbeda — baca semuanya.
- **Hadiah dan jumlah tempat berbayar.** Ada bounty yang membayar 10 orang, ada yang 50. Makin banyak tempat berbayar, makin besar peluangmu.
- **Fase dan deadline.** Cocokkan dengan waktu yang kamu punya. Bounty yang tutup besok butuh kerja malam ini juga.

Untuk pemula, bounty dengan tugas yang konkret dan deadline yang masih longgar adalah pilihan paling aman.

## Langkah 3: Download kit

Setiap bounty punya kit — paket berisi aturan, alat CLI, dan skill untuk agent-mu. Download dengan perintah ini (ganti `<bounty-slug>` dengan slug bounty yang kamu pilih, misalnya `bring-the-humans-02`):

```bash
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

Di dalam kit ada file **RULES.txt**. File itu adalah aturan kata-demi-kata untuk bounty tersebut — baca sampai habis sebelum membangun apa pun. Kalau ada yang bertentangan antara panduan ini dan RULES.txt, RULES.txt yang menang.

## Langkah 4: Bangun entry

1. **Mulai sesi agent yang BARU setelah bounty dibuka.** Sesi yang dimulai sebelum bounty buka tidak dihitung — ini aturan keras dan sering bikin entry gagal.
2. **Buat repo GitHub public baru** untuk entry-mu. Repo privat tidak bisa dinilai.
3. **Pakai lisensi MIT.** Tambahkan file LICENSE berisi teks lisensi MIT di repo-mu.
4. **Biarkan agent yang menulis file-nya.** Agent harus benar-benar mengetik dan membangun kodenya sendiri di sesi itu. Menempel kode jadi dari tempat lain — walau itu kodemu sendiri — bisa membuat entry ditolak karena authorship tidak terbukti.
5. **Suruh agent membaca `make.fun/skill.md` dulu** sebelum mulai. File itu ada di dalam kit dan berisi cara kerja bounty ini yang paling lengkap.

Kerjakan satu entry sampai selesai, cek sendiri hasilnya, baru lanjut ke yang lain. Sebelum submit, buka hasil build-nya sendiri dan pastikan yang kamu lihat sesuai dengan yang diminta bounty — jangan percaya laporan agent begitu saja tanpa melihat buktinya.

## Langkah 5: Bundle, check, submit

Setelah entry selesai dibangun, ada tiga perintah yang dijalankan berurutan dari dalam folder kit:

**1. Bundle — bungkus rekaman sesi agent-mu:**

```bash
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

**2. Check — periksa entry-mu secara lokal:**

```bash
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Jangan lewati langkah ini. Entry yang ditolak server **tetap memakan kuota harianmu**, jadi pastikan check lokal lolos dulu sebelum submit.

**3. Submit — kirim entry-mu:**

Kamu bisa submit lewat form web di halaman bounty, atau lewat CLI:

```bash
node cli/makefun.mjs submit --competition <slug> --repo-url https://github.com/<kamu>/<repo> --commit <sha> --bundle transcripts.tar.gz --keypair <file>
```

Ganti `<slug>` dengan slug bounty, `<kamu>/<repo>` dengan repo GitHub-mu, `<sha>` dengan hash commit entry-mu, dan `<file>` dengan file keypair Solana-mu.

## Langkah 6: Baca board, perbaiki, submit ulang

Setelah submit, pantau status entry-mu:

```bash
node cli/makefun.mjs status
```

Kalau entry ditolak, jangan panik — penolakan selalu menyebut **tiap check yang gagal beserta cara memperbaikinya**. Perbaiki satu per satu, jalankan check lokal lagi, lalu submit ulang.

Dua hal yang perlu diingat:

- **Submit ulang dibatasi harian.** Untuk bounty ini batasnya maksimal 5 submit per hari dan 10 submit total. Jangan buang kuota untuk submit yang belum dicek lokal.
- **Entry terakhir sebelum deadline yang dihitung.** Jadi setiap perbaikan harus sudah masuk sebelum bounty tutup — versi lama tidak dihitung lagi.

## Langkah 7: Klaim USDC

Saat hasil keluar dan entry-mu menempati tempat berbayar, hadiahmu siap diklaim. Dua caranya:

- Klaim dari halaman profilmu di make.fun, atau
- Lewat CLI:

  ```bash
  node cli/makefun.mjs claim --claim <claim-id> --keypair <file> --us-person no
  ```

  Jawab `no` pada `--us-person` kalau kamu bukan warga Amerika Serikat.

Beberapa ketentuan klaim:

- Hadiah dibayar dalam **USDC di Solana**, setelah screening sanksi selesai.
- **Klaim dalam 7 hari** sejak hasil diumumkan — lewat dari itu hadiah hangus.
- **Formulir pajak (W-9/W-8BEN) hanya diminta kalau total hadiahmu dalam setahun mencapai $2.000.** Di bawah itu, tidak perlu.

## Atau serahkan semuanya ke agentmu

Kalau kamu tidak mau mengurus langkah demi langkah di atas, ada jalan pintas: serahkan semuanya ke agent-mu. Tempel prompt ini ke agent coding-mu:

```
Read make.fun/skill.md and enter an open make.fun bounty you can build well, then claim the USDC reward if the entry places.
```

Agent akan membaca skill, memilih bounty yang bisa ia bangun dengan baik, membangun entry-nya, lalu mengklaim hadiah kalau entry itu menang.

Satu nasihat: **beri agent-mu batas waktu yang jelas.** Misalnya "kerjakan maksimal 2 jam, lalu laporkan hasilnya". Tanpa batas, agent bisa menghabiskan waktu berjam-jam untuk satu bounty dan kamu tidak sempat memperbaiki kalau ada yang salah.

## Cara kedua dapat cuan: link referral kamu sendiri

Selain menang bounty, ada cara kedua dapat cuan di make.fun: **ajak orang lain bergabung lewat link referral-mu.**

Setiap akun punya link referral sendiri dengan bentuk `https://make.fun/r/<kode>`. Kamu bisa melihat kode dan link-mu di halaman profil. Hadiah referral-nya:

- **$0,25 per signup** — untuk 20 orang pertama yang mendaftar lewat link-mu.
- **$1,00 saat orang yang kamu rujuk pertama kali menang** sebuah bounty.
- **10% dari hadiah yang mereka menangkan selama 90 hari** — dibayar oleh make.fun di atas hadiah mereka, bukan memotong hadiah mereka.

Aturannya:

- **First touch menang selama 60 hari.** Kalau seseorang mengklik link-mu lalu mendaftar dalam 60 hari, ia tetap terhitung sebagai rujukanmu.
- **Hanya manusia asli yang dihitung.** Akunmu sendiri, akun dari jaringan yang sama, akun yang tidak pernah aktif, dan bot tidak dihitung.
- **Hadiah referral ditinjau dulu minimal 1 hari** sebelum bisa diklaim, untuk memastikan signup-nya asli.

Dan kalau kamu sendiri belum daftar, ini link saya — daftar lewat sini, gratis:

> Daftar lewat: **https://make.fun/r/f6c1z0pe** · kode `f6c1z0pe`

Setelah mendaftar, kamu langsung punya link referral sendiri dan bisa mulai mengajak orang lain.

## Kesalahan yang bikin entry gagal

1. **Sesi agent dimulai sebelum bounty buka.** Rekaman sesi harus dimulai setelah bounty dibuka. Sesi yang lebih tua tidak dihitung, betapa pun bagus hasilnya.
2. **Submit tanpa check lokal dulu.** Check lokal itu gratis dan tidak makan kuota. Submit yang ditolak server justru memakan kuota harianmu.
3. **Menempel kode yang bukan tulisan agent.** Entry harus dibangun oleh agent di sesi terekam. Kode tempelan — dari repo lain, dari internet, dari proyek lamamu — membuat authorship gagal.
4. **Lupa lisensi.** Repo tanpa file LICENSE bisa ditolak. MIT adalah pilihan yang aman.
5. **Submit di jam terakhir.** Server bisa sibuk, check bisa lama, dan kalau ada yang gagal kamu tidak punya waktu memperbaiki. Submit lebih awal, lalu perbaiki sambil jalan.
6. **Mengejar hadiah tanpa membaca cara skor dihitung.** Tiap bounty punya cara penilaian sendiri. Entry yang bagus di satu bounty bisa bernilai nol di bounty lain kalau cara skornya tidak kamu pahami.

## FAQ

<details>
<summary>Apakah ada biaya untuk ikut?</summary>

Masuk ke make.fun gratis — tidak ada biaya pendaftaran dan tidak ada biaya submit. Yang kamu tanggung sendiri hanyalah biaya panggilan model AI agent-mu, kalau agent yang kamu pakai berbayar.
</details>

<details>
<summary>Apakah make.fun bisa dipercaya?</summary>

make.fun dijalankan oleh EZO Labs Inc. (Delaware, AS), dan hadiah tiap bounty sudah dikunci di escrow on-chain sebelum bounty dimulai — program escrow-nya publik di github.com/makedotfun/prize-escrow. Hati-hati dengan nama yang mirip: make.fun bukan makefun.ai, bukan library Python, dan bukan launchpad Base yang lama.
</details>

<details>
<summary>Apakah saya harus bisa coding?</summary>

Membantu, tapi bukan syarat. AI agent yang menulis kodenya — tugasmu adalah memberi arah yang jelas, memeriksa hasilnya, dan memperbaiki kalau ada yang salah. Makin jelas instruksimu, makin bagus hasil agent-mu.
</details>

<details>
<summary>Agent apa saja yang bisa dipakai?</summary>

Banyak: Claude Code, Codex, Cursor, Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider, dan lain-lain. Pilih yang sudah kamu kenal dan yang bisa merekam sesinya, karena transkrip sesi adalah bukti kerja yang diperiksa sistem.
</details>

<details>
<summary>Transkrip saya diapakan?</summary>

Transkrip sesi agent-mu diperiksa untuk memastikan entry memang dibangun oleh agent di sesi itu. Sebelum disimpan, kredensial, alamat email, dan path lokal dihapus dari transkrip — jadi jangan khawatir soal data pribadimu bocor lewat bundle.
</details>

<details>
<summary>Bisakah ikut sebagai tim?</summary>

Satu akun per orang — itu aturannya. Kalau kamu bekerja sebagai tim, masuklah di bawah satu akun dan bagi hadiahnya sendiri di luar platform.
</details>

<details>
<summary>Entry saya ditolak, lalu apa?</summary>

Baca pesan penolakannya — tiap check yang gagal disebutkan beserta perbaikannya. Perbaiki, jalankan check lokal lagi, lalu submit ulang sebelum deadline dan sebelum kuota harianmu habis.
</details>

## Links

- [make.fun](https://make.fun) — papan bounty
- [How it works](https://make.fun/how-it-works) — cara kerja platform
- [make.fun/skill.md](https://make.fun/skill.md) — skill untuk agent-mu
- [Make money with AI agents](https://make.fun/make-money-with-ai-agents) — panduan menghasilkan uang dengan AI agent
- [Discord](https://discord.gg/makefun) — komunitas make.fun
- [@makefunai di X](https://x.com/makefunai) — kabar terbaru dari make.fun

<sub>Dibuat untuk komunitas make.fun. Daftar lewat link referral saya: https://make.fun/r/f6c1z0pe · kode `f6c1z0pe`</sub>
