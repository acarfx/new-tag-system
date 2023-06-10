# New Tag System
Discord.js üzerine getirilmemiş v13 ve v14 botu olan bot yazarlar için global_name çıktısını event haline dökmek ve onu almak için kolay bir yöntem.
Username çıktısını görünen isme almanın tek kolay yolu budur ve "userUpdate / Events.userUpdate" eventlerinde değişim yapıldığı zaman otomatik olarak evente düşmektedir.

Benim botu kullanan insanlar sadece bu değişikliliği yapmasıyla tag sistemi görünen ad olacaktır <GuildMember>.user.username görünen adı çekecektir. Görünen adı olmayanlarda ise kullanıcı adını çekecektir. Bilginize!

v13 Kullanıcılarında hata alma ihtimali olabilir o yüzden npm install @discordjs/rest modülünü kurmanız gerekmektedir.

/node_modules/discord.js/src/structures/ bu konuma gelerek atmanız gerekmektedir.
Aklı olan yapardı neyse fazla bekletmeyede gerek yok iyi günler kolay gelsin.
