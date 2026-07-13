Olist E-Ticaret Veri Analizi ve Operasyonel Performans Projesi
Bu proje, Olist E-Ticaret veri seti üzerinde Python kullanarak gerçekleştirilen uçtan uca bir veri analizi sürecini ve bu analizlerin Power BI ile görselleştirilmesini kapsamaktadır. Çalışma kapsamında müşteri davranışı, lojistik performans ve satış metrikleri detaylıca incelenmiştir.

Proje Kapsamı ve Analiz Detayları
1. Veri Hazırlama ve Temizleme (Python)
Veri setindeki farklı dosyalar (orders, items, customers, payments, products) analiz için tek bir veri çerçevesinde birleştirilmiştir.

Eksik veriler (missing values) tespit edilmiş ve analiz sürecini bozmayacak şekilde işlenmiştir.

Ödeme verileri sipariş bazında tekilleştirilerek (aggregation) sağlıklı bir ciro analizi yapısı kurulmuştur.

2. Temel Analiz Bulguları
Müşteri Sadakati: Tekrar alışveriş yapan müşteri oranı %3.12 olarak hesaplanmış, müşteri elde tutma (retention) stratejilerinin önemi vurgulanmıştır.

Müşteri Segmentasyonu: Müşteriler; low, medium, high ve vip olarak 4 segmente ayrılmış; büyük çoğunluğun düşük ve orta segmentte yoğunlaştığı tespit edilmiştir.

Lojistik Performans: Siparişler ortalama 12 gün erken teslim edilmesine rağmen, 188 güne varan uç operasyonel gecikmeler tespit edilmiştir. Şehir bazlı teslimat performansı analiz edilmiştir.

Satış ve Gelir Analizi:

En yüksek ciro getiren kategoriler: bed_bath_table, health_beauty ve computers_accessories.

Ödeme Yöntemleri: Kredi kartı en çok tercih edilen yöntem olup, yüksek tutarlı alışverişlerde tercih edildiği gözlemlenmiştir.

Taksit Analizi: Taksit sayısı arttıkça ortalama sepet değerinin (AOV) arttığı, müşterilerin yüksek fiyatlı ürünlerde taksit avantajını kullandığı saptanmıştır.

Zaman Serisi Analizi: Satışların haftanın belirli günlerinde ve saatlerinde (özellikle 13:00 - 21:00 arası) yoğunlaştığı, yıl bazında ise 5. ayın ciro zirvesi olduğu belirlenmiştir.

Kullanılan Teknolojiler
Python (Pandas, Matplotlib, NumPy): Veri temizleme, istatistiksel hesaplamalar ve görselleştirme.
