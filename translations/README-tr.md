# Görüşme Kodlama Üniversitesi

Aslında bunu bir yazılım mühendisi olabilmek için kısa çalışma listeleri olarak hazırladım, 
ancak bugün gördüğünüz gibi geniş bir listeye dönüştü.
Bu çalışma planını yapmaya başladıktan sonra, Amazon'da (https://startupnextdoor.com/ive-been-acquired-by-amazon/?src=ciu) Yazılım Geliştirme Mühendisi olarak işe alındım. 
Muhtemelen benim yaptığım gibi çok çalışmak zorunda kalmazsınız. 
Her neyse, ihtiyacınız olan her şey burada.

Burada listelenen öğeler devlerde dahil olmak üzere (Amazon, Facebook, Google ya da Microsoft...) hemen hemen her yazılım şirketindeki mülakatlara hazırlayacak.

*Size iyi şanlar!*

Çeviriler:
- [中文版本](#translations/README-cn.md)
- [Tiếng Việt - Vietnamese](#translations/README-vn.md)
- Çeviri İlerlemeleri:
    - [İspanyolca](#https://github.com/jwasham/coding-interview-university/issues/80)
    - [Hintçe](#https://github.com/jwasham/coding-interview-university/issues/81)
    - [İbranice](#https://github.com/jwasham/coding-interview-university/issues/82)
    - [Endonezya](#https://github.com/jwasham/coding-interview-university/issues/101)
    - [Arabça](#https://github.com/jwasham/coding-interview-university/issues/98)
    - [Türkçe](#https://github.com/jwasham/coding-interview-university/issues/90)
    - [Fransızca](#https://github.com/jwasham/coding-interview-university/issues/89)
    - [Rusça](#https://github.com/jwasham/coding-interview-university/issues/87)
    - [Ukraynaca](#https://github.com/jwasham/coding-interview-university/issues/106)
    - [Brezilya Portekizcesi](#https://github.com/jwasham/coding-interview-university/issues/113)
    - [Korece](#https://github.com/jwasham/coding-interview-university/issues/118)
    - [Telugu](#https://github.com/jwasham/coding-interview-university/issues/117)
    - [Lehçe](#https://github.com/jwasham/coding-interview-university/issues/122)
    - [Almanca](#https://github.com/jwasham/coding-interview-university/issues/135)
    - [Urduca](#https://github.com/jwasham/coding-interview-university/issues/140)
    - [Tay Dili](#https://github.com/jwasham/coding-interview-university/issues/156)
    - [Yunanca](#https://github.com/jwasham/coding-interview-university/issues/166)
    - [Italyanca](#https://github.com/jwasham/coding-interview-university/issues/170)

## Bu Nedir?

Bu rehber bir web geliştiricinin (kendi kendini eğitmiş, BT derecesi olmayan) büyük bir şirkette yazılım mühendisi olabilmesi için aylık çalışma planı olarak hazırlanmıştır.

![Coding at the whiteboard - from HBO's Silicon Valley](#https://dng5l3qzreal6.cloudfront.net/2016/Aug/coding_board_small-1470866369118.jpg)
 
Yeni mezun yazılım mühendisleri veya yazılım / web geliştiriciler'in Yazılım Mühendisliği'ne geçişi için hazırlanan bu rehberde uzun yıllara dayanan tecrübeniz varsa veya uzun yıllardır yazılım mühendisliği deneyimi yaşıyorsanız, daha zor bir mülakat bekleyin ve Google, Amazon, Facebook ve Microsoft gibi büyük yazılım şirketlerinin yazılım mühendisliğini, yazılım/web geliştiricilerden farklı gördüğünü ve bilgisayar bilimi bilgisine ihtiyaç duyduklarını unutmayın. Eğer güvenlik veya sistem mühendisi olmak istiyorsanız, bu listeden daha fazla çalışın (ağ oluşturma, güvenlik...).

---

## İçindekiler

- [Bu ne?](#bu-ne?)
- [Neden kullanıyorsun?](#neden-kullanıyorsun?)
- [Bu nasıl kullanılır](#bu-nasıl-kullanılır)
- [yeterince zeki hissetme](#yeterince-zeki-hissetme)
- [Video Kaynakları Hakkında](#video-kaynakları-hakkında)
- [Görüşme Süreci ve Genel Röportaj Hazırlığı](#görüşme-süreci-ve-genel-röportaj-hazırlığı)
- [Röportaj için bir dil seçin](#röportaj-için-bir-dil-seçin)
- [Kitap listesi](#kitap-listesi)
- [Başlamadan Önce](#başlamadan-önce)
- [Kapatılan Ne Görmeyeceksin](#kapatılan-ne-görmeyeceksin)
- [Önkoşul Bilgisi](#önkoşul-bilgisi)
- [Günlük Plan](#günlük-plan)
- [Algoritmik karmaşıklık / Büyük-O / Asimptotik analiz](#algoritmik-karmaşıklık---büyük-o---asimptotik-analiz)
- [Veri Yapıları](#veri-yapıları)
    - [Diziler](#diziler)
    - [Bağlantılı Listeler](#bağlantılı-listeler)
    - [yığın](#yığın)
    - [Sıra](#sıra)
    - [Taburelik masa](#taburelik-masa)
- [Daha Fazla Bilgi](#daha-fazla-bilgi)
    - [İkili arama](#i̇kili-arama)
    - [Bitwise işlemleri](#bitwise-işlemleri)
- [Ağaçlar](#ağaçlar)
    - [Ağaçlar - Notlar ve Arka Plan](#ağaçlar---notlar-ve-arka-plan)
    - [İkili arama ağaçları: BST'ler](#i̇kili-arama-ağaçları-bstler)
    - [Öbek / Öncelik Sırası / İkili Öbek](#öbek---öncelik-sırası---i̇kili-öbek)
    - [dengeli arama ağaçları (genel kavram, ayrıntılar değil)](#dengeli-arama-ağaçları-genel-kavram-ayrıntılar-değil)
    - [traversals: ön sipariş, inorder, postorder, BFS, DFS](#traversals-ön-sipariş--inorder--postorder--bfs--dfs)
- [Sıralama](#sıralama)
    - seçim
    - ekleme
    - heapsort
    - hızlı sıralama
    - sıralama birleştir
- [Grafikler](#grafikler)
    - yönlendirilmiş
    - yönsüz
    - bitişiklik matrisi
    - bitişik liste
    - geçişler: BFS, DFS
- [Daha Fazla Bilgi](#daha-fazla-bilgi)
    - [Özyineleme](#özyineleme)
    - [Dinamik Programlama](#dinamik-programlama)
    - [Nesne yönelimli programlama](#nesne-yönelimli-programlama)
    - [Tasarım desenleri](#tasarım-desenleri)
    - [Kombinatorikler (n seçmeli) ve Olasılık](#kombinatorikler-n-seçmeli-ve-olasılık)
    - [NP, NP-Komple ve Yaklaşım Algoritmaları](#np--np-komple-ve-yaklaşım-algoritmaları)
    - [Önbellekler](#önbellekler)
    - [Süreçler ve Konular](#süreçler-ve-konular)
    - [Makaleler](#makaleler)
    - [Test yapmak](#test-yapmak)
    - [Çizelgeleme](#çizelgeleme)
    - [Sistem rutinlerini uygulama](#sistem-rutinlerini-uygulama)
    - [Dize arama ve manipülasyonlar](#dize-arama-ve-manipülasyonlar)
    - [deniyor](#deniyor)
    - [Yüzen Nokta Numaraları](#yüzen-nokta-numaraları)
    - [Unicode](#unicode)
    - [Endianness](#endianness)
- [Ağ Oluşturma](#ağ-oluşturma)
- [Sistem Tasarımı, Ölçeklenebilirlik, Veri İşleme Deneyimi)](#sistem-tasarımı--ölçeklenebilirlik--veri-i̇şleme-deneyimi)
- [Son İnceleme](#son-i̇nceleme)
- [Kodlama Soru Uygulama](#kodlama-soru-uygulama)
- [Kodlama egzersizleri / zorluklar](#kodlama-egzersizleri---zorluklar)
- [Bir kez görüşmeye yaklaştıklarında](#bir-kez-görüşmeye-yaklaştıklarında)
- [Özgeçmişin](#özgeçmişin)
- [Röportaj geldiğinde düşünmek](#röportaj-geldiğinde-düşünmek)
- [Görüşmeci için sorularınız var](#görüşmeci-için-sorularınız-var)
- [Bir Zamanlar İş Bulundurun](#bir-zamanlar-i̇ş-bulundurun)

---------------- Bu noktanın altındaki her şey isteğe bağlıdır ----------------

- [İlave Kitaplar](#i̇lave-kitaplar)
- [Ek Öğrenme](#ek-öğrenme)
    - [Derleyiciler](#derleyiciler)
    - [Emacs ve vi (m)](#emacs-ve-vi-m)
    - [Unix komut satırı araçları](#unix-komut-satırı-araçları)
    - [Bilgi teorisi](#bilgi-teorisi)
    - [Eşlik ve Karıştırma Kodu](#eşlik-ve-karıştırma-kodu)
    - [Entropi](#entropi)
    - [Kriptografi](#kriptografi)
    - [Sıkıştırma](#sıkıştırma)
    - [Bilgisayar Güvenliği](#bilgisayar-güvenliği)
    - [Çöp toplama](#çöp-toplama)
    - [Paralel Programlama](#paralel-programlama)
    - [Mesajlaşma, Seri hale getirme ve Kuyruklama Sistemleri](#mesajlaşma-seri-hale-getirme-ve-kuyruklama-sistemleri)
    - [A*](#a)
    - [Hızlı Fourier Dönüşümü](#hızlı-fourier-dönüşümü)
    - [Bloom Filtresi](#bloom-filtresi)
    - [HyperLogLog](#hyperloglog)
    - [Yörele Duyarlı Hashing](#yörele-duyarlı-hashing)
    - [van Emde Boas Ağaçları](#van-emde-boas-ağaçları)
    - [Artırılmış Veri Yapıları](#artırılmış-veri-yapıları)
    - [N-ary (K-ary, M-ary) ağaçları](#n-ary-k-ary--m-ary-ağaçları)
    - [Dengeli arama ağaçları](#dengeli-arama-ağaçları)
        - AVL ağaçları
        - Splay ağaçları
        - Kırmızı / Siyah Ağaçlar
        - 2-3 arama ağacı
        - 2-3-4 Ağaçlar (aka 2-4 ağaç)
        - N-ary (K-ary, M-ary) ağaçları
        - B-Ağaçları
    - [k-D Ağaçları](#k-d-ağaçları)
    - [Listeleri atla](#listeleri-atla)
    - [Ağ Akışları](#ağ-akışları)
    - [Ayrık Kümeler & Birlik Bul](#ayrık-kümeler-&-birlik-bul)
    - [Hızlı İşleme İçin Matematik](#hızlı-i̇şleme-i̇çin-matematik)
    - [Treap](#treap)
    - [Doğrusal programlama](#doğrusal-programlama)
    - [Geometri, Dışbükey gövde](#geometri--dışbükey-gövde)
    - [Ayrık matematik](#ayrık-matematik)
    - [Makine öğrenme](#makine-öğrenme)
- [Bazı Konularda Ek Detay](#bazı-konularda-ek-detay)
- [Video Serisi](#video-serisi)
- [Bilgisayar Bilimi Dersleri](#bilgisayar-bilimi-dersleri)
