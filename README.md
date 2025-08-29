# 🔊 NetCoreAI Project 10 - Text to Speech (TTS)

Bu proje, **.NET Console Application** ile **System.Speech.Synthesis** kütüphanesini kullanarak basit bir **Metin → Ses (Text-to-Speech)** uygulamasıdır.  
Kullanıcıdan alınan metin, bilgisayarın varsayılan ses motoru ile seslendirilir.  

---

## 🛠️ Kullanılan Teknolojiler
- .NET Framework / .NET 8 (Windows ortamında `System.Speech` desteği ile)  
- `System.Speech.Synthesis.SpeechSynthesizer`  

---

## 📂 Proje Yapısı
- `Program.cs` → Konsoldan metin alır, `SpeechSynthesizer` ile seslendirme yapar.  
- `.csproj` → Proje yapılandırma dosyası  

---

## ⚙️ Kurulum ve Çalıştırma
1. Repo’yu klonla:
   git clone https://github.com/kullaniciadiniz/NetCoreAI_Project_10_TextToSpeech.git
   cd NetCoreAI_Project_10_TextToSpeech
Uygulamayı çalıştır:
dotnet run
Konsolda metin gir:
Metni Girin:
> Merhaba dünya, bu bir seslendirme testidir.
Çıktı: Bilgisayarın hoparlöründen girilen metin sesli okunur.

✨ Özellikler
✔️ Konsoldan girilen metni seslendirme

✔️ Ses şiddeti (Volume) ve hız (Rate) ayarlanabilir

✔️ Windows Speech API (SAPI) tabanlıdır﻿
