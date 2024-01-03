# Markdown nedir ve nasıl kullanılır?

Okunması ve yazması kolay, düz metin şeklinde oluşturabileceğiniz markdown
belgelerini, HTML'e dönüştürebilir ya da github'da yayınlayabilirsiniz.  

## Kurallar
Boşuklar önemlidir. Alt satıra ```<br>``` geçmek için satır sonuna  
iki veya daha fazla boşluk koyup entere basın.  

Paragraf ```<p>``` için yazılar arasına boş bir satır bırakabilirsin. 

```\``` Bazen kaçış karakteri gerekebiliyor.

---

[Vurgu](#vurgu)

[Liste](#liste)

[Link](#link)

[Görsel](#görsel)

[Kod](#kod)

[Tablo](#tablo)

[Alıntı](#alıntı)

[Başlık](#başlık)

[Ekstralar](#ekstralar)

---

## Vurgu

```
**kalın**, __kalın__  

*italik*, _italik_

**_kalın ve italik_**,  ***kalın ve italik***, ___kalın ve italik___

~~üstüçizili~~

```


**kalın**, __kalın__

*italik*, _italik_

**_kalın ve italik_**, ***kalın ve italik***, ___kalın ve italik___

~~üstüçizili~~

---

## Liste

```
- Sırasız 
- Sırasız 

* Sırasız 
* Sırasız 

+ Sırasız
+ Sırasız

+ İçiçe Sırasız
  + İçiçe Sırasız 
    + İçiçe Sırasız


1. Sıralı
2. Sıralı
3. Sıralı

1) Sıralı
2) Sıralı
3) Sıralı
```

- Sırasız 
- Sırasız 

* Sırasız 
* Sırasız 

+ Sırasız
+ Sırasız

+ İçiçe Sırasız
  + İçiçe Sırasız 
    + İçiçe Sırasız

1. Sıralı
2. Sıralı
3. Sıralı

1) Sıralı
2) Sıralı
3) Sıralı

---

## Link

```
[Başlıklı Link](https://tr.wikipedia.org/wiki/Markdown)

Başlıksız Link
<https://datatracker.ietf.org/doc/html/rfc7763>

[Referans 1 CommonMark][1]

[Referans 2 DaringFireball][2]
.
.
.
Referanslar istenilen yerde yazılabilirler ve görünmezler
[1]: https://commonmark.org
[2]: https://daringfireball.net
```

[Başlıklı Link](https://tr.wikipedia.org/wiki/Markdown)

Başlıksız Link  
<https://datatracker.ietf.org/doc/html/rfc7763>

[Referans 1 CommonMark][1]  
[Referans 2 DaringFireball][2]


[1]: https://commonmark.org
[2]: https://daringfireball.net


---

### Tablo

```
|Başlık 1|Başlık 2|Başlık 3|
|:-------|:------:|-------:|
|Solda   |Ortada  |Sağda   |

İki nokta üst üstenin konumu önemli.
```

|Başlık 1|Başlık 2|Başlık 3|
|:-------|:------:|-------:|
|Solda   |Ortada  |Sağda   |

---

### Görsel

```
![Alt Metin](https://ornek-gorsel.com/logo.png "Başlık")

ya da referansla kullanılabilir.

![Alt Metin][3]
.
.
.
[3]: https://ornek-gorsel.com/logo.png "Başlık"
```

![Markdown](https://github.com/sezerweb/markdown/blob/main/md.png  "Başlık")

![Alt Metin][3]

[3]: https://github.com/sezerweb/markdown/blob/main/md.png "Başlık"

---

### Kod

```
Yazı içinde `kod` tırnak arasına yazılır.

    Dört boşluk
    Koyarak da kod bloğu yazabiliriz.

\```
Kod bloğu üç tırnak arasına yazılır.
Çok satırlı kodları böyle yazabiliriz.
\```
```

yazı içinde `kod` bu şekilde yazılır.

    Dört boşluk
    Koyarak da kod bloğu yazabiliriz. 

```
Kod bloğu üç tırnak arasına yazılır.
Çok satırlı kodları böyle yazabiliriz.
```

---

### Alıntı
```
> Alıntıları büyüktür işareti ile yapmak gerekiyor.

> Çok satırlı alıntı için
> 
> her satır başını işaretlemelisin 

> İç içe geçmiş alıntılar için
>
>> şöyle bir kullanım da mevcut.
```

> Alıntıları büyüktür işareti ile yapmak gerekiyor.

> Çok satırlı alıntı için
> 
> her satır başını işaretlemelisin 

> İç içe geçmiş alıntılar için
>
>> şöyle bir kullanım da mevcut.

---

## Başlık

```
# H1 Ana Başlık
## H2 Alt Başlık
### H3 Alt Başlık
#### H4 Alt Başlık
##### H5 Alt Başlık
###### H6 Alt Başlık
H1 Alternatif Ana Başlık
====================
H2 Alternatif Alt Başlık
---------------------
```

# H1 Ana Başlık

## H2 Alt Başlık

### H3 Alt Başlık

#### H4 Alt Başlık

##### H5 Alt Başlık

###### H6 Alt Başlık

H1 Alternatif Ana Başlık
====================

H2 Alternatif Alt Başlık
---------------------

## Ekstralar

```
<!---
yorum satırı
--->

Onay Kutuları
- [x] İşaretli olan
- [ ] İşaretsiz olan

Yatay Çizgiler
--- 
***
___

Github'da emoji kullanmak istersek  
:smiley:, :yum:, :alien:, :heartpulse:

Görsele Link Verme
 [![görsel alt metin](görsel url link)](link)
```
<!---
yorum satırı
--->

Onay Kutuları

- [x] İşaretli olan
- [ ] İşaretsiz olan

Yatay Çizgiler

--- 
***
___

Github'da emoji kullanmak istersek 

:smiley:, :yum:, :alien:, :heartpulse:

Görsele Link Verme

[![Markdown](https://github.com/sezerweb/markdown/blob/main/md.png "Markdown Logo")](https://github.com/sezerweb/markdown/blob/main/md.png)






