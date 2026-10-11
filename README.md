# Durak Durak

Verdiğin durakların hepsinden geçen en kısa rotayı bulan tek sayfalık web uygulaması.

**Canlı:** https://fignupafya.github.io/durak-durak/

- Durakları adres arayarak, haritaya tıklayarak ya da toplu yapıştırarak ekle.
- Sıra, kuş uçuşuna göre değil gerçek yol mesafesine (ya da süreye) göre hesaplanır.
- 19 durağa kadar kesin en kısa sıra (Held-Karp), üstünde sezgisel çözüm (2-opt / or-opt).
- Sonucu Google Maps'te açmak için hazır link üretir.

Sunucu ve API anahtarı yok; harita, arama ve yol verisi OpenStreetMap tabanlı açık servislerden gelir (Leaflet, Nominatim, OSRM).

## Yerelde çalıştırma

`index.html` dosyasını tarayıcıda açmak yeterli.
