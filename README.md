# Grup-9-Isletim-Sistemi-Proje-Odevi

## Grup Üye Adları
  - Bilal Yıldız
  - İsmail Karaçayır
  - Furkan Argün

## Dosya Listesi ve Açıklama
 - src klasörü=> İçerisinde .c uzantılı dosyasyı bulunduruyor. Bu dosya derlenerek .out uzantılı dosya oluşturuluyor.
 - bin klasörü=>İçerisinde out uzantılı dosya oluşturuluyor.Bu dosya çalıştırılarak kabuk başlatılıyor.
 - Kabuk.c => Linux işletim sistemi üzerinde çalışan kabuk yapısını oluşturmak için yazdığımız kodları içeriyor.
 - Makefile=>Makefile çalıştırılarak src dosyası  içerisindeki kabuk.c derleniyor ve bin klasörü içerisinde .out uzantılı dosya oluşturuluyor ve çalıştırılıyor..

## Programı Derlemek İçin Talimatlar
 - Komut satırı açılarak "cd [Dosya ismi] " şeklinde proje dosyasına girilmeli.
 - Komut satırına make yazılarak proje çalıştırılmalı.
 

## Programlarınızı/komut Dosyalarınızı Çalıştırma Talimatları
  - exit => exit komutu girilirse shell sonlandırılıyor.
  - cd => cd komutları ile içinde bulunulan dosya dizini değiştirilebiliyor.
  - echo,cat, ps  => gibi komutlar ve başka birçok komut proceses oluşturarakta çalıştırılabilir.

## Geliştirme Sırasında Karşılaşılan Zorluklar
  - Showpid ile fork komutunu kullanmadan nasıl 5 adet child oluşturup pid'sini yazdııraileceğimizi araştırmamıza rağmen bulamadık.
  - cd komutu ile eğer iki veya daha fazla kelimeden oluşan bir dizine girmek isteniyorsa bu 2 kelimeyi parametre olarak nasıl gösterebileceğimiz konusunda zorlandık. Örnek klasör ismi "İşletim Sistemleri".
  - C dili tecrübemiz çok az olması nedeniyle genel char dizileri ve pointerlar üzerinde işlem yapmakta zorlandık.
  - Process oluşumuyla ilgili türkçe kaynak az olduğu için genel process işlemlerinde zorlandık.

## Kaynaklar
  - https://www.geeksforgeeks.org/making-linux-shell-c/
  - https://stackoverflow.com/

