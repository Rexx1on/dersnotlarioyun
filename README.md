# Oyun Geliştirme / Unity Ders Notları

## İçindekiler
- [1. Hafta: Unity Arayüzü ve Temel Kavramlar](#1-hafta-unity-arayuzu-ve-temel-kavramlar)
- [2. Hafta: C# Kod Sözlüğü ve Temel Komutlar](#2-hafta-c-kod-sozlugu-ve-temel-komutlar)

---

## 1. Hafta: Unity Arayüzü ve Temel Kavramlar

### Teorik Pekiştirme (Arayüz ve Kavramlar)
- **Unity Hub:** Projeleri ve Unity versiyonlarını yönettiğimiz alet çantamız.
- **LTS:** Uzun Süreli Destek (En hatasız sürüm).
- **Visual Studio:** Unity için kod yazacağımız (kod düzenleyici) program.
- **Scene:** Film Setimiz (Çalışma alanımız).
- **Game:** Oyuncunun gördüğü ekran (Kamera açısı).
- **Hierarchy:** Sahnedeki objelerin isim listesi.
- **Project:** Oyun malzemelerimizin (ses, resim, kod) durduğu depo.
- **Inspector:** Seçilen objenin özelliklerini gördüğümüz ve değiştirdiğimiz denetçi paneli.

---

## 2. Hafta: C# Kod Sözlüğü ve Temel Komutlar

### Kod Sözlüğü
- **Script:** Oyundaki objelere ne yapacağını söylediğimiz senaryo/kod dosyası.
- **void Start():** Sadece oyunun en başında bir kere çalışan kod bölümü.
- **void Update():** Oyun açık olduğu sürece saniyede defalarca, sürekli çalışan kod bölümü.
- **Debug.Log():** Unity Konsoluna mesaj yazdırmaya (hata bulmaya) yarayan komut.
- **public:** Kodda yazdığımız değişkenin Unity Inspector (Denetçi) panelinde görünmesini ve değiştirilmesini sağlayan kelime.
- **transform.Translate:** Bir objeyi x, y veya z yönünde hareket ettiren kod parçası.

### Zihin Jimnastiği (Haftaya Hazırlık)
> *"Bu hafta küpümüz durmadan, kendi kafasına göre ileri gitti. Peki biz bu küpü kendi istediğimiz zaman, klavyenin YÖN TUŞLARI (veya W, A, S, D) ile nasıl kontrol edebiliriz? Haftaya 'Eğer oyuncu W tuşuna basarsa -> İleri Git' mantığını (If sorgularını) öğreneceğiz ve ilk araba/karakter kontrolcümüzü yapacağız. Haftaya görüşmek üzere!"*
