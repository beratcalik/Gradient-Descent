**Giriş** 

Bu proje, araç fiyatlarını tahmin etmek için bir regresyon modeli geliştirmeyi amaçlamaktadır. Araç fiyatlarını etkileyen çeşitli faktörler bulunmaktadır, bunlar arasında aracın model yılı, kilometre, motor hacmi ve markası gibi özellikler yer almaktadır. Bu özelliklerin kullanılmasıyla bir regresyon modeli oluşturulacak ve eğitilecektir. Sonuç olarak, bu model, veri setindeki araçların fiyatlarını tahmin etmek için kullanılabilir.

**Yöntemler**

**1. Veri Hazırlığı:** Veri seti, araçların model yılı, kilometre, motor hacmi, markası ve fiyatı gibi özelliklerini içeren bir Data Frame'e yüklenir. Kategorik değişkenler sayısal değerlere dönüştürülür ve eksik değerler kontrol edilir.



**2. Model Eğitimi:** Özellikler (X\_train) ve hedef değişken (y\_train) ayrıştırılır. Ardından, gradient iniş algoritması kullanılarak regresyon modelinin parametreleri optimize edilir.



**3. Model Değerlendirme:** Optimize edilmiş parametreler ve maliyet fonksiyonu değeri yazdırılır.

**Sonuçlar**

Modelin optimize edilmiş parametreleri ve elde edilen maliyet fonksiyonu değeri çıktı olarak görüntülenir.

**Tartışma** 

Bu proje, araç fiyatlarını tahmin etmek için basit bir regresyon modeli kullanmaktadır. Ancak, daha karmaşık bir model veya daha fazla özellik kullanılarak modelin performansı artırılabilir. Ayrıca, daha büyük bir veri seti kullanmak ve modelin genelleme yeteneğini artırmak için çeşitli ön işleme teknikleri uygulamak da faydalı olabilir. Bu şekilde, modelin tahmin yeteneği ve doğruluğu artırılabilir.
