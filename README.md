# TheAgora
TheAgora scans local news and community discussions to highlight issues affecting citizens. It gives representatives a transparent, research‑backed view of public sentiment, strengthening accountability and empowering communities to shape their future.


# TheAgora — Civic Engagement Platform (Kotlin Multiplatform)

TheAgora is an open-source civic-tech application designed to empower communities by connecting constituents directly with their elected representatives.

The application scans:
- Local news sources  
- Social media platforms  
- Community forums  
- Public reports  

…to identify issues affecting a neighbourhood or region. It then summarizes public sentiment and provides representatives with impartial, research-backed insights into what their community needs.

## ✨ Mission
To strengthen democratic representation by giving every community a transparent, secure, and open-source channel to communicate with their MP, MLA, MPP, Senator, or local representative.

## 🔐 Why Open Source?
- Transparency builds trust  
- Security researchers can audit the code  
- Communities can adapt the tool to their needs  
- Prevents misuse or closed-source appropriation  

Licensed under **GPL‑3.0** to ensure the project remains free and open forever.

## 🛠️ Tech Stack
- **Kotlin Multiplatform** (Android, iOS, Desktop, Web)
- **Ktor** for networking
- **SQLDelight** or **Realm** for local storage
- **ML Kit / ONNX Runtime** for sentiment analysis
- **Coroutines + Flow** for async pipelines

## 📦 Getting Started
```bash
git clone https://github.com/gax1985/TheAgora.git
cd TheAgora
./gradlew build
