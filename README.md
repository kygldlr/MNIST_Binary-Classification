# 2 ve 3 Rakamları Sınıflandırma Projesi

## 1. Proje Hakkında:
Bu proje, MNIST veri setindeki 2 ve 3 rakamlarını sınıflandırmak için bir sinir ağı modeli oluşturmayı amaçlamaktadır. Proje, görüntü işleme ve sınıflandırma problemleriyle ilgilenenler için temel bir örnektir.

### 2. Kullanılan Teknolojiler:
- **PyTorch**: Model ve veri işlemleri için.
- **PIL**: Görüntü işleme için.
- **NumPy**: Veri ön işleme ve tensor dönüştürme için.
- **Matplotlib**: Eğitim doğruluk grafiğini görselleştirmek için.

### 3. Veri Seti:
- **MNIST** veri seti kullanılmıştır.
- Eğitim ve doğrulama veri setleri, 2 ve 3 rakamlarını içeren görüntülerden oluşturulmuştur.
- Görüntü piksel değerleri normalleştirilerek 0-1 aralığına getirilmiştir.

### 4. Model:
- Basit bir feedforward sinir ağı modeli kullanılmıştır.
- Model, 28x28 boyutundaki görüntüleri alır ve 3 katmanlı bir yapıda işler.
- Aktivasyon fonksiyonu olarak ReLU kullanılmıştır.

### 5. Eğitim ve Doğruluk Değerleri:
- Model, SGD optimizasyon yöntemiyle 40 epoch boyunca eğitilmiştir.
- Eğitim ve doğrulama doğruluk değerleri her validasyon adımında (valid_epoch parametresiyle) hesaplanır.
- Eğitim doğrulukları ve validasyon doğrulukları grafiği, modelin performansını görselleştirir.


### 6. Geliştirme:
Kodda, eğitilecek modelin optimizasyon parametrelerini ve eğitim süresini değiştirebilirsiniz. Grafiklerde daha fazla detay ve doğruluk değerlerinin izlenmesi için kod üzerinde değişiklikler yapılabilir.

### 7. Sonuçlar:
Model, 2 ve 3 rakamlarını sınıflandırmada başarılı bir doğruluk elde etmiştir.
Eğitim ve doğrulama doğruluk değerleri, belirli aralıklarda görülebilir.