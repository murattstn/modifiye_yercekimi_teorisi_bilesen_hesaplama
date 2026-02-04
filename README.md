# Modifiye Yerçekimi Teorilerinde Parametre Yığılmalarının Sayısal Analizi

Bu çalışma, **modifiye yerçekimi teorilerinde** ortaya çıkan sabitlerin ve parametrelerin belirli değerler etrafında **yığılma (accumulation / clustering)** eğilimi gösterip göstermediğini incelemek amacıyla hazırlanmıştır.

Çalışmanın temelini, **yazara ait bir modifiye yerçekimi modeli** oluşturmaktadır. Bununla birlikte kod yapısı, yalnızca bu modele bağlı kalmayacak şekilde tasarlanmış ve **başka modifiye yerçekimi teorilerinden türetilen denklemlere genellenebilir** hale getirilmiştir.

## Bilimsel Motivasyon

Genel Görelilik kuramının ötesine geçen modifiye yerçekimi teorileri, çoğunlukla ek parametreler, düzeltme terimleri veya bağlanım sabitleri içerir. Bu parametrelerin hangi değerleri alabildiği genellikle gözlemsel kısıtlarla ele alınırken, **sayısal olarak parametre uzayında nasıl davrandıkları** daha az incelenmiştir.

Bu çalışma şu soruya odaklanmaktadır:
- Parametreler uzayı düzgün (homojen) mi doldurur?
- Yoksa belirli değerler etrafında **çekici (attractor benzeri)** davranışlar mı sergiler?

## Yöntem

- Parametreler için belirli aralıklar tanımlanır.
- Denklemler döngüler aracılığıyla sayısal olarak taranır.
- Ortaya çıkan değerlerin frekansları ve dağılımları incelenir.
- Belirli noktalarda yoğunlaşma gözlenmesi durumunda, bu noktalar yığılma bölgeleri olarak değerlendirilir.

Çalışma deterministik ve keşif amaçlıdır; istatistiksel çıkarım veya gözlemsel uyum hedeflenmemektedir.

## Genelleştirilebilirlik

Kodun ilk uygulaması yazara ait bir modifiye yerçekimi teorisine dayansa da:

- Sayısal döngü yapıları belirli bir modele bağımlı değildir.
- Farklı teorilerden elde edilen denklemler kolaylıkla uyarlanabilir.
- Aynı yığılma analizi başka teorik çerçeveler için de kullanılabilir.

Bu yönüyle proje, **modelden bağımsız sayısal bir analiz aracı** olmayı hedeflemektedir.

## Uygulama Detayları

- Proje tek bir Python dosyasından oluşmaktadır.
- Sembolik hesaplama yerine sayısal yöntemler kullanılmıştır.
- Kod içerisinde yer alan yorumlar, hem matematiksel hem fiziksel varsayımları açıklamaktadır.
- Okunabilirlik ve genişletilebilirlik ön planda tutulmuştur.
