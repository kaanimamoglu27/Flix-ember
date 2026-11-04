# Flix Sen Olsaydın

Hocanın yerine geç, kararını ver, gerçekte ne olduğunu gör.

- **Oyna (Safari / tarayıcı):** https://kaanimamoglu27.github.io/Flix-Sen-Olsaydin/
- **Eski sürümler:** [`eski/`](eski/) klasöründe (v2 … v24)
- **iOS uygulaması (TestFlight):** [flix-kick-up/direktor/app](https://github.com/kaanimamoglu27/flix-kick-up/tree/main/direktor/app) · yükleme rehberi: [TESTFLIGHT_REHBERI.md](https://github.com/kaanimamoglu27/flix-kick-up/blob/main/TESTFLIGHT_REHBERI.md)
- **Canlı veri:** `flix-kick-up/tools/direktor-live.mjs`, GitHub Actions ile 20 dakikada bir çalışır (flix-kick-up reposunda `.github/workflows/direktor-live.yml`) ve flix-kick-up `gh-pages` dalındaki `direktor/live.json` dosyasını günceller. "Bu haftanın maçları" bu veriden her hafta kendiliğinden kurulur.

## Nasıl oynanır
1. **Hemen oyna** ile bu haftanın gerçek Süper Lig maçını aç, hangi takımın hocası olacağını seç.
2. Üstte maç canlı oynanır. 30, 46, 60, 70 ve 80. dakikalarda oyun durur, altta karar kartları açılır.
3. Bir kart seç (oyuncu değiştir, hücuma geç, kapan ya da devam) ve **Kararı ver**e bas. Kartın altındaki yüzdeler gol şansını ve gol yeme riskini gösterir.
4. Takımın karşı karşıya kalınca nişangah çıkar: boş köşedeyken ekrana dokun.
5. Maç bitince skorun gerçek skorla karşılaştırılır. Gerçek hocadan iyi sonuç alırsan ekstra yıldız ve Flix Coin kazanırsın.

Oyun ilk açılışta bu adımları kısa bir ekranla anlatır, ana ekrandaki **Nasıl oynanır?** ile tekrar açılır.

## Klasörler
- `index.html`: oyun (tek dosya, her şey içinde)
- `eski/`: önceki sürümler
- `cember/`: bu reponun eski oyunu Flix Çember (https://kaanimamoglu27.github.io/Flix-Sen-Olsaydin/cember/)
- iOS uygulaması ve canlı veri flix-kick-up reposunda (`direktor/app/`, `direktor/live.json`).

## Modlar
- **Kariyer:** 2010-11'den bugüne bir sezon ve takım seç, sadece maçları yönet: kadro, taktik ve maç içi kararlar. Transfer ve kulüp işleri yok.
- **Gerçek maçlar:** bu haftanın Süper Lig maçları ve efsane maçlar. Gerçek hocanın kararlarıyla kendi kararlarını karşılaştır.
- **Canlı bülten:** Avrupa ve Türkiye'den maçlar, skor tahmini, biten maçı yönetme.
- **Online düello:** arkadaşınla aynı maçı yönet.
