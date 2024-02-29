# Overview / Genel Bakış
**ENG**
In this project, I endeavored to tackle the pressing issue of obesity prediction through a machine learning lens. The aim was to create a robust predictive model that leverages a variety of algorithms to accurately classify individuals' obesity levels based on a series of health-related features. The dataset, sourced from a Kaggle competition, provided a rich foundation for feature engineering, analysis, and model training.

**TR**
Bu projede, obezite tahmini sorununu makine öğrenimi perspektifinden ele almayı amaçladım. Bir dizi sağlıkla ilgili özelliklere dayanarak bireylerin obezite seviyelerini doğru bir şekilde sınıflandırabilen güçlü bir tahmin modeli oluşturmak hedeflendi. Kaggle yarışmasından elde edilen veri seti, özellik mühendisliği, analiz ve model eğitimi için zengin bir temel sundu.

# Data Engineering and Analysis / Veri Mühendisliği ve Analizi
**ENG**
The initial phase involved importing essential libraries and loading the dataset for preprocessing. I performed comprehensive feature engineering to enhance the dataset, which included creating new features such as BMI categories, age groups, and a healthy lifestyle score. Notably, I addressed discrepancies in the test data by aligning categorical values with the training set.

**TR**
İlk aşama, temel kütüphaneleri içe aktarmak ve veri setini ön işleme için yüklemekle başladı. Veri setini iyileştirmek için kapsamlı özellik mühendisliği gerçekleştirildi; bu, BMI kategorileri, yaş grupları ve sağlıklı yaşam puanı gibi yeni özelliklerin oluşturulmasını içerdi. Test verilerindeki tutarsızlıklar, eğitim setiyle kategorik değerleri hizalayarak giderildi.

# Visualization for Insights / İçgörü için Görselleştirme
**ENG**
Data visualization played a crucial role in this study, offering a window into the patterns and relationships within the data. Various plots, such as BMI distribution and the impact of active transportation on obesity status, were crafted using libraries like Matplotlib and Seaborn. These visualizations not only provided insights but also guided the feature engineering process.

**TR**
Bu çalışmada veri görselleştirme, veriler içindeki desenleri ve ilişkileri gösteren önemli bir rol oynadı. BMI dağılımı ve aktif ulaşımın obezite durumu üzerindeki etkisi gibi çeşitli grafikler, Matplotlib ve Seaborn kütüphaneleri kullanılarak hazırlandı. Bu görselleştirmeler sadece içgörü sağlamakla kalmadı, aynı zamanda özellik mühendisliği sürecini yönlendirdi.

# Model Development with Optuna Optimization / Optuna Optimizasyonu ile Model Geliştirme
**ENG**
I employed Optuna for hyperparameter tuning to determine the optimal settings for several classifiers, including CatBoost, XGBoost, LightGBM, Gradient Boosting, and Random Forest. The models were trained and evaluated individually, with accuracy as the primary metric. I found that the CatBoost and XGBoost models, when combined, yielded the most promising results.

**TR**
Birçok sınıflandırıcı için optimal ayarları belirlemek amacıyla hiperparametre ayarlaması için Optuna kullandım. Modeller tek tek eğitildi ve değerlendirildi, ana metrik olarak doğruluk kullanıldı. CatBoost ve XGBoost modellerinin birleşimi en umut verici sonuçları verdi.

# Ensemble Learning with Voting Classifier / Oylama Sınıflandırıcısı ile Ansambl Öğrenme
**ENG**
Seeking to amplify the predictive power, I utilized a Voting Classifier that harnessed the strengths of the individual models. The soft voting mechanism was applied to combine predictions, leading to a noteworthy improvement in the model's accuracy.

**TR**
Tahmin gücünü artırmak amacıyla, bireysel modellerin güçlerini kullanan bir Oylama Sınıflandırıcısı kullandım. Tahminleri birleştirmek için yumuşak oylama mekanizması uygulandı, bu da modelin doğruluğunda dikkate değer bir iyileşme sağladı.

# Conclusion and Submission / Sonuç ve Gönderim
**ENG**
The final step of this project was to predict obesity levels on the test set using the Voting Classifier I developed. The predictions were carefully formatted and saved into a submission file, which achieved a score of **0.91184** in the Kaggle competition, showcasing the performance of our model.

This journey through the project has been a testament to the efficacy of ensemble methods in machine learning and their capacity to refine predictions in complex scenarios like obesity prediction. The experience has been an enriching demonstration of the synergy between data science and healthcare, providing valuable insights into the practical application of advanced analytics in real-world health challenges.

**TR**
Bu projenin final adımı, geliştirdiğim Oylama Sınıflandırıcısını kullanarak test setindeki obezite seviyelerini tahmin etmekti. Tahminler özenle biçimlendirildi ve Kaggle yarışmasında **0.91184** puan alarak modelimizin performansını sergileyen bir gönderim dosyasına kaydedildi.

Bu proje yolculuğu, obezite tahmini gibi karmaşık senaryolarda tahminleri rafine etme kapasitesi ile makine öğrenimi ensemble yöntemlerinin etkinliğine bir tanıklıktır. Sağlıkla ilgili gerçek dünya zorluğuna uygulanan makine öğreniminin ayrıntılarına dair bu deneyim, veri bilimi ve sağlık bilimleri arasındaki sinerjiyi zengin bir şekilde göstermiş ve ileri analitik uygulamalarının gerçek sağlık sorunlarına nasıl değerli içgörüler sağlayabileceğini ortaya koymuştur.


**Kaggle Notebook Link = https://www.kaggle.com/code/ahtabekdas/obesity-risk-multi-class-prediction-eng-tr**

**Kaggle Project Link = https://www.kaggle.com/competitions/playground-series-s4e2**
