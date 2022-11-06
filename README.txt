Hazırladığım veri seti Yolov4 ile eğitilmiştir. Veri seti ve eğitilmiş .weights uzantılı dosya açıklamaya eklenmiştir.
Sadece iskambil destesinde bulunan Sinek A, Maça 8,Kupa K, Karo Q, Kupa A nesneleri tanımakta ve sınıflandırmaktadır.

# yolo-with-opencv
Bu reponun amacı openCV kütüphanesiyle yolo modellerini kullanmak.

Kodun içerisindeki kütüphaneler:
opencv, matplotlib, numpy.

Modelinizi kullanabilmek için modelin ağırlık(.weights), config(.cfg) ve isim(.names) dosyasına ihtiyacınız var. 

Main dosyası içerisindeki readNetFromDarknet() fonksiyonu içerisine kendi .weights dosyanızı ve .cfg dosyanızın ismini yazmanız gerekiyor.

classFile = 'obj.names' satırındaki .names dosyasının ismini de kendi .names dosyanızın ismiyle değiştirmeniz gerekiyor.

