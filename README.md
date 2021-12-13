# Ortakproje
import random

# list of books is stored in the list -'books'
books =[ 'Geralt of Rivia', 'Kılıcın Yolu']

# An item from the list 'books' is selected
# by random.choice()
print(random.choice(books))

# Importing random module
import random
#  Defining list of phrases which will help to build a story
time = [' Uzun zaman önce', ' Yüzyıllar öncce','Zamanların en iyisiydi , en kötüsüydü , hem akıl çağıydı hem aptallık...']
constant1 = (" Kaosun nüksettiği topraklarda Noxus adında, \n dünyayı kendi hakimiyeti altına almayı amaçlayan  bir imparatorluk hüküm sürüyordu.  \n O sırada  Noxus'un henüz işgal etmediği, Kocaman Dağların, Göllerin çevrelediği; Eskiden huzurun her tarafa yayıldığı \n Demacia adındaki bir krallığın Basilix şehrinde Geralt adındaki ")
character = [' bir paralı asker \n ' , ' ']
story_plot = ['Yorgunluğu kehribar renkli gözlerinden belli olan ,1.86 boylarında heybetli,\n ifadesiz , Savaşın izlerinin yüzüne vurduğu,Gri saçları omzuna kadar uzanan Geralt. ']
constant2 = ("Atından inip başını okşadıktan sonra eyerini çıkartıp samanlığın üzerine koydu. \nipini Han ın dış kısmında bulunan diğer atların yanına   bağladı.  \nTozlu havanın etkisiyle birkaç kez öksürdükten sonra hânın kapısını araladı.\n İçeride gürültülü bir ortam vardı.")

second_character = [" Gerginlikleri yüzlerinden okunan bir grup asker. Aralarında yüksek sesli tartışıyorlardı:\n" 

"\n\n- Noxus Kapımıza kadar dayandı! Generalin hamle yapmasını daha ne kadar bekleyeceğiz , Öldükten sonra mı !?"
"\n--Sakin ol Kael, Askerlerin kulağının nerde olduğunu bilemezsin..."
 ]
third_character = ["\n\nHan sahibi 50 li yaşlarda sakalına ak düşmüş yaşlı bir adamdı. Boğuk sesiyle seslendi: "]
dialogue = ["\n\n--Hohoho... Seni bir daha görebileceğimi tahmin etmemiştim, Anlaşılan Gökler tarafından gözetleniyorsun... \n++Uzun zaman oldu yaşlı bunak. yolculuğum yorucu geçti ve Duyduğun üzere Karnım gurulduyor.\n --Son zamanlarda Domuzlarımız huysuz. bilirsin huysuz domuz kötü şans getirir ohohohoho(espri) Ama senin için depoya bir bakayım...\nAhh sanırım birkaç kurutulmuş geyik etimiz kalmış... "]
story_plot2 = ["\n\nHancıyla görüştükten sonra Kurutulmuş geyik eti ve bardak dolusu  birasyıla Sakin bir yere çekildi. \nYemeğini yediği sırada Gözüne ahşap zemindeki bir tümsek takıldı. Bir yandan yemeğini bitirmeye çalışırken han'ın az ışık \n alan bölgesinde neden böyle bir tümsek olduğunu kendi içinde sorgulamaya başladı. Dikkatlice \n etrafını gözledi ve tümseğe doğru hareket etti. Gerginliği yüz ifadesinden anlaşılıyordu. \n tümseğin  altında bir boşluğu keşfetti. "]
constant3 = ("heyacanlıydı,etrafına göz gezdirdi.  güvenli olduğunu düşündükten sonra eliyle o çıkıntıyı araladı. \n kenarı yırtılmış yüzeyi eskimiş bir mektup not gözüne ilişti. Tozları eliyle çırptı. Sonra küçüklüğünde gördüğü,\n  Noxus İmparatorluğunun amblemi gözüne ilişti. Ve aşina olduğu kelimeler yavaşça zihninde belirmeye başladı: \n  "  "\n- Halkımızın çağrımıza kulak verme zamanı geldi! Yüzyıllardır beklediğimiz fırsat elimizin altında. Elçilçerin çoğu Başkent Freylord a sızdı.\n  Aristokratların büyük bir kısmını tarafımıza çekmeyi başardık. Yüksek zümre Lou ve Zhui Ailesi dahil...\nBaşkentte Komutan Merlin ile hazırlıkları yapmanızın tam zamanı ! Sana kan dökmeni, Öldürmeni emrediyorum Syriel, \nSana verilen görevin öneminin farkında olduğunu sanıyorum kardeşim...Çeyrek Ay'ın Karanlık Gecesinde.  \n Noxus'un Gücü,Yüce İmparatorumuz IV.Rell in şerefi için!..  \n --- Darius Noxus'un Eli " )
constant4 = (" \n \nMektupta yazılanları şok içerisinde okuduktan sonra,Korkudan kaskatı kesildiğini fark ettikten sonra ,  \n düşürdüğünü fark ettiği mektubu yerden titreyen elleriyle alıp hızlıca cebine sıkıştırdı.Eskiden Kaldığı  \n odaya telaşla ayrıldıktan sonra kendisini izleyen bir çift göz olduğundan habersizdi...  ")
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         "# Selecting an item from each list and concatenating them.
print(random.choice(time) + constant1 +random.choice(character)+
    random.choice(story_plot)+constant2+
    random.choice(second_character)+random.choice(third_character)+ random.choice(dialogue) +random.choice(story_plot2) + constant3 + constant4 )
