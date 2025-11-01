# ✍️ Proje Adı: C++ Adam Asmaca Oyunu (Hangman Console App)

Bu proje, C++ konsol ortamında geliştirilmiş, kelime tahminine dayalı klasik Adam Asmaca oyunudur.

Oyun, kelimeyi harf harf tahmin etmeye dayanır ve oyuncunun yanlış tahmin sayısı kısıtlıdır.

---

### 🛠️ KULLANILAN C++ BECERİLERİ

Bu proje, özellikle metin işleme ve döngüsel kontrol becerilerimi sergilemektedir:

* **String (Metin) İşleme:** Kelimeyi gizleme (örneğin `_ _ _`), kullanıcının harf tahminini kontrol etme ve kelimeyi açığa çıkarma işlemleri.
* **Dinamik Oyun Durumu:** Oyunun o anki durumunu (kaç harf bilindiği, kaç can kaldığı) sürekli güncelleyen değişken yönetimi.
* **Karakter/Harf Kontrolü:** Tahmin edilen harfin kelime içinde var olup olmadığını kontrol eden karşılaştırma döngüleri.
* **Kullanıcı Girişi Kontrolü:** Tekrar tahmin edilen harflerin kontrolü ve hakların doğru şekilde yönetilmesi.

### 🚀 Nasıl Çalıştırılır (Derleme)

Bu projeyi derlemek için standart C++ derleyicisi (`g++` veya Visual Studio) yeterlidir.

1.  **Deponuzu indirin/klonlayın.**
2.  Konsolu açın ve dosyanın bulunduğu dizine gidin.
3.  Aşağıdaki komutu kullanarak projeyi derleyin:

```bash
# Kod dosyanızın adı 'hangman.cpp' veya 'main.cpp' olabilir.
g++ main.cpp -o hangman

4.Oyun dosyasını çalıştırın.
./hangman
