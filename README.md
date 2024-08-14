Java ile Mayın Tarlası
Proje Hakkında
Bu proje, klasik Mayın Tarlası (Minesweeper) oyununu Java programlama dili ile terminal tabanlı olarak geliştirilmiştir. Oyuncu, bir ızgara üzerinde rastgele yerleştirilmiş mayınlardan kaçınarak tüm güvenli hücreleri açmaya çalışır.

Özellikler
Rastgele Mayın Yerleştirme: Mayınlar, oyun ızgarasında rastgele yerleştirilir.
Dinamik Oyun Alanı: Oyun alanının boyutunu ve mayın sayısını belirleyebilme.
Komut Satırı Arayüzü: Oyun komut satırı üzerinden oynanır, her hamlede güncellenmiş ızgara ekranda gösterilir.
Oyun Sonu Kontrolü: Oyuncu bir mayına bastığında oyunun sona ermesi; tüm güvenli hücreler açıldığında oyunun kazanılması.

Kullanım
Oyun başlatıldığında, komut satırında bir oyun alanı oluşturulur. Oyuncu, satır ve sütun numaralarını girerek bir hücre seçer. Hücre açıldığında:

Eğer hücrede mayın varsa oyun biter.
Eğer hücrede mayın yoksa, etrafındaki mayınların sayısı gösterilir.
Oyuncu, tüm mayınsız hücreleri açana kadar oyuna devam eder. Tüm mayınsız hücreler açıldığında oyun kazanılır.
