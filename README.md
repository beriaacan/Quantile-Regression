# Quantile-Regression

Bu repo quantile regresyon üzerine konu anlatımı ve uygulamalı örnek kod dosyası içermektedir.

"quantile_regression.ipynb" adlı kod dosyasında öğrenci notlarına bakarak yıl sonu scoreunu tahmin yapan bir kod yazmaya çalıştım, kendi oluşturduğum bu küçük sentetik dataset üzerinde quantile regresyonun daha az hata verdiği gözlemlenmiştir ama veri setinin küçük olması nedeni ile kullanımını tavsiye etmem. Kendi küçük datasetinizi normal dağılıma sahip verilerinize aykırılıklar ekleyerek yapabilirsiniz. (Sklearnın quantile regression adlı dökümantasyonunu incelemenizi tavsiye ederim bunun için)

Diğer kod örneğinde " presentationI-beriaacan.ipynb " ortalama insan hayatı üzerine tahmin yaptığım örnekte mean ve median değerlerinin outlierı  az olan veri setinde yani varyansı düsük olan veri setinde hatanın neredeyse aynı çıktığı gösterilmiştir. 

Quantile regresyonun daha iyi çalıştığı modellerde veri setinde varyansın değişken olması ya da aykırı değerlerin fazla olması gerekmektedir. Veri setinizde önce her bir sütunun dağılımını inceleyerek hangisi için quantile regresyonun gerekli olduğuna kolayca karar verebilirsiniz.

Kod ve sunumu kullanırken referans vermeyi unutmayın. Sevgiler <3

(NOT: Konu üzerine araştırma yaparken faydalı bulduğum kaynakları ekledim özellikle ilk link Quantile Regression, Envelope Fitting, and Daily PV Energy adlı yazı fizikçiler için keyifli bir uygulama seti olmuş bakmanızı tavsiye ederim)

https://bmeyers.github.io/QuantileRegression/

https://tech.instacart.com/how-instacart-delivers-on-time-using-quantile-regression-2383e2e03edb

https://ethen8181.github.io/machine-learning/ab_tests/quantile_regression/quantile_regression.html

https://github.com/ajhalthor/quantile-regression/blob/main/Quantile%20Regression.ipynb

https://mlwithouttears.com/2024/01/03/quantile-regression-an-expressive-and-robust-alternative-to-least-square/
