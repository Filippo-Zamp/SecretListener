# 🎧 Secret Listener

**Secret Listener** è un'app Flutter progettata per ascoltare messaggi vocali di **WhatsApp** salvati sul dispositivo **senza aprire l'app di WhatsApp** e quindi **senza lasciare visualizzato il messaggio** al mittente.

## 🚀 Funzionalità

- 📁 **Selezione dei file audio**: Usa il selettore di file per scegliere un messaggio vocale `.opus` o `.ogg` salvato da WhatsApp.
- ▶️ **Riproduzione nascosta**: Ascolta l’audio direttamente nell’app senza attivare la spunta blu su WhatsApp.
- ⏩ **Velocità di riproduzione**: Passa da velocità normale (1.0x) a veloce (2.0x) per ascoltare i messaggi più rapidamente.
- 🖼️ Interfaccia semplice e intuitiva, con un design scuro moderno.

## 📸 Screenshot

![Secret Listener Logo](https://static.vecteezy.com/system/resources/previews/023/986/631/original/whatsapp-logo-whatsapp-logo-transparent-whatsapp-icon-transparent-free-free-png.png)

## 🧠 Come funziona

1. Premi il pulsante con l'icona del file audio per aprire il selettore di file.
2. Scegli un messaggio vocale WhatsApp salvato sul tuo dispositivo.
3. Premi il pulsante Play per ascoltarlo.
4. (Facoltativo) Cambia la velocità di riproduzione con il pulsante `x1.0` / `x2.0`.

> ⚠️ **Nota**: L'audio deve essere già presente sul dispositivo. L'app non accede direttamente ai file di WhatsApp, ma puoi usare un file manager per copiarli da: /WhatsApp/Media/WhatsApp Voice Notes/

## 📦 Dipendenze

- [`file_picker`](https://pub.dev/packages/file_picker)
- [`audioplayers`](https://pub.dev/packages/audioplayers)
- `flutter/material.dart`

## 🛠️ Installazione

1. Clona il repository o scarica i file.
2. Esegui il comando:

```bash
flutter pub get
flutter run
```
> ⚠️ **Nota**: Questa app è a scopo educativo e personale. Non violare la privacy altrui. Utilizza l'app responsabilmente e legalmente secondo le leggi del tuo paese.
