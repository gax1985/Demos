# TheAgora — Where the community speaks, and leaders listen
TheAgora connects communities with their elected representatives by highlighting local issues, public concerns, and sentiment from trusted sources. Built on transparency and open‑source principles, it empowers citizens to be heard and helps leaders respond to real community needs.


# TheAgora — Civic Engagement Platform (Kotlin Multiplatform)

TheAgora is an open-source civic-tech application designed to empower communities by connecting constituents directly with their elected representatives.

The application scans:
- Local news sources  
- Social media platforms  
- Community forums  
- Public reports  

…to identify issues affecting a neighbourhood or region. It then summarizes public sentiment and provides representatives with impartial, research-backed insights into what their community needs.

## ✨ Mission
TheAgora empowers communities by gathering local issues, public sentiment, and verified information into a transparent, open platform that connects citizens directly with their elected representatives. Inspired by the ancient Greek agora — the birthplace of public dialogue — TheAgora strengthens accountability, amplifies community voices, and helps leaders understand the real concerns shaping people’s lives.

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
