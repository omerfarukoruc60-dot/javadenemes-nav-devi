1.problem analizi
öncelikle kullanıcıdan dogru ve yanlıs sayılarını istiyoruz daha sonra bu dogru yanlıs sayılarıyla kullanıcının netini ve boş sayısını hesaplayıp tekrardan kullanıcının ekranına veriyoruz ekranda kullanıcın girdiği sınavın toplam soru sayısı dogru yanlıs bos sayısını netini kullanıcıya sunuyoruz problemde bu
2.girdi.işlem.çıktı
ilk olarak kullanıcının dogru ve yanlıs sayısını dogru girdiğini farz ettiğimiz örnegi verriyorum:
kullanıcı dogru sayısını 16 girer yanlıs sayısını ise 2
kullanıcının girdiği dogru ve yanlıs değerleri benim yazdığım if else kontrollerine uyduğu için programın bir sonraki aşamasına geçer
kullanıcının girdiği dogru ve yanlıs sayısıyla kullanıcnın netini ve bos sayısını hesaplar 
program daha sonra ise hesapladığı net saysısı ile kullanıcının durumunu bulur
bu örnekte kullanıcın bosu 2 neti ise 15.5tir
en sonda ise print kodu ile çıktıyı ekrana verir
3.matematiksel formüller
bos hesaplama için 20-(dogru+yanlıs)
net hesaplama için dogru-(yanlıs/4)
bir de if elselerdeki küçüktür büyükler var
4.sözde kod
kullanıcıdan dogru yanlıs iste
gereksinimleri karşılamayan bir sayı girilirse geçresiz sayı  yazdır
gereksinimler sağlanırsa net ve bos sayısını hesapla
net saysısına göre durumu hesapla
değişkenleri doğru tırnak içindeki kelimelerele doğru şekilde hizalayarak ekrana ver
5.akışşeması
Öncelikle programı çalıştırıp ekrana bir hoş geldin mesajı vererek işe başlıyoruz hemen ardından kullanıcıdan sınavdaki doğru sayısını girmesini istiyoruz girilen bu doğru sayısının 0dan küçük veya 20den büyük olup olmadığını kontrol ediyoruz eğer kurala uymayan bir şey girildiyse direkt "GECERSIZ GIRIS" yazdırıp programı bitiriyoruze ğer doğru sayısı geçerliyse bu kez sıra yanlış sayısını istemeye geliyor yanlıs sayısı için de aynı kontrolü yapıyoruz (0 ile 20 arasında mı diye) arıca doğru ve yanlışların toplamının 20yi geçip geçmediğine bakıyoruz eğer toplam 20yi aşarsa yine "GECERSIZ GIRIS" deyip çıkış yapıyoruz vrilen bilgiler tamamen normalse hesaplama kısmına geçiyoruz
neti bulmak için: doğru sayısından yanlıs sayısının 4e bölümünü  çıkarıyoruz
boş sayısını bulmak için toplam soru sayısı olan 20den doğru ve yanlışın toplamını çıkarıyoruz
net hesaplandıktan sonra kullanıcının başarısını değerlendirip bir durum etiketi veriyoruz:
net 15'ten büyükse 
 COK IYI
net 10'dan büyükse 
 IYI
net 5'ten büyükse 
 ORT
5 ve altındaysa 
GELISTIRILMELI
son olarak toplam soru sayısını doğru yanlış boş net ve bu başarı durumunu tek bir cümle halinde ekrana yazdırıp programı sonlandırıyoruz
6.başarı durumu koşulu
kullanıcının doğru ve yanlııs sayısını dogru girmesi sadece bunlar doğruysa kod otomatik olarka doğru bir şekilde çalışır
7.test
Doğru	Yanlış	Beklenen	              Programın sonucu	                                                  Doğru mu?
20	  0	      Net 20, Çok iyi		      TOPLAMSORUSAYISI20DOGRUSAYINIZ20YANLISSAYINIZ0BOSSAYINIZ0NETINIZ20.0DURUMCOKIYI
15	  4	      Net 14, İyi             TOPLAMSORUSAYISI20DOGRUSAYINIZ15YANLISSAYINIZ4BOSSAYINIZ1NETINIZ14.0DURUMUNUZIYI
10	  8	      Net 8, Orta		          TOPLAMSORUSAYISI20DOGRUSAYINIZ10YANLISSAYINIZ8BOSSAYINIZ2NETINIZ8.0DURUMUNUZORTA
5	    0	      Net 5, Geliştirilmeli		TOPLAMSORUSAYISI20DOGRUSAYINIZ5YANLISSAYINIZ0BOSSAYINIZ15NETINIZ5.0DURUMUNUZGELISTIRILMELI                          
0	    20	    Net -5, Geliştirilmeli	TOPLAMSORUSAYISI20DOGRUSAYINIZ0YANLISSAYINIZ20BOSSAYINIZ0NETINIZ-5.0DURUMUNUZGELISTIRILMELI	
10	  10	    Net 7,5, Orta		        TOPLAMSORUSAYISI20DOGRUSAYINIZ10YANLISSAYINIZ10BOSSAYINIZ0NETINIZ7.5DURUMUNUZORTA
15	  10	    Geçersiz giriş		      GECERSIZGIRIS
12	  9	      Geçersiz giriş		      GECERSIZGIRIS
-1	  5	      Geçersiz giriş		      GECERSIZGIRIS

doğru mu kısmı sığmadı ama hepsi doğru ayrıca yer kalmadı diyeboşluksuz bitişik yazdım 




