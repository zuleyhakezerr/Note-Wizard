# 🎵 Nota Bulucu

Nota Bulucu, OpenAI GPT-4 API'sini kullanarak istediğiniz şarkının notalarını bulan modern bir web uygulamasıdır. Seçtiğiniz enstrümanlar için şarkı notalarını detaylı bir şekilde sunar.

## 🚀 Özellikler

- 🎸 Çoklu enstrüman desteği
- 🌙 Karanlık/Aydınlık tema
- 📱 Responsive tasarım
- 🕒 Arama geçmişi
- 🔍 Gerçek zamanlı nota arama
- 💾 Yerel depolama desteği

## 🛠️ Teknolojiler

### Backend
- FastAPI (Python web framework)
- OpenAI GPT-4 API
- Uvicorn (ASGI sunucu)
- Python-dotenv (Çevre değişkenleri yönetimi)

### Frontend
- React.js
- Chakra UI (UI framework)
- Axios (HTTP client)
- React Icons
- LocalStorage API

## 📋 Gereksinimler

- Python 3.8+
- Node.js 14+
- npm veya yarn
- OpenAI API anahtarı

## ⚙️ Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/kullaniciadi/nota-bulucu.git
cd nota-bulucu
```

2. Backend kurulumu:
```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

3. `.env` dosyasını oluşturun:
```bash
echo "OPENAI_API_KEY=your_api_key_here" > .env
```

4. Frontend kurulumu:
```bash
cd frontend
npm install
```

## 🚀 Çalıştırma

1. Backend'i başlatın:
```bash
cd backend
source venv/bin/activate  # Windows: venv\Scripts\activate
uvicorn main:app --reload
```

2. Frontend'i başlatın (yeni bir terminal penceresinde):
```bash
cd frontend
npm start
```

3. Tarayıcınızda [http://localhost:3000](http://localhost:3000) adresini açın
<img width="701" alt="Ekran Resmi 2025-01-12 21 01 04" src="https://github.com/user-attachments/assets/b807c26b-bae5-4c1f-9c86-580b1f083b08" />

## 🎯 Kullanım

1. Şarkı adını girin
2. İstediğiniz enstrümanları seçin
3. "Notaları Bul" butonuna tıklayın
4. Sonuçları görüntüleyin

## 🔒 Güvenlik

- API anahtarınızı `.env` dosyasında güvenli bir şekilde saklayın
- `.env` dosyasını asla git deposuna eklemeyin
- CORS ayarları sadece geliştirme ortamı için yapılandırılmıştır

## 🤝 Katkıda Bulunma

1. Bu depoyu fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Bir Pull Request oluşturun

