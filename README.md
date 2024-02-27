# Obesity Risk Multi Class Prediction
This project focuses on predicting the risk of obesity among individuals based on their eating habits and physical condition using various machine learning models. The objective is to classify individuals into one of the seven obesity levels ranging from 'Insufficient Weight' to 'Obesity Type III'.
# Project Overview
* Data Preprocessing: The dataset undergoes a comprehensive preprocessing phase, including handling missing values, feature engineering to create new insightful features like BMI (Body Mass Index) categories, and transforming categorical variables for machine learning readiness.
* Feature Engineering: New features such as BMI, Age Categories, Healthy Lifestyle Score, Active and Passive Transport, and Total Water Intake were introduced to provide more depth and improve model accuracy.
* Model Training and Optimization: Multiple models including CatBoost, XGBoost, LightGBM, Gradient Boosting, and RandomForest were trained. Hyperparameter tuning was performed with Optuna to find the optimal settings for each model.
* Ensemble Learning: The project leverages ensemble methods, particularly Voting Classifier, to combine the predictions of the individual models. This approach aims to improve prediction accuracy by considering the strengths of each base model.
* Evaluation: Models were evaluated based on accuracy, and the best-performing models were identified through comparative analysis.
# Key Findings
* The combination of CatBoost and XGBoost models using a soft voting mechanism achieved the highest accuracy, highlighting the effectiveness of ensemble methods in improving predictions.
* Feature engineering played a crucial role in enhancing model performance by introducing new perspectives and information extracted from the raw data.

# Turkish:
# Obezite Riski Çok Sınıflı Tahmin
Bu proje, bireylerin yeme alışkanlıkları ve fiziksel durumlarına dayanarak obezite risklerinin tahmin edilmesine odaklanmaktadır. Amaç, bireyleri 'Yetersiz Ağırlık' ile 'Obezite Tip III' arasında değişen yedi obezite seviyesinden birine sınıflandırmaktır.
#Proje Genel Bakış
* Veri Ön İşleme: Veri seti, eksik değerlerin ele alınması, yeni anlamlı özelliklerin oluşturulması gibi kapsamlı bir ön işleme aşamasından geçmektedir. BMI (Vücut Kitle İndeksi) kategorileri gibi yeni özellikler eklenmiş ve makine öğrenimi için kategorik değişkenler dönüştürülmüştür.
* Özellik Mühendisliği: BMI, Yaş Kategorileri, Sağlıklı Yaşam Skoru, Aktif ve Pasif Ulaşım, Toplam Su Tüketimi gibi yeni özellikler tanıtarak model doğruluğunu iyileştirmek ve veriye daha derin bir bakış açısı kazandırmak amaçlanmıştır.
* Model Eğitimi ve Optimizasyon: CatBoost, XGBoost, LightGBM, Gradient Boosting ve RandomForest dahil olmak üzere çoklu modeller eğitilmiştir. Optuna ile her model için hiperparametre ayarlaması yapılarak optimal ayarlar bulunmuştur.
* Topluluk Öğrenimi: Proje, bireysel modellerin tahminlerini birleştirmek için topluluk yöntemleri, özellikle Voting Classifier kullanmaktadır. Bu yaklaşım, her temel modelin güçlü yönlerini dikkate alarak tahmin doğruluğunu artırmayı amaçlamaktadır.
* Değerlendirme: Modeller doğruluk bazında değerlendirilmiş ve karşılaştırmalı analiz ile en iyi performans gösteren modeller belirlenmiştir.
# Temel Bulgular
* CatBoost ve XGBoost modellerinin yumuşak oylama mekanizması kullanılarak kombinasyonu en yüksek doğruluğa ulaşmış, topluluk yöntemlerinin tahminleri iyileştirmede etkili olduğunu göstermiştir.
* Özellik mühendisliği, ham veriden elde edilen yeni bilgileri ve perspektifleri tanıtarak model performansını artırmada önemli bir rol oynamıştır.
