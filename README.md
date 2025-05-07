# 🛡️ SentinelAI – Akıllı Discord Sunucu Güvenlik Sistemi

SentinelAI, sunucunuzu sadece basit küfür/spam filtreleriyle değil, **tam anlamıyla yapay zekâ destekli bir tehdit analiz sistemiyle korur**. Yeni gelen kullanıcıları analiz eder, bot ağlarını tespit eder, davranış örüntülerini inceler ve size detaylı güvenlik kontrolü sunar.

---

## 🚀 Özellikler

- **AI Destekli Kullanıcı Analizi:** Yeni katılan kullanıcıların geçmiş aktivitelerine göre risk puanı verir.
- **Bot Ağı Tespiti:** Anormal girişler, toplu bot girişleri otomatik tespit edilir ve engellenir.
- **Risk Puanı Sistemi:** Her kullanıcı için davranış bazlı dinamik güvenlik puanı.
- **Scam/Spam Algılama:** DM üzerinden dolandırıcılık mesajlarını bile fark eder.
- **Shield Mode:** Acil durumda sunucunun kilitlenmesini sağlar.
- **Günlük Güvenlik Özeti:** Sunucuda olan biten tüm olayları admin'e özet geçer.
- **Web Panel:** Tüm tehditleri anlık olarak izleyin ve müdahale edin (Coming Soon).

---

## ⚙️ Kurulum

### Gereksinimler
- Node.js 18+
- MongoDB
- OpenAI API Key
- Discord Bot Token

### Kurulum Adımları

```bash
git clone https://github.com/kullanici-adi/SentinelAI.git
cd SentinelAI
npm install
cp .env.example .env
# .env dosyasını doldur (Token, API Key vb.)
npm run dev
```

---

## 🌐 Web Panel (Opsiyonel)

Panel klasörüne girerek ayrı frontend kurulumunu yapabilirsiniz:

```bash
cd panel
npm install
npm run dev
```

---

## ✨ Özellikler Gelecek
- Web Panel üzerinden tam kontrol
- Kullanıcı geçmişi görselleştirme
- AI tabanlı öneri sistemi
- Telegram/Email bildirim entegrasyonu

---

## ⚖️ Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.

---

## ❤️ Katkıda Bulun

Pull request’lere her zaman açığız! Yeni özellik fikirlerin varsa [Issues](https://github.com/Cexha/SentinelAI/issues) sekmesine yazmayı unutma!

---

## 👑 Geliştirici

**AIcord & SentinelAI** projeleri  
by [@Cexha](https://github.com/Cexha)
