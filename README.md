# AKALIN TECH


# 🎮 Linux'ta Metin2 Keyfi! | Gameforge Gaming Platform ile Garuda Linux'ta Metin2 Çalıştırma Rehberi 🐉🐾

Merhaba, bu rehberde **Gameforge Gaming Platform** aracılığıyla **Metin2**'yi Linux sisteminizde nasıl çalıştırabileceğinizi anlatıyorum! 💻 Linux'un gücünü keşfederken, oyun dünyasında da neler yapabileceğinizi görmeye hazır olun! 🌟

## 🚀 Sistem Özelliklerim
- **OS**: Garuda Linux x86_64
- **Kernel**: 6.12.10-zen1-1-zen
- **DE**: KDE Plasma 6.2.5

Eğer siz de bu adımları takip ederseniz, Windows'a veda edip Metin2 dünyasına Linux üzerinden giriş yapabilirsiniz. 🎉

---

## 🛠 Adım 1: Gerekli Dosyayı İndirin
Gameforge Installer'ı indirmek için aşağıdaki bağlantıya gidin:
➡️ **[Gameforge İndir](https://gameforge.com/en-US/download)**

---

## 🍷 Adım 2: Wine Kurulumu ve Ayarları
Wine, Windows uygulamalarını Linux'ta çalıştırmamızı sağlar. Aşağıdaki komutlarla sisteminize Wine'ı kurun:

### ARCH TABANLI LINUX DAĞITIMLARINDA
```bash
sudo pacman -S wine winetricks
```
### DEBIAN TABANLI LINUX DAĞITIMLARINDA
```bash
sudo apt install wine winetricks
```

### ISTEĞE BAĞLI KOMUT
```bash
winetricks corefonts vcrun6
```

Wine kurulumunu tamamladıktan sonra, indirdiğiniz `GameforgeInstaller.exe` dosyasını çalıştırın:

```bash
wine gameforgeinstaller.exe
```

---

## 🔑 Adım 3: Gameforge'a Giriş Yapın
Gameforge açıldıktan sonra kullanıcı bilgilerinizle giriş yapın. 🖥
🎉 Artık Gameforge üzerinden Metin2'yi indirebiliriz!

---

## 📂 Adım 4: Metin2 Kurulumu
1. Metin2 oyununu seçin ve **Kur** butonuna tıklayın.
2. Dosya yolu olarak aşağıdaki dizini belirleyin (istediğiniz dosya yolunu belirtebilirsiniz, (yani hangi klasöre kurmak istiyorsan onu seç)):
   ```plaintext
   /home/mustafa/Documents/games/Metin2/
   ```
3. "Masaüstü ikonu oluştur" seçeneğini **kaldırın**. 🖼
4. **Install** (Yükle) butonuna tıklayın ve kurulumu başlatın! 🚀

**Not:** Yükleme sırasında %90'a geldiğinde takılabilir. Panik yapmayın! 🙌
Gameforge'u kapatıp aşağıdaki komutla tekrar çalıştırabilirsiniz:

```bash
wine gameforgeinstaller.exe
```

---

## 🕹 Adım 5: Oyunun Tadını Çıkarın
Gameforge'u yeniden başlattıktan sonra **Oyna** butonuna tıklayın ve Metin2 dünyasına adım atın! 🌍🐉

💡 Artık Metin2, sadece Windows'ta değil, **Linux'ta da oynanabilir**! 🎉

---

## ❤️ Ekstra İpuçları ve Öneriler
- **Wine Ayarları:** Daha stabil bir oyun deneyimi için `winetricks` ile eksik kütüphaneleri yükleyebilirsiniz.
- **Yedekleme:** Kurulum sırasında oyun dosyalarını yedekleyerek, ileride zamandan tasarruf edebilirsiniz.

🎉 **İyi Oyunlar!** 🎮 Eğer bu rehber işinize yaradıysa, Linux ve oyun dünyasında daha fazla rehber için bizi takipte kalın! 🚀


# AKALIN TECH
