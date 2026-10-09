# Kütüphane Yönetim Sistemi

Global AI Hub Python eğitiminin sonunda yazdığım küçük bir komut satırı uygulaması. Kitapları `books.txt` adlı bir metin dosyasında tutuyor; listeleme, ekleme ve silme yapılabiliyor.

```text
*** MENU ***
1) List Books
2) Add Book
3) Remove Book
q) Quit
```

- Her kitap tek satırda saklanıyor: `ad,yazar,yayın yılı,sayfa sayısı`
- Yayın yılı ve sayfa sayısı sayı değilse tekrar soruluyor
- Aynı kitap ikinci kez eklenemiyor
- Dosya program boyunca açık tutuluyor, nesne silinirken kapatılıyor

## Çalıştırma

Python 3 yeterli, ek paket yok.

```bash
python lms.py
```

Python'da dosya işlemleri ve sınıf yapısıyla ilk denemelerimden biri. Bugün yazsam kitapları CSV ya da SQLite ile tutardım; virgül içeren bir kitap adı şu an satırı bozuyor.
