# Instacart Veri Analizi | Power BI & Machine Learning

Instacart alışveriş verileri kullanılarak müşteri davranışları, sipariş alışkanlıkları ve ürün performansının analiz edildiği uçtan uca veri analizi projesidir.

## Kullanılan Teknolojiler

- **Google BigQuery** — Veri depolama ve SQL sorgulama
- **dbt** — Veri temizleme, dönüştürme ve veri modelleme
- **SQL** — Veri sorgulama ve hazırlama
- **Power BI** — Veri görselleştirme ve interaktif dashboard
- **DAX** — KPI ve analitik metriklerin oluşturulması
- **Python** — Machine Learning ve tahminleme çalışmaları

## Veri Analizi Süreci

Proje kapsamında uçtan uca bir veri analizi süreci gerçekleştirilmiştir:

**BigQuery → dbt → Power BI → Python / Machine Learning**

### 1. Veri Aktarımı | BigQuery

Ham Instacart verileri **Google BigQuery** ortamına aktarılmış ve analiz için SQL sorguları hazırlanmıştır.

### 2. Veri Temizleme ve Modelleme | dbt

**dbt** kullanılarak:

- Veri temizleme işlemleri gerçekleştirilmiştir.
- İlgili tablolar birleştirilmiştir.
- Analiz için kullanılabilecek veri modelleri oluşturulmuştur.

### 3. Veri Görselleştirme | Power BI

Hazırlanan veri modelleri BigQuery üzerinden **Power BI**'a aktarılmıştır.

Power BI kullanılarak:

- KPI'lar oluşturulmuştur.
- Siparişlerin zamansal dağılımı analiz edilmiştir.
- Müşteri davranışları ve sadakat göstergeleri incelenmiştir.
- Ürün ve satış performansı analiz edilmiştir.
- Yeniden sipariş davranışları incelenmiştir.
- İnteraktif dashboard'lar oluşturulmuştur.

### 4. Machine Learning | Python

Projenin son aşamasında **Python** kullanılarak Machine Learning çalışmaları gerçekleştirilmiştir.

Elde edilen Machine Learning sonuçları Power BI raporunun sonuç bölümünde sunularak, veri analizi çıktıları ile birlikte değerlendirilmiştir.

## Analiz Kapsamı

- KPI ve temel performans göstergeleri
- Siparişlerin zamansal dağılımı
- Müşteri davranışları ve sadakat
- Ürün ve satış performansı
- Yeniden sipariş davranışları
- Müşteri ve ürün ilişkileri
- Machine Learning sonuçları

## Dashboard Görselleri

### Proje Özeti

![Proje Özeti](images/01-giris.png)

### KPI Analizi

![KPI](images/02-kpi.png)

### Zaman Analizi

![Zaman Analizi](images/03-zaman-analizi.png)

![Zaman Analizi](images/04-zaman-analizi.png)

### Müşteri Analizi

![Müşteri Analizi](images/05-musteri-analizi.png)

![Müşteri Analizi](images/06-musteri-analizi.png)

### Ürün Analizi

![Ürün Analizi](images/07-urun-analizi.png)

![Ürün Analizi](images/08-urun-analizi.png)

![Ürün Analizi](images/09-urun-analizi.png)

### Sonuçlar ve İş Önerileri

![Sonuçlar ve İş Önerileri](images/10-sonuclar.png)

## Power BI Raporu

Power BI raporu:

[📊 Instacart Veri Analizi — Power BI Raporu](./Instacart-Veri-Analizi.pbix)

> `.pbix` dosyasını görüntülemek ve raporu incelemek için bilgisayarınızda Power BI Desktop bulunması gerekir.

## CV'de Kullanım

**Instacart Veri Analizi | BigQuery, dbt, Power BI, Python**

Instacart verileri üzerinde BigQuery ve dbt kullanılarak veri temizleme ve modelleme gerçekleştirilmiş; Power BI ile KPI, müşteri, ürün ve sipariş analizlerini içeren interaktif dashboard'lar geliştirilmiş ve Python ile Machine Learning çalışmaları gerçekleştirilmiştir.

**Kullanılan teknolojiler:** BigQuery · SQL · dbt · Power BI · DAX · Python

> Workintech eğitim projesi.
