# :airplane:Diabetes & EDA & Prediction:airplane: 
**Pima indians diabetes veri kümesi kullanılarak veri analizi ve makine öğrenmesi modeli eğitimi :star: :closed_book:**
---
📌Bu kılavuz, makine öğrenimi çalışmalarını tamamlamak için aşağıdaki adımlarla ilgili rehberlik sunar:

1. Eksik değerlerin yerine konması
2. Keşfedici veri analizi
3. Doğruluğu artırmak için yeni özelliklerin oluşturulması
4. Özelliklerin kodlanması
5. XGBM kullanımı ve hiperparametrelerin optimize edilmesi
---
Diyabet Nedir? Diyabet, pankreasın artık insülin üretemediği veya vücudun ürettiği insülini iyi şekilde kullanamadığı durumlarda ortaya çıkan kronik bir hastalıktır.

**Kullanılan veri kümesi:** Pima Indians Diabetes Database ( https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database/data )

Bu veri kümesi orijinal olarak Ulusal Diyabet ve Sindirim ve Böbrek Hastalıkları Enstitüsü'nden alınmıştır. Veri kümesinin amacı, veri kümesinde yer alan belirli tanısal ölçümlere dayanarak bir hastanın diyabet hastası olup olmadığını tanısal olarak tahmin etmektir.

**Veri Kümesi Hakkında:** Veri kümesinde yer alan özellikler ve açıklamaları:

- Pregnancies : Bir kadının hamile kalma sayısı
- Glucose : Oral glukoz tolerans testinde 2 saatlik Plazma Glikoz konsantrasyonu
- BloodPressure : Diyastolik Kan Basıncı (mm hg)
- SkinThickness : Triceps cilt kıvrım kalınlığı (mm)
- Insulin : 2 saatlik serum insülini(mu U/ml)
- BMI : Vücut Kitle İndeksi ((kg cinsinden ağırlık/m cinsinden boy)^2)
- Age : Yaş(yıl)
- DiabetesPedigreeFunction : aile geçmişine dayalı olarak diyabet olasılığını puanlar
- Outcome : 0 (diyabet hastası değil) veya 1 (diyabet hastası)

**Proje hakkında:** Bu projenin amacı bir kişinin diyabet hastası olup olmadığını sınıflandırmaktır. Veri seti birkaç Tıbbi Değişkenden (Bağımsız) ve bir Sonuç Değişkeninden (Bağımlı) oluşur Bu veri setindeki bağımsız değişkenler şunlardır: 'Pregnancies', 'Glucose', 'BloodPressure', 'SkinThickness', 'Insulin','BMI', 'DiabetesPedigreeFunction', 'Age' Sonuç değişkeni değeri, kişinin diyabet hastası olup(1) olmadığını(0) belirten 1 veya 0'dır.

📌 Bu projede diabetes verisi üzerinde veri analizi gerçekleştirildi. Verilerin keşfedici analizi yapıldı ve bu analiz sonuçlarına dayanarak veriler görselleştirildi. Eksik veriler işlendi ve yeni özellikler eklenerek veri seti zenginleştirildi.
 
📌 Kişinin insülin, glukoz vb. değerlerinden sağlıklı veya diyabet hastası olup olmadığını belirlemek için XGBM adı verilen bir makine öğrenmesi modeli kullanıldı. Model eğitildikten sonra %92.2 doğruluk ve %96.8 ROC AUC değerleri elde edildi. 
