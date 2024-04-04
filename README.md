
---

# LibraSys Kütüphane Yönetim Sistemi

## Proje Hakkında
LibraSys, kütüphanelerin kitap ve üye yönetimini kolaylaştırmak amacıyla tasarlanmış bir kütüphane yönetim sistemidir. Python dili kullanılarak geliştirilmiştir ve SQLite veritabanı ile entegre çalışır. Bu sistem, kütüphanelere kitapların kaydını tutma, üye işlemlerini yönetme ve kütüphane içi sorgulamaları kolaylaştırma gibi temel işlevler sunar.

## Özellikler
- Kitap kayıt işlemleri
- Üye yönetimi
- Kitap ve üye sorgulama
- Veritabanı ile entegrasyon
- CSV dosya işlemleri

## Kurulum
LibraSys'in çalışabilmesi için Python'un sisteminizde yüklü olması gerekmektedir. Projeyi lokal bilgisayarınıza klonladıktan sonra, bağımlılıkları kurmak için aşağıdaki komutu terminalinizde çalıştırın:

```bash
pip install -r requirements.txt
```

Bu komut, projenin sorunsuz çalışabilmesi için gerekli olan tüm Python kütüphanelerini yükleyecektir.

## Kullanım
Projeyi çalıştırmak için, terminalinize aşağıdaki komutu girin:

```bash
python main_project.py
```

Bu komut, kütüphane yönetim sisteminin ana arayüzünü başlatacaktır. Buradan, kitap ekleyebilir, üye işlemlerini gerçekleştirebilir ve çeşitli sorgulamalar yapabilirsiniz.

## Katkıda Bulunma
LibraSys, açık kaynak bir projedir ve katkılarınıza açıktır. Projeye katkıda bulunmak isterseniz, lütfen aşağıdaki adımları takip edin:
1. Projeyi forklayın.
2. Feature branch'ı oluşturun (`git checkout -b feature/YeniÖzellik`).
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellikler eklendi'`).
4. Branch'ı push edin (`git push origin feature/YeniÖzellik`).
5. Yeni bir Pull Request oluşturun.

## Lisans
Bu proje [MIT lisansı](LICENSE) altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakın.

---
