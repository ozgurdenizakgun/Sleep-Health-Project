Makine Öğrenmesi ile Uyku Bozukluklarının Tahmini ve Analizi

Bu proje, İstanbul Medeniyet Üniversitesi – Veri Bilimine Giriş Dersi final projesi kapsamında gerçekleştirilmiştir.

Projenin temel amacı, bireylerin günlük yaşam alışkanlıklarından (adım sayısı, stres seviyesi, BMI vb.) yararlanarak uyku bozukluklarını (Insomnia, Uyku Apnesi) tahmin edebilen makine öğrenmesi modelleri geliştirmektir.

Veri Seti Hakkında

Bu çalışmada Kaggle platformunda paylaşılan Sleep Health and Lifestyle Dataset kullanılmıştır.

Veri Sayısı: 374 katılımcı

Öznitelik Sayısı: 13 (Yaş, Cinsiyet, Uyku Süresi, Fiziksel Aktivite, Stres, Tansiyon vb.)

Hedef Değişken: Sleep Disorder (None, Insomnia, Sleep Apnea)

Kullanılan Teknolojiler ve Kütüphaneler

Proje Python programlama dili kullanılarak geliştirilmiştir. Aşağıdaki kütüphanelerden yararlanılmıştır:

Pandas & NumPy: Veri analizi ve veri ön işleme

Matplotlib & Seaborn: Veri görselleştirme

Scikit-learn: Makine öğrenmesi modelleri (Random Forest, KNN, Logistic Regression) ve performans metrikleri


| Model Adı                 | Doğruluk Oranı (Accuracy) |
| ------------------------- | ------------------------- |
| Random Forest             | %88.00                    |
| Logistic Regression       | %86.67                    |
| K-Nearest Neighbors (KNN) | %86.67                    |


Temel Bulgular

Stres Seviyesi: Uyku kalitesini en fazla etkileyen faktörlerden biridir. Stres seviyesi arttıkça uyku süresinde azalma gözlemlenmiştir.

BMI ve Uyku Apnesi: Vücut kitle indeksi (BMI) “Obese” ve “Overweight” kategorilerinde olan bireylerde uyku apnesi riski belirgin şekilde daha yüksektir.

Model Performansı: Random Forest algoritması, özellikle sağlıklı bireyleri sınıflandırmada yüksek doğruluk oranı elde etmiştir.
