# CicekSepeti TestAutomation Project
Bu ÇiçekSepeti Test Otomasyon projesidir. Bu projede 2 class içerisinde toplam 4 test senaryosu gerçekleşetirilmiştir. Projede Page Object Model kullanılmıştır.

## **TEST CLASS 1**
- ***Test 1 : Sepete Ürün Ekleme***

    *www.ciceksepeti.com* adresine gidilir.

    Arama yerine gelinir ve istenilen ürünün ismi yazılıp enter tuşuna basılır.

    Çıkan ürün listesinden istenilen ürün seçilir.
    
    Ürün detay sayfasındaki *"Sepete Ekle"* butonuna tıklanır.

- ***Test 2: Sepetten Ürün Çıkarma***

    *www.ciceksepeti.com* adresine gidilir.

    Arama yerine gelinir ve istenilen ürünün ismi yazılıp enter tuşuna basılır.

    Çıkan ürün listesinden istenilen ürün seçilir.
    
    Ürün detay sayfasındaki *"Sepete Ekle"* butonuna tıklanır.
    
    Butona tıkladıktan sonra yönlendirilen Sepetim sayfasında ürünün yanındaki *"X"* işaretine tıklanır.
    
    Ürün sepetten çıkarılmak için onaylanır.

## **TEST CLASS 2**

- ***Test 3 : Şifre Unutma***

    https://www.ciceksepeti.com/uye-girisi adresine gidilir.

    *"Şifremi Unuttum"* botununa basılır.

    Şifre yenileme işlemlerinin yapılacağı e-posta adresi ilgili bölüme yazılır ve *"Gönder"* botununa tıklanır.
    
    Ekrana *"Şifreniz belirttiğiniz e-posta adresine gönderildi."* bilgisi gelir.

- ***Test 4 : Ürün Filtreleme***

    *https://www.ciceksepeti.com* adresine gidilir.

    Ekranda filtre yapmak istenilen ürünün üzerine tıklanır. (Örnek: ÇİÇEK)

    Filtreleme seçeneklerinden istenilen kategoriler seçilir. (Örnek: NE İÇİN--->Doğum Günü, RENK--->Beyaz).
    
    *"Uygula botununa"* tıklanır.
    
    Ekrana ilgili ürünler listesi gelir.
