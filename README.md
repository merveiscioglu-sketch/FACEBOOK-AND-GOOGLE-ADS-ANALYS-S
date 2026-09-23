# 📊 Facebook ve Google Ads Veri Analizi Projesi

Bu proje, Facebook ve Google Ads reklam performans verileri ile GA4 e-ticaret etkinlik verilerinin BigQuery SQL kullanılarak analiz edilmesi ve Tableau üzerinde görselleştirilmesi amacıyla hazırlanmıştır.

---

## 📌 Proje Kapsamı ve Analizler
Proje kapsamında aşağıdaki temel iş metrikleri ve dönüşüm performansları analiz edilmiştir:

* **GA4 Etkinlik & Kullanıcı Zaman Analizi:** Kullanıcıların e-ticaret hiyerarşisindeki adımları ve zaman bazlı davranışları.
* **Dönüşüm Hunisi (Funnel) Analizi:** `session_start` adımından `purchase` adımına kadar olan kullanıcı dönüşüm oranları.
* **Kanal & Reklam Performansı:** Facebook ve Google Ads kampanyalarının erişim, harcama ve ROAS değerlerinin karşılaştırılması.
* **Haftalık Rekor & Kesintisiz Yayın Analizleri:** Reklam setlerinin sürdürülebilirliği ve tepe performans günleri.

---

## 🛠️ Kullanılan Teknolojiler
* **SQL / Google BigQuery:** Veri sorgulama, temizleme, dönüşüm hunileri ve pencere (window) fonksiyonları.
* **Tableau Public:** İnteraktif gösterge panelleri (dashboards) ve görsel raporlama.
* **GitHub:** Kod deposu ve sürüm kontrolü.

---

## 📁 Sorgu Dosyaları
Depoda yer alan `.txt` / `.sql` dosyaları:
1. `2021 ETKİNLİKLERİ.txt` – Temel e-ticaret etkinlik parametrelerinin çekilmesi.
2. `GA4 DÖNÜŞÜM HUNİSİ 2021.txt` – Kullanıcı dönüşüm adımlarının analizi.
3. `GA4 KANAL DÖNÜŞÜM 2021.txt` – Trafik kaynakları ve kanallara göre dönüşüm metrikleri.
4. `GA4 KULLANICI ZAMAN ANALİZİ.txt` – Zaman bazlı kullanıcı etkileşim sorguları.
5. `GA4 EKSTRA GÖREV KORELASYON.txt` – Etkinlikler arası ilişki sorguları.
