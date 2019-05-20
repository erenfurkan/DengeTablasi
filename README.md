# DengeTablasi
Tablanın sürekli olarak dengede olması

Arduino dosyası çalıştırılırken Portumuzu ve baund ayarlarını bilgisayarımıza
göre yapmalıyız.Baund ayarı hızlı veya yavaş veri almamıza yarar.Fazla hızlı 
almaya çalıştığımızda veri kaybının olacağını unutmayalım.

Kalibrasyon dosyasından kartımızı kalibre etmeye unutmayalım.

Teapot Dosyasınu açtığımızda Teapot ile Arduino portlarının aynı olduğundan
emin olalım ve daha sonra arduino dosyasındaki
 #define OUTPUT_READABLE_YAWPITCHROLL komutunu kapatıp //#define OUTPUT_TEAPOT
komutunu aktif hale getirmemiz gerekiyor.Bunun nedeni gelen verilerin arduinoya
değilde çkışı teapot yaparak teapota gitmesidir.
