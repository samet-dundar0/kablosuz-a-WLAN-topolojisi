# kablosuz_ağ_WLAN_topolojisi
Bu proje, Cisco Packet Tracer üzerinde bir ev ağısenaryosunu temel alır. Amacım kablolu bağlantısı olmayan cihazların bir Access Point üzerinden nasıl bir ağa dahil edildiğini ve IP katmanında nasıl haberleştiğini simüle etmektir.

NELER YAPTIM:

-Donanım Güncellemesi: Laptop ve masaüstü bilgisayarların üzerindeki varsayılan kablolu (FastEthernet) ağ kartlarını çıkararak, kablosuz bağlantı sağlayan WMP300N modülleriyle değiştirdim.
-WLAN Kurulumu: Tüm uç cihazları (Akıllı telefon, tablet, laptop ve PC) merkezi bir Access Point üzerinde topladım. Cihazların wireless arayüzleri üzerinden sinyal eşleşmelerini sağladım.
-IP Planlaması: Ağdaki her cihaz için çakışma olmayacak şekilde statik IP tanımlamaları yaptım. (Örn: 192.168.1.x bloğu).
-Haberleşme Testi: Konfigürasyon sonrası terminal üzerinden ping komutu kullanarak veri paketlerinin başarıyla iletildiğini doğruladım.
