HARİTA DÜZELTİLMİŞ SÜRÜM

Bu pakette:
- index.html: Harita il tıklama hatası giderildi.
- data.json: HARİTA DENEME.xlsm içindeki Sayfa1 verilerinden yeniden oluşturuldu.

Yapılan kritik düzeltme:
Mevcut sitede harita tıklaması select() fonksiyonunu, render() ise refreshMap() fonksiyonunu çağırıyordu; bu iki fonksiyon tanımlı değildi. Bu nedenle il sınırına dokunulduğunda JavaScript ReferenceError oluşuyor ve alt bilgi paneli boş kalıyordu.

Kurulum:
index.html ve data.json dosyalarını GitHub'daki Harita deposunun ana dizinine birlikte yükleyin/değiştirin.
