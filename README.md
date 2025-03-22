# AI Chatbot

Modern ve kullanıcı dostu bir AI chatbot uygulaması. OpenAI'nin GPT API'sini kullanarak akıllı yanıtlar verebilen, çoklu sekme desteği sunan gelişmiş bir sohbet arayüzü.


## Özellikler

- 🎨 Modern ve kullanıcı dostu tasarım
- 💬 Çoklu sekme desteği ile paralel sohbetler
- 🤖 OpenAI GPT tabanlı akıllı yanıtlar
- 📝 Sohbet geçmişi yönetimi
- ⚡ Yanıtların canlı olarak akışı
- 📤 Sohbet dışa aktarma (DOCX, TXT, PDF)
- 📎 Dosya yükleme desteği

## Kurulum

1. Repoyu klonlayın:
```bash
git clone [repo-url]
cd [repo-name]
```

2. Gerekli paketleri yükleyin:
```bash
pip install -r requirements.txt
```

3. `.env` dosyasını oluşturun:
- OpenAI API anahtarınızı `.env` dosyasına ekleyin
```
OPENAI_API_KEY=your_api_key_here
```

## Kullanım

Uygulamayı başlatmak için:
```bash
streamlit run app.py
```

Tarayıcınızda otomatik olarak açılacaktır. Eğer açılmazsa, konsolda gösterilen URL'yi tarayıcınıza yapıştırın.

## Özellik Detayları

- **Çoklu Sekme**: Farklı konularda paralel sohbetler yürütün.
- **Dosya Yükleme**: Metin ve PDF dosyalarını yükleyip analiz edin.
- **Dışa Aktarma**: Sohbetlerinizi DOCX, TXT veya PDF formatında dışa aktarın.
- **Sohbet Temizleme**: Her sekmede bağımsız olarak sohbeti temizleyin.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakın.