# BOZ213u02a01-2.1.5-25040109
# Python print() Fonksiyonu – LAB Çalışması

## 1. Proje Hakkında

Bu proje, Python programlama dilinde `print()` fonksiyonunun kullanımını öğrenmek, ekrana metin yazdırmak ve temel programlama hatalarını incelemek amacıyla hazırlanmıştır.

Çalışma kapsamında Python IDLE kullanılarak farklı `print()` komutları denenmiş ve bilerek oluşturulan bir hata analiz edilmiştir.

## 2. Projenin Amacı

- Python'da `print()` fonksiyonunun kullanımını öğrenmek.
- Ekrana metin yazdırmayı öğrenmek.
- Tırnak işaretlerinin görevini anlamak.
- Metinler ile değişkenler arasındaki farkı kavramak.
- Python'un verdiği hata mesajlarını incelemek.
- Hatalı kodları düzelterek yeniden çalıştırmak.

## 3. Kullanılan Teknolojiler

- Python 3
- Python IDLE
- GitHub

## 4. Uygulama Aşamaları

**1. Adım: Ekrana metin yazdırma**

```python
print("Hello, Python!")
```

Çıktı:

```text
Hello, Python!
```

**2. Adım: Farklı bir metin yazdırma**

```python
print("Yaren")
```

Çıktı:

```text
Yaren
```

**3. Adım: Bilerek hata oluşturma**

```python
print(Yaren)
```

Alınan hata:

```text
NameError: name 'Yaren' is not defined
```

**4. Adım: Hatanın nedenini inceleme**

Python, tırnak işaretleri olmadan yazılan `Yaren` ifadesini bir değişken olarak algılamıştır. Ancak bu isimde bir değişken daha önce tanımlanmadığı için `NameError` hatası oluşmuştur.

**5. Adım: Hatayı düzeltme**

```python
print("Yaren")
```

Çıktı:

```text
Yaren
```

## 5. Alternatif Çözüm: Değişken Tanımlama

`Yaren` ifadesi bir değişken olarak tanımlanırsa tırnak işaretleri kullanılmadan da `print()` fonksiyonuyla yazdırılabilir.

```python
Yaren = "Merhaba Dünya"
print(Yaren)
```

Çıktı:

```text
Merhaba Dünya
```

Bu örnekte `Yaren` önceden tanımlandığı için hata oluşmamaktadır.

## 6. Projenin Faydaları

Bu çalışma sayesinde:

- `print()` fonksiyonunun temel kullanım şekli öğrenilmiştir.
- Metinlerin tırnak işaretleri içerisinde yazılması gerektiği anlaşılmıştır.
- Değişken ve metin arasındaki fark gözlemlenmiştir.
- `NameError` hatasının neden oluştuğu öğrenilmiştir.
- Python'da hata bulma ve düzeltme becerileri geliştirilmiştir.

## 7. Projenin Çalıştırılması

1. Bilgisayarda Python 3 kurulu olmalıdır.
2. Python IDLE programı açılmalıdır.
3. Projedeki `.py` uzantılı dosya açılmalıdır.
4. `Run > Run Module` seçeneği veya `F5` tuşu kullanılarak kod çalıştırılmalıdır.
5. Sonuçlar Python Shell ekranından incelenmelidir.

## 8. Sonuç

Bu laboratuvar çalışmasında Python'un temel fonksiyonlarından biri olan `print()` kullanılmıştır.

Bilerek oluşturulan `NameError` hatası sayesinde Python'da metinlerin ve değişkenlerin nasıl değerlendirildiği anlaşılmıştır.

Hata mesajları incelenerek kodun doğru yazımına ulaşılmıştır.

## 9. Lisans

Bu proje MIT Lisansı ile lisanslanmıştır. Ayrıntılı bilgi için `LICENSE` dosyasına bakılabilir.
