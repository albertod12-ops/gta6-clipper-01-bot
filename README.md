# gta6-clipper-01-bot

[![make.fun · gta6-clipper-01](https://make.fun/badge/gta6-clipper-01.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![rank](https://make.fun/badge/gta6-clipper-01/albertod12-ops/gta6-clipper-01-bot/rank.svg)](https://make.fun/bounty/gta6-clipper-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![reward](https://make.fun/badge/gta6-clipper-01/albertod12-ops/gta6-clipper-01-bot/reward.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)

IShowSpeed hugs RED HULK in GTA 6 — a 43s vertical Short (1080x1440) cut by an AI agent from the Nov 19 IShowSpeed GTA 6 livestream. Part A: the Red Hulk rampage. Part B: wounded Kyle kneels and hugs Jason. Then a 6s end card pitching make.fun. The video is public on YouTube: https://www.youtube.com/shorts/2HRzbu_7BNk

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01) · AI agents build software for cash rewards</sub>

## Upload (user uploads)

Title: IShowSpeed Hugged the RED HULK in GTA 6 😭

v2 (user: jangan identik): caption asli TikTok ditutup banner hitam.
DIBATALKAN — user: jangan ambil dari TikTok, ambil dari YouTube, rekam
dan edit sendiri, pakai style biasa.

v3 (20:59 WIB, sumber YouTube): Short YouTube "IShowSpeed sees the RED
HULK in GTA 6" (yt-_isMzFfcdao.webm, 608x1080, 117.8s, diunduh via
yt-dlp --js-runtimes node), di-crop buang caption + bar hitam, re-cut
segmen 8–28s (rampage) + 73–99s (berlutut, HUG, peluk), blur-fill
vertikal 1080x1920, gaya minimal user: 1 baris teks putih kecil tanpa
kotak/banner ("Speed just met Red Hulk in GTA 6", 6 detik pertama),
tanpa zoom, tanpa SFX, suara asli. End card pitch make.fun 6 detik.
File v3: ../gta6-speed-redhulk-clip-v3.mp4 (52s, 1080x1920, 12MB).

v4 (22:22 WIB, user: putih di tengah, rasio 3:4): frame 1080x1440,
teks putih di tengah frame. DIBATALKAN — user tunjuk contoh template
Windah (vt.tiktok.com/ZSpKn8sH5, "jason udah GANTENG banget"): facecam
atas, STRIP PUTIH di tengah + caption hitam, gameplay bawah, 3:4.

v8 (23:38 WIB, template contoh, sumber YouTube): 46 detik, 1080x1440
(3:4), facecam Speed di atas (crop dari kompilasi YouTube, facecam
asli Short terlalu kecil 92x62), strip putih tengah "speed ketemu
RED HULK di GTA 6", gameplay bawah (rampage 0–20s kompilasi +
berlutut/peluk 79–99s Short), watermark strip motion klip, end card
pitch make.fun 6 detik. File v8: ../gta6-speed-redhulk-clip-v8.mp4
(46s, 1080x1440, 13MB).

v9 (23:51 WIB, user: project ini tidak pakai watermark): SAMA seperti
v8 tapi watermark strip motion klip DIHAPUS. File v9:
../gta6-speed-redhulk-clip-v9.mp4 (46s, 1080x1440, 13MB).

v10 (00:04 WIB, user: suara telat): BUG AUDIO v6–v9 — concat lama
memetakan `-map 0:a -map 1:a` sehingga file punya DUA track audio
yang bunyi bersamaan dari detik 0 (audio bagian B menumpuk di atas
bagian A, lalu hening 20–40 detik). v10 = concat ulang dengan audio
digabung berurutan (`[0:a][1:a]concat` + apad): SATU track audio
46,16 detik, terverifikasi bunyi di 0–20 detik (mean -15,4 dB) dan
20–40 detik (mean -22,1 dB). Gambar sama persis dengan v9. File v10:
../gta6-speed-redhulk-clip-v10.mp4 (46s, 1080x1440, 13MB).

v11 (00:18 WIB, user: potongan di detik 19): BUKAN dari edit — di
sumber kompilasi, detik 17,27 ada cut ke klip lain (aerial RED
ARCADE) yang TIDAK ADA facecam-nya, jadi crop facecam tetap
menangkap area itu dan kelihatan gelap/blank 17–20 detik. v11 =
Part A dipendekkan jadi 0–17 detik (berakhir sebelum cut itu),
Part B tetap 20 detik, end card 6 detik; total 43 detik, SATU
track audio, frame 16–18 detik terverifikasi facecam utuh dan
transisi bersih. File v11: ../gta6-speed-redhulk-clip-v11.mp4
(43s, 1080x1440, 12MB).

v12 (01:02 WIB, user: suara masih telat setelah potongan):
penyebabnya BUKAN delay teknis — cross-correlation membuktikan
audio Part B sama persis dengan audio Short-nya (lag 0,000 detik,
corr 0,999). Masalahnya: facecam Part B diambil dari kompilasi
(momen rampage, 20 detik yang SAMA dengan Part A), sementara
gameplay + suara dari Short (momen pelukan, momen lain) — muka
dan suara beda momen, jadi terasa telat. Perbaikan: Part B
sekarang SEMUA dari Short yang sama — atas = gameplay lebar
(facecam kecil asli Short ikut kelihatan di pojok, sinkron),
bawah = close-up Kyle + Hulk (pelukan kelihatan besar di detik
~35). Kompilasi TIDAK punya momen pelukan (dicek 59 frame
seluruh 590 detik: Speed cuma di 0–17 detik). Facecam besar
kompilasi hanya dipakai di Part A, yang memang momennya sama.
Total 43 detik, SATU track audio (0–17 detik mean -15,0 dB,
17–37 detik mean -20,9 dB). File v12:
../gta6-speed-redhulk-clip-v12.mp4 (43s, 1080x1440, 11MB) —
INI yang di-upload. v1–v11 JANGAN dipakai.
CATATAN: 3:4 bukan Short (Short harus 9:16) — views tetap dihitung,
tapi tidak masuk rak Shorts. LESSON: trim di filter_complex tidak
memotong durasi (v5 jadi 590 detik!) — pre-trim segmen dulu dengan
-ss/-t jadi file, baru compose.

v13 (09:11 WIB, user: "mulai dari awal saja" setelah komplain v12
"beda di detik 19" — facecam besar hilang di Part B): Part B DIBANGUN
ULANG dari stream penuh 19 Nov, bukan dari Short. Pelukan ketemu di VOD
qSyo5d-dVzA "PLAYING GTA 6 EARLY ACCESS GAMEPLAY" (23:45:42) lewat jam
sub-count (rampage 62.810.939 ≈ VOD 73473; pelukan 62.811.197 di VOD
73530, dikonfirmasi visual + jam game 20:13:48). VOD diunduh range
73505–73545 (vod19B.mp4, 1920x1080+Opus). Part B (17–37 detik) =
VOD 73514–73534: facecam besar VOD di atas (crop 276:164:0:500, diukur
programatik — jangan tebak koordinat dari frame kecil), strip putih
yang sama, gameplay VOD di bawah (crop 1180:792:420:80), pelukan besar
di detik ~35. Layout sekarang SAMA dari awal sampai akhir: facecam
besar atas, strip, gameplay bawah. Audio Part B = audio VOD
(envelope corr 1,000, offset 0,0025 detik — sinkron). Total 43 detik,
SATU track audio (0–17 detik mean -15,0 dB, 17–37 detik mean -20,8 dB,
end card sunyi). File v13: ../gta6-speed-redhulk-clip-v13.mp4 (43s,
1080x1440, 14MB) — INI yang di-upload. v1–v12 JANGAN dipakai.
LESSON: input-seek di file hasil -c copy mux bisa meleset
berdetik-detik — pakai filter trim/atrim untuk window akurat; endcard
tanpa audio butuh anullsrc saat concat; concat butuh setsar=1 di semua
input video.

v14 (09:35 WIB, user: "detik 27 masih telat hampir 1 detik saat speed
ngomong redhulk dan seterusnya"): BUG AUDIO Part B v13 — audio VOD di
vod19B.mp4 TELAT ~0,9 detik dari videonya (audio seek mendarat ~0,9
detik SEBELUM video seek saat mux range download). Bukti: subtitle
"Okay." muncul di video VOD 27,75–28,0 tapi suaranya baru di 28,60;
bibir Speed bergerak di VOD 18,6–19,3 tapi suaranya di 19,55–20,25.
Anchor pelukan (teriakan 24,78 vs pelukan 24,75) menipu — itu teriakan
soal Hulk yang MERAIH, kebetulan mendarat pas pelukan selesai. FIX:
Part B di-render ulang (partB14.mp4) dengan audio atrim=start=9.9:
end=29.9 (video tetap trim 9:29) — suara dimajukan 0,9 detik.
Verifikasi: dialog "Okay." sekarang di partB14 t=18,7, subtitle di
18,75–19,0 (selisih 0,05 detik); suara "redhulk" di t=9,65–10,35,
bibir di 9,6–10,3. v14 = partA11 + partB14 + endcard-v4, 43 detik,
SATU track audio, layout sama. File v14:
../gta6-speed-redhulk-clip-v14.mp4 (43s, 1080x1440, 16MB) — INI yang
di-upload. v1–v13 JANGAN dipakai.

v15 (09:43 WIB, user: "Speed bilang redhulk di detik 26, tapi suaranya
muncul di detik 30"): v14 SALAH — offset sebenarnya ~5,0 detik, bukan
0,9 detik. Anchor "Okay." di v14 keliru (suara di 28,60 itu kata lain;
"Okay." yang asli ada di audio VOD 32,90, subtitle 27,75–28,0 → offset
5,0 detik); "redhulk": bibir di video VOD 18,15–18,30, suara di audio
23,15–23,30 → offset 5,0 detik. Penyebab: audio seek vod19B mendarat
di VOD ~73510 (batas segmen DASH 5 detik), video di ~73505. FIX: Part B
di-render ulang (partB15.mp4) dengan audio atrim=start=14.0:end=34.0
(video tetap trim 9:29) — suara dimajukan 5,0 detik. Verifikasi:
"redhulk" suara di partB15 t=9,1–9,2 vs bibir 9,15–9,30; "Okay." suara
t=18,9 vs subtitle 18,75–19,0 (selisih 0,05 detik). v15 = partA11 +
partB15 + endcard-v4, 43 detik, SATU track audio, layout sama. File v15:
../gta6-speed-redhulk-clip-v15.mp4 (43s, 1080x1440, 16MB) — INI yang
di-upload. v1–v14 JANGAN dipakai. LESSON: audio/video seek terpisah di
DASH bisa meleset kelipatan segmen (5 detik) — SELALU verifikasi offset
A/V dengan anchor subtitle/dialog sebelum render; jangan percaya satu
anchor, cocokkan minimal dua anchor independen.

Description (exact line first, then play code):

Made by my AI agent for a $500 bounty on make.fun, where you can earn money making clips with AI: https://make.fun/bounty/gta6-clipper-01
makefun-orbit-sauce-patio

#GTA6 #Shorts #ishowspeed

Publish Public as a Short, keep public until results are out. Then send
the video URL back so VIDEO.json can be filled in and the entry submitted.

File: ../gta6-speed-redhulk-clip.mp4 (52s, 1080x1920, 16MB)
