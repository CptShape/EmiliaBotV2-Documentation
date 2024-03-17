# MusicBot V1.0

- /play : Müzik çal.
- /playlist-shuffle : Mevcut playlist'i karıştır.
- /playlist : Mevcut playlistte kaç şarkı kaldığını ve sıradaki 10 şarkıyı görüntüle.
- /volume [int volume] : Ses seviyesini ayarlar.
- /stop : Playlisti durdur ve botu at
- /pause : Şarkıyı durdur
- /resume : Şarkıyı devam ettir
- /skip : Şarkıyı geç
- /position : Mevcut şarkının kaçıncı dakika ve saniyesinde olduğumuzu görüntüler.

# V 1.0.1

- /pause komutu hem durdurma hem başlatma işlemi yapıyor, /resume komutu sadece başlatma işlemi yapıyor.
- /skip komutundan sonra kaç tane şarkı geçileceği girilebiliyor.
- /play komutunu kullanırken "-shuffle" ayarını etkinleştirerek playlist shuffle'lanıp oynatılmaya başlanır.
- /play komutunun default aratma yeri youtube, defaul isplaylist'i ise false'a ayarlandı.
- /playlist-save [query] [name] [options]: server'a özel unique isimle query kaydeder.
- /playlists : serverdaki playlistlerin isim ve query'lerini yazdırır.
- /playlist-load [name] [options]: serverda aratılan isimdeki query bulunur ve playlist'e eklenir.
- /music-data [user] : Her şarkı bittiğinde odada bulunan kullanıcılara +1 ekleyerek Database'de "Dinlenilen şarkı sayısı" kaydedilir. Server başı ve toplam olarak görüntülenebilir.

# Mümkün Geliştirmeler

- playlist-shuffle için daha kısa bir komut düşünülebilir.
- playlist komutu geliştirilebilir.
- volume ile girilen değer Database'e kaydedilebilir.
- /playlist-save ile oluşturulan playlist options'larını değiştirmek için /playlist-update gibi bir komut kullanılabilir