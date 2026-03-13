# 🎲 Dice Roller App (Jetpack Compose)

Google'ın **Android Basics with Compose** eğitimindeki Unit 2 kapsamında geliştirilen bu proje, Jetpack Compose'un temel çalışma mantığını ve State (durum) yönetimini anlamamı sağlayan önemli bir kilometre taşıdır.

---

## 📸 Uygulama Önizlemesi
<p align="center">
  <img src="zar_ekran_goruntusu.png" width="300" title="Dice Roller Preview">
</p>

---

## 🛠️ Teknik Detaylar & Neler Öğrendim?

Bu proje basit görünse de arka planda şu kritik Android kavramlarını barındırıyor:

### 1. State Management (Durum Yönetimi)
Compose'un "Recomposition" (tekrar çizilme) özelliğini kontrol etmek için `remember` ve `mutableStateOf` yapılarını kullandım. 
- **Mantık:** Zar sonucu değiştiğinde Compose bunu algılar ve sadece ilgili UI bileşenini (Image) günceller.

### 2. UI Layout Components
- **Column:** Bileşenleri dikey olarak hizalamak için kullanıldı.
- **Modifier:** `fillMaxSize()`, `wrapContentSize()` ve `padding()` gibi özelliklerle uygulamanın her ekran boyutuna uyum sağlamasını sağladım.
- **Spacer:** Bileşenler arası boşlukları yönetmek için eklendi.

### 3. Kotlin Logic
- `Random.nextInt(1, 7)` ile rastgele sayı üretimi.
- `when` bloğu kullanarak üretilen sayıya göre kaynak dosyasındaki (`R.drawable`) doğru görselin dinamik olarak seçilmesi.

---


---

## 📚 Kurs Bilgisi
- **Ünite:** Unit 2 - Building App UI
- **Konu:** Interactive Apps
