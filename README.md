# KTU-Tez-Latex
Karadeniz Teknik Üniversitesi Yüksek Lisans ve Doktora yazım kurallarına göre oluşturulmuş Latex Şablonu

[![Generic badge](https://img.shields.io/badge/Overleaf-1E96C0.svg)](https://shields.io/) ![CI status](https://github.com/overleaf/logo-exercise/workflows/CI/badge.svg)
* * *
Sadece [overleaf](https://www.overleaf.com/) hesabından çalıştırın.
* * *

```
NOT : Dosyanın resmiyeti  yoktur. Sadece bir şablondur.

```
## Yapılacaklar

- [x] Yazım yöntemi *Times New Roman* ve *12 punto*
- [x] Sayfa düzeni üst ve sol kenardan *3cm* alt ve sağ kenardan *2.5cm* boşluk
- [x] Önsöz, İçindekiler, Türkçe ve İngilizce Özetler, Genel Bilgiler, Bulgular gibi ana başlıklar *4cm* aşağı ve *1.5cm* aralıklı satır boşluğu
- [x] Bütün metinler *1.5* satır aralıklı
- [x] Tablo ve Şekil başlıkları sol tarafa yaslanmalı
- [x] Tablo ve Şekil etiket isimleri alt satıra inerse metnin aynı hızasında devam etmeli
- [x]  Paragraflar *1cm* içerden başlamalı
- [x]  Tüm alt başlıklar ve sınıflandırma numaraları koyu (**bold**) karakterde yazılmalı
- [x] Bölüm başlığı ile ara başlık ve ara başlıkla
metin arasında 1,5 satır aralığı 1 boşluk bırakılmalı
- [x] Tezin Ön sayfaları Romen rakamları ile
(I,II,III,IV...) sayfanın alt orta olmalı
- [x] İç kapaklara numara konmaz
- [x] Numaralama **Önsöz** sayfasının altına yazılan **(III)** sayısı ile başlar
- [x] 1. Genel Bilgiler ile başlayan kısmı, sayfanın **orta üst** kısmında yer alacak şekilde Arap rakamları (1, 2, 3) ile numaralandırılmalı
- [x] Genel bilgiler  sayfasına numara **konmamalı** bölümünün ikinci sayfasında **2** ile başlamalı
- [x] Alt başlıklar arasında **2 satır** aralığı 1 boşluk bırakılmalı
- [x] Sabit değişkenler ayrı bir yere toplanacak
- [ ] Okunurluk arttırılacak
- [ ] Kodlara yorum satırı yazılacak
- [ ] Dış kapaklar Enstüti Sayfasına göre tasarlanacak


## Dosya dizin yapısı


1. Chapters
	- abstract.tex
	- contents.tex
	- diskapak.tex
	- genelbilgiler.tex
	- giris.tex
	- kaynaklar.tex
	- konuileilglilibasliklar.tex
	- kısaltmalar.tex
	- literatur.tex
	- onsoz.tex
	- ozet.tex
	- sonuclar.tex
	- tezEtik.tex
2. Figures
	-  IP_ground_.png
	-  ...
3.  ktustyle.sty
4.  main.tex
5.  References.bib

## Chapters
Bu dizin altında tezinizde hangi bölümlerin olmasını istediğinizi ekliyorsunuz.

## Figures
Bu dizin altında metinlerinizi görsellerle daha ayrıntılı anlatmak için görüntülerini koyduğunuz dizin.

## ktustyle.sty
Bu dosyanın içerinde ise program `main.tex` derlenirken hangi kurallara göre olacağını ve ayrıca değişkenleri set ettiğiniz yer.

## main.tex
Latex dosyasımız derlendiği kernel olarak düşünebiliriz. İçi ne kadar az isi o kadar okunaklığı artar.

## References.bib
Bu dosyada ise tezin/makalenizin referanslarla desteklediğiniz kişileri eklediğiniz yer.
