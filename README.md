# spotify

Spotify Mahnı Hit Flop Təsnifatı (Classification)
Bu layihədə Spotify platformasından toplanmış musiqi xüsusiyyətləri əsasında mahnıların hit (uğurlu) və ya flop (uğursuz) olub-olmadığını təxmin edən maşın öyrənməsi modeli yaradılmışdır.

Layihənin Məqsədi
Spotify mahnılarının müxtəlif akustik və audio xüsusiyyətlərinə əsaslanaraq onların hit və ya flop olma ehtimalını qabaqcadan proqnozlaşdırmaq. Bu, musiqi sənayesində uğurlu mahnıların təyini və analizində istifadə oluna bilər.

İstifadə olunan Alətlər və Kitabxanalar
Python 3

Pandas, NumPy — verilənlərin işlənməsi və analizi

Scikit-learn — maşın öyrənməsi modelləri və verilənlərin öncədən emalı

Seaborn, Matplotlib — vizuallaşdırma və analiz

İşləmə Addımları
Verilənlərin Yüklənməsi və İlk Analiz
Dataset oxunur, məlumatların tip və keyfiyyəti yoxlanılır.

Təkrarlanan Sətrlərin Silinməsi
Duplikatlar aradan qaldırılır.

Outlier (İstisna Dəyər) Analizi
IQR metodu ilə istisnalar aşkar edilir.

Vizual Analiz
Hər ədədi sütunun paylanması boxplot və histogramlarla göstərilir.

Əlaqə Analizi
Xüsusiyyətlər arasında korrelasiya matrisi yaradılır və istilik xəritəsi ilə göstərilir.

Verilənlərin Hazırlanması

Sayısal xüsusiyyətlər standartlaşdırılır (StandardScaler)

Kateqorik xüsusiyyətlər (məsələn, track, artist) one-hot encoding ilə çevrilir

Train-Test Bölünməsi
Verilənlər 80% təlim və 20% test qruplarına ayrılır.

Model Qurulması və Təlimi
Logistic Regression modeli öncədən emal mərhələləri ilə pipeline şəklində hazırlanır və öyrədilir.

Modelin Qiymətləndirilməsi

Dəqiqlik (accuracy)

Precision, Recall, F1-score

ROC əyrisi və AUC skoru

Konfüzyon matrisi

Nəticələrin Vizuallaşdırılması və Təhlili

Hit və flop mahnıların xüsusiyyətlərinin müqayisəsi

Modelin ən vacib xüsusiyyətlərinin əhəmiyyət dəyərləri


