<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=1000&lines=BEU+Veri+Yap%C4%B1lar%C4%B1+%C3%96dev+Teslim+Rehberi+%F0%9F%9A%80" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="500">
</div>

<h2 align="center">🚀 GitHub Üzerinden Ödev Teslim Süreci</h2>

<div align="center">
Bu rehber, Veri Yapıları dersi kapsamında verilen ödevlerin GitHub organizasyonu üzerinden nasıl teslim edileceğini adım adım açıklamaktadır. Lütfen tüm adımları dikkatlice takip edin.
</div>

---

### 💡 GitHub'a Yeni Başlayanlar İçin Önemli Not
Eğer Git ve GitHub komutlarına (`clone`, `add`, `commit`, `push`) yabancıysanız, sürece başlamadan önce aşağıdaki ücretsiz BTK Akademi eğitimini tamamlamanız şiddetle tavsiye edilir. Bu eğitim, tüm adımları daha kolay anlamanıza yardımcı olacaktır.

<div align="center">
  <a href="https://www.btkakademi.gov.tr/portal/course/versiyon-kontrolleri-git-ve-github-19439" target="_blank">
    <img src="https://img.shields.io/badge/BTK_Akademi-Git_ve_GitHub_Eğitimi-00BFFF?style=for-the-badge&logo=git&logoColor=white" alt="BTK Akademi Git ve GitHub Eğitimi"/>
  </a>
</div>

---

### 1️⃣ Adım 1: Organizasyon İçinde Kendi Deponuzu Oluşturun

Her öğrenci, dönem boyunca tüm ödevlerini barındıracak olan kendi deposunu doğrudan organizasyon içinde oluşturacaktır.

1.  GitHub hesabınıza giriş yapın ve organizasyonun ana sayfasına gidin: **[beu-veri-yapilari-2024-2025](https://github.com/orgs/beu-veri-yapilari-2024-2025/)**
2.  **"Repositories"** sekmesine tıklayın.
3.  Sağ tarafta bulunan yeşil renkli **"New"** butonuna tıklayın.
4.  **Repository name** (Depo adı) olarak **`adiniz-soyadiniz`** formatında, Türkçe karakter kullanmadan ve küçük harflerle isminizi yazın. (Örnek: `ahmet-yilmaz`)
5.  Repository'yi **"Public"** olarak ayarlayın.
6.  **"Create repository"** butonuna tıklayarak deponuzu oluşturun.

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="100">
</div>

---

### 2️⃣ Adım 2: Deponuzu Bilgisayarınıza Klonlayın (Clone)

Oluşturduğunuz depoyu, ödevlerinizi eklemek için bilgisayarınıza indirmeniz gerekmektedir. Bu işlem sadece **bir kere** yapılır.

1.  Oluşturduğunuz deponun ana sayfasında, yeşil **"<> Code"** butonuna tıklayın.
2.  Açılan pencerede **HTTPS** sekmesinin seçili olduğundan emin olun ve yandaki linki kopyalayın.
3.  Bilgisayarınızda terminali (Git Bash, CMD veya PowerShell) açın ve ödevlerinizin durmasını istediğiniz bir klasöre gidin.
4.  Aşağıdaki komutu yapıştırın ve çalıştırın:
    ```shell
    git clone KOPYALADIGINIZ_URL
    ```

---

### 3️⃣ Adım 3: Ödev Dosyalarını Haftalık Olarak Yükleyin (Add, Commit, Push)

Her hafta yeni ödevinizi teslim etmek için bu adımları tekrar edeceksiniz. **Her ödev kendi haftasının klasöründe olmalıdır (`hafta1`, `hafta2`, vb.).**

1.  **Dosya Gezgini'ni (File Explorer)** kullanarak bilgisayarınıza klonladığınız `adiniz-soyadiniz` klasörünü açın.
2.  Bu klasörün içinde, o haftanın ödevi için **yeni bir klasör oluşturun**. (Örneğin, sağ tıklayıp `Yeni > Klasör` seçeneği ile `hafta2` adında bir klasör açabilirsiniz.)
3.  Tamamladığınız ödev dosyalarını bu yeni oluşturduğunuz klasörün (`hafta2`) içine kopyalayın.
4.  Şimdi, `adiniz-soyadiniz` klasörünün içindeyken terminali açın.
    > **İpucu:** Windows'ta klasörün en üstündeki adres çubuğuna `cmd` yazıp `Enter`'a basarak terminali doğrudan o klasörde başlatabilirsiniz.
5.  Aşağıdaki komutları sırasıyla çalıştırarak o haftanın ödevini GitHub'a yükleyin:

    ```shell
    # 1. Adım: Tüm yeni dosyaları ve değişiklikleri ekle
    git add .

    # 2. Adım: Değişiklikleri o haftaya özel bir mesajla paketle
    # Mesajı her hafta güncellemeyi unutmayın!
    git commit -m "Hafta 2 odevleri eklendi"

    # 3. Adım: Paketi GitHub'a gönder
    git push
    ```
Bu kadar! Her hafta sadece bu adımları tekrarlayarak yeni ödevlerinizi kendi deponuza yükleyebilirsiniz. Deponuzun son hali aşağıdaki gibi görünmelidir:
```
/
├── hafta1/
│   ├── odev1.py
│   └── ...
├── hafta2/
│   ├── odev2.cpp
│   ���── ...
└── ...
```

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284136-03988914-d42b-4505-b9d4-f13b74e2c0e4.gif" width="400">
</div>

<div align="center">
  
### Başarılar! ✨
Ödevlerinizi zamanında ve doğru şekilde yüklemeyi unutmayın.

</div>
