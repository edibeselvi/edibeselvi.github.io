# Kör Puanlama Sonuçları — Şeffaflık Sayfası

Bu klasör, [makale adı eklenecek] çalışmasının puanlama verilerini içerir.

- **index.html** — Etkileşimli sonuç sayfası: soru/model filtresi, nihai puanlar ve her puanın rubrikteki basamak tanımı.
- **data/nihai_puanlar.csv** — 130 yanıtın nihai (uzlaşı) puanları; her puanın kaynağı işaretlidir (`uyum` = iki kodlayıcı bağımsız olarak aynı puanı verdi; `uzlaşı` = puan müzakere oturumunda belirlendi).
- **data/rkod_model_eslestirme.csv** — Kör kod ↔ model eşleştirmesi.

Puanlama, iki kodlayıcı (Kodlayıcı 1 ve Kodlayıcı 2) tarafından model kimlikleri maskelenmiş kitapçık üzerinden bağımsız olarak yapılmış; kodlayıcılar arası güvenirlik Cohen kappa ve ağırlıklı kappa ile hesaplanmış; uyuşmazlıklar müzakere (negotiated agreement) ile çözülmüştür. Ayrıntı için makalenin Yöntem bölümüne bakınız.
