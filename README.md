# Datathon - Veri Analizi Yarışması

Bu proje, Hacettepe AI Club tarafından düzenlenen Datathon 2025 yarışması için hazırlanmış ve Insider'dan alınan gerçek veriler üzerinde çalışılmıştır.

## Veri Seti Açıklaması

Google Play Store Apps veri seti şu sütunları içermektedir:

- **CSAT_Survey_Data**: Kullanıcıların, uygulama ve sağlanılan servis hakkındaki anket oylamaları.
- **Customer_Age_Data**: MJüşterilerin yaş verileri.
- **Customer_MRR_Data**: Müşterilerin aylık yinelenen gelir verileri.
- **Customer_Revenue_Data**: Müşterilerin sağlanan servis ile kazandıkları kazanç verileri.
- **Help_Ticket_Data**: Servis ile ilgili açılan yardım bilet verileri.
- **Newsletter_Interaction_Data**: Sağlanılan servisin haber bültenine ilişkin veriler.
- **Product_Bug_Task_Data**: Sağlanılan servisin hata ve hataları çözme verileri.
- **RegionAndVertical_Data**: Müşterilere ait bölgesel veriler.
- **StatusAndLevel_Data**: Servisi kullanan müşterilerin kurum seviyesi verileri.

## Kullanılan Kütüphaneler ve Yöntem
Bu denli sayıda csv dosyalarını birleştirirken outer yöntemi kullandık.

- **Pandas**
- **Numpy**
- **Matplotlib**
- **Seaborn**

## Veri Üzerinde Yapılan Süreçler
Bu veri analizi projesi içerisinde verileri işleme ve temizleme için bu işlemler gerçekleştirildi:

- **Eksik Verilerin İşlenmesi**: Her bir sütuna en uygun şekilde eksik veriler elden geçirildi.
- **Çifte Veriler**: Veri setinde bulunan çifte veriler kaldırıldı.
- **İstatistiksel Analiz**: Sayısal sütunların standart sapma gibi istatistiksel değerleri incelendi.
- **Veri Görselleştirme**: İçgörüler için veriler görselleştirilme işlemlerine tâbi tutuldu

## Yarışma Sonucu
Yarışma sonucunda 12. olmayı başardık.

