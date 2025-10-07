# Kotlin Basics: Control Structures

Bu proje, **Kotlin programlama diline giriş** seviyesinde hazırlanmış örnekleri içermektedir.  
Değişken tanımlama, veri tipleri, kullanıcıdan değer alma ve koşul yapılarının (`if-else`) kullanımı detaylı olarak gösterilmiştir.

---

##  İçerik Özeti

- Değişken türleri: `Int`, `Double`, `Float`, `String`, `Char`
- Kullanıcıdan veri alma: `readln()`
- `if-else` yapısıyla koşul kontrolü
- Dört temel matematiksel işlem (toplama, çıkarma, çarpma, bölme)
- Üs alma işlemi: `Math.pow()`
- Kullanıcı adı ve şifre doğrulama sistemi

---

##  Amaç

Bu çalışma, Kotlin dilinde temel kontrol yapılarının nasıl çalıştığını göstermek ve **giriş seviyesinde algoritma mantığını** geliştirmek amacıyla hazırlanmıştır.

---

##  Kullanılan Teknolojiler

- Kotlin (JVM)
- IntelliJ IDEA / Android Studio

---

##  Dosya Bilgisi

- **Dosya Adı:** `Kod1.kt`  
- **Paket:** `com.example.ybshafta2`

---

##  Örnek Çalıştırma

```kotlin
val sayi_int: Int = 320000
if (sayi_int % 2 == 0) {
    println("$sayi_int sayısı çift sayıdır")
} else {
    println("$sayi_int sayısı tek sayıdır")
}
