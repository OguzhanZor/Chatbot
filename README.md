Ai CHATBOT

Pytroch destekli yapay zekalı sohbot botu

Yararlanılan pytroch tutorial (çalısma mantıgı temeli) ::: https://www.youtube.com/playlist?list=PLqnslRFeH2UrFW4AUgn-eY37qOAWQpJyg

Türkçe Dogal dil işleme kütüphanesi ::: Zemberek NLP https://github.com/ahmetaa/zemberek-nlp 

Proje temel başlama sayfası chat.ipynb sayfasından başlamaktadır.

Telegram bot yapmak için telegramın web hug(kanca) larından yararlanılmaktadır. 
telegram botu başlatmak için telegramBot.ipynb sayffasından başlatılmalıdır.

Not(Düzeltilecek ve güncellenecek)

Webhug mesajları send yapmak için birden fazla telegram sayfasında send fonk vardır onların içindeki linkler düzeltirlmelidir. 
Yoksa istenilen cevaplar kapanmış web kancalarına gidebilir buda kullanıcıya hiç cevap gönderilmemesine sebeb olur.

send fonksiyonu tek bir sınıf olarak düzenlenip öbür sayfalara gönderilmesi için düzenleme yapılacaktır.


nltk_utils.ipynb içersindeki def ner(text) fonksiyonunda hiç bir lokasyon bulunmadıgında " " (tek boşluk) stringi göndemektedir buda ileri doğru 
beklenmedik sıkıntılar yaratmaktadır fonksiyon geri dönüşü düzenlenlenecektir.
