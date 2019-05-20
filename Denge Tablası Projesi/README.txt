Arduino dosyasý çalýþtýrýlýrken Portumuzu ve baund ayarlarýný bilgisayarýmýza
göre yapmalýyýz.Baund ayarý hýzlý veya yavaþ veri almamýza yarar.Fazla hýzlý 
almaya çalýþtýðýmýzda veri kaybýnýn olacaðýný unutmayalým.

Kalibrasyon dosyasýndan kartýmýzý kalibre etmeye unutmayalým.

Teapot Dosyasýnu açtýðýmýzda Teapot ile Arduino portlarýnýn ayný olduðundan
emin olalým ve daha sonra arduino dosyasýndaki
 #define OUTPUT_READABLE_YAWPITCHROLL komutunu kapatýp //#define OUTPUT_TEAPOT
komutunu aktif hale getirmemiz gerekiyor.Bunun nedeni gelen verilerin arduinoya
deðilde çkýþý teapot yaparak teapota gitmesidir.

