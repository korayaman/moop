# moop Kullanimi kolay PHP kutuphanesi <br>
Koray YAMAN : 0532 307 95 63  <br>
Kullanim Ornekleri : <br>
Seneryo uyelik olsun ve uye eklemek isteyelim tablomuz uye stunlar ad, soyad, telefon <br>
<hr>
Ekleme Sekli
$uyeEkle=ekle("uye",array( <br>
"ad"=>"uye ad", <br>
"soyad"=>"soyad", <br>
"telefon"=>"telefon" <br>
));
<hr>
Uye Kaldirma<br>
$uyeKaldir=kaldir("uye","1");
<hr>
Uye Guncelleme 
$set=" <br>
ad='uyead', <br>
soyad='soyad', <br>
telefon='uye telefon' <br>
"; <br>
$uyeGuncelle=guncelle("uye","{$set}","1");
<hr>
