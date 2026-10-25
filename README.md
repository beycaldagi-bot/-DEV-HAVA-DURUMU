Proje Yazarı: Beyazıt_ÇALDAĞI
# Proje Adı: Kod-Asistan Basit Kayıt 

## Projenin Amacı:
Kullanıcıdan ad ve soyadı ayrı ayrı alıp birleştirerek tek bir profil kimliği oluşturmak

## Projenin Hedefleri:
* V1.0 Ad ve soyad alma
* V2.0 Selamlama mesajı gösterme

# Projenin Kapsamı: Kullanıcı kaydı

BAŞLA
ad oku
soyad oku
profil = ad + " " + soyad
YAZ "Merhaba, " + profil
DUR

## Akış Şeması:
    basla([Başla]) --> ad[/Ad gir/]
    ad --> soyad[/Soyad gir/]
    soyad --> profil["profil = ad + soyad"]
    profil --> yaz[/Merhaba profil yaz/]
    yaz --> dur([Dur])
## Kaynakça: Programlama Temelleri