# Saklanan Veriler

HOFX Bot verileri genellikle saklamaz. Sakladığı veriler "User ID, Guild ID" vb. şeylerdir. 

# Kaydedilen Veriler hangi komutlardır ve ne amaçla saklanır.
`Ekonomi Sistemi, Botlist sistemi, Kayıt Sistemi, Moderasyon Komutları, Owner Komutları`

### Ekonomi Sistemi alınan veriler ne amaçla saklanır.
`para` komutu, sizin paranızın ne kadar olduğunu göstermesi amacıyla. (Alınan veriler `User ID`)
`para-gönder` komutu, siz birine para gönderdiğinizde karşı tarafa para eklemek ve sizden o miktarda para siler. (Alınan veriler `User ID`)
`günlük` komutu, Her 24 saatte bir rastgele bir miktar sizin hesabınıza para ekler. (Alınan veriler `User ID`)


### Botlist Sistemi
`botlist-ayarla <yetkili_rol> <bot_log> <bot_ekle>` komutu, sunucunuzda botlist sistemini aktif eder. (Alınan veriler `Guild ID, Channel ID(Bot Log, Bot Ekle)`)        

`botlist-mesajgönder` komutu, Eğerki botun attığı bot ekleme mesajı silinirse kullanılır. (Alınan veriler `Guild ID`)                                                    

`bot-ekle (Buton, Modal)` komutu, Botunuzun bilgilerini girerek botu sisteme eklersiniz. (Alınan veriler `Guild ID, User ID(Bot ID, Owner ID), Bot Prefix`)

### Kayıt Sistemi (Güncellemede Gelecek! YAKINDA...)
`kayıt-mesaj-gönder` komutu, Eğerki botun attığı kayıt olma mesajı silinirse kullanılır. (Alınan veriler `Guild ID, Channel ID(Kayıt Ol kanal ID)`)                      

`kayıt-ayarla <kayıt_olma_kanalı> <kayıt_esnasında_üyeye_verilecek_rol> <kayıt_esnasında_üyedem_alınacak_rol>` komutu, sunucunuzda kayıt sistemini aktif eder. (Alınan veriler `Guild ID, Channel ID(Kayıt Olma Kanalı), Rol ID(Kayıt esnansında üyeye/üyeden verilecek/alınacak rol)`)                                                        

`kayıt-sıfırla` Kayıt sistemini kapatır. (Alınan veriler `Guild ID`)

### Owner Komutları
`karaliste-al | karaliste-çıkar` komutu, Bir kullanıcı ID'si girerek botun kulanmasını engeller. (Alınan veriler `User ID`)                                              

`premium-kodoluştur` komutu, Rastgele premium kodu oluşturur. (Alınan veriler `Kod`)

# Kullanıcı Hakları (Botu Kullananların)
Botu kullanmakta özgürsünüz ama bazı kısıtlamalarımız vardır. Bunlar; Botta hata, sorun vb. şeyler varsa bize bildirmeli, botta eksikler varsa bize ulaşıp bildirebilirsiniz. Son olarak botta açık varsa bunu değerlendirmeyin veya kimselere söylemeyin aksi takdir karalisteye alınırsınız ve adli işlemler başlatılır, bize ulaşınız.


Verilerini sildirmek isteyenler `AliBerat#6892` ulaşabilir, eğerki şüphe duyuyorsız kullanmayın botu!                                                                    

Verileriniz VDS(Sanal Makina)'da saklanmaktadır, bilgilerinizi kimselerle paylaşmayız!
