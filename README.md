# Sims 1960 - MS-DOS Edition

Terminal tabanlı bir hayat simülasyonu oyunu. 1960'lı yılların MS-DOS stilinde tasarlanmış modern bir simülasyon deneyimi.

## Özellikler

- Zengin terminal arayüzü (Rich kütüphanesi ile)
- Karakter oluşturma ve geliştirme
- **Gelişmiş meslek sistemi**: Object-oriented job sınıfları ile meslek hiyerarşisi
- İş, sosyal hayat ve temel ihtiyaçlar yönetimi
- Meslek seviyesi ve deneyim sistemi
- Rastgele olaylar ve durumlar
- Çok oyunculu mod desteği
- Oyun kaydetme ve yükleme
- **Meslek bazlı özel bonuslar**: Doktor acil durum bonusu, sanatçı değişken gelir

## Meslek Sistemi

### Mevcut Meslekler
- **Teknoloji Sektörü**: Yazılımcı, Mühendis
- **Sağlık Sektörü**: Doktor (acil durum bonusu ile)
- **Eğitim Sektörü**: Öğretmen
- **Yaratıcı Sektör**: Sanatçı (değişken gelir ile)

### Meslek Özellikleri
- Her meslek kendine özgü maaş, enerji tüketimi ve deneyim kazanımı
- Seviyeye göre maaş artışı
- Mesleğe özel beceriler ve açıklamalar
- Terfi sistemi

## Kurulum

1. Gerekli paketleri yükleyin:

```bash
pip install -r requirements.txt
```

2. Oyunu başlatın:

```bash
python main.py
```

## Gereksinimler

- Python 3.7+
- pyfiglet
- inquirer
- rich

## Oyun İçi Komutlar

- **Ye**: Karakterinizin açlığını giderir
- **Uyu**: Enerji toplamanızı sağlar
- **Banyo Yap**: Temizlik seviyenizi artırır
- **İş**: İş ile ilgili eylemler
  - İşe Git: Meslekte çalışır ve para kazanır
  - İş Ara: Yeni meslek bulur
  - İstifa Et: Mevcut işten ayrılır
- **Sosyalleş**: Sosyal aktiviteler ve ilişkiler

## Teknik İyileştirmeler

- **OOP Tasarım**: Job sınıf hiyerarşisi ile inheritance kullanımı
- **Factory Pattern**: JobFactory ile meslek nesnesi oluşturma
- **Polymorphism**: Her meslek sınıfı kendine özgü davranışlar sergiler
- **Gelişmiş Error Handling**: Network bağlantıları için güçlendirilmiş hata yönetimi
- **Code Organization**: Meslek sistemi ayrı modüle taşındı

## Geliştirici

Bu oyun, Python programlama dersi final projesi olarak geliştirilmiştir. 