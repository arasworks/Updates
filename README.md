# ArasWorks güncellemeleri

Bu depo ArasWorks uygulamalarının yayınlanmış sürümlerini barındırır.
Uygulamalar **Ayarlar → Güncellemeleri denetle** ile buradan yeni sürüm olup olmadığına bakar
ve yeni sürümü buradaki **Releases** bölümünden indirir.

Kaynak kodu burada değildir; dosyalar her yeni sürümde otomatik olarak buraya yüklenir.

| Uygulama | Platform | Bilgi dosyası |
|---|---|---|
| Astra | Android | [`astra/android.json`](astra/android.json) |
| Astra | Windows | [`astra/windows.json`](astra/windows.json) |

## Bilgi dosyası biçimi

```json
{
  "app": "Astra",
  "platform": "android",
  "version": "1.0.4",
  "versionCode": 12,
  "url": "https://github.com/arasworks/Updates/releases/download/astra-android-v1.0.4/Astra.apk",
  "sha256": "…",
  "size": 12345678,
  "notes": "Bu sürümdeki değişiklikler",
  "date": "2026-11-20T14:00:00Z"
}
```

Sürüm etiketleri: `<uygulama>-<platform>-v<sürüm>` (ör. `astra-android-v1.0.4`, `astra-windows-v1.0.2`).

© 2026 ArasWorks
