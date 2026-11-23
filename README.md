<div align="center">

<img src="docs/01-kapak.png" alt="Gerçek Zamanlı Etkinlik Takibi — Enes Öztürk imzalı proje" width="100%">

# Gerçek Zamanlı Etkinlik Takibi

**Ödev 5 — WebSocket üzerinden canlı akış, katılımcı yönetimi ve çift ekran test simülatörü içeren etkinlik sistemi.**

[![WebSocket](https://img.shields.io/badge/WebSocket-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/gercek-zamanli-etkinlik)
[![Express](https://img.shields.io/badge/Express-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/gercek-zamanli-etkinlik)
[![React](https://img.shields.io/badge/React-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/gercek-zamanli-etkinlik)
[![Realtime](https://img.shields.io/badge/Realtime-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/gercek-zamanli-etkinlik)
[![Doğrulama](https://img.shields.io/badge/Do%C4%9Frulama-lint%20%2B%20build%20ge%C3%A7ti-2EA043?style=for-the-badge)](https://github.com/EnesBinMalik/gercek-zamanli-etkinlik)
[![Enes Öztürk](https://img.shields.io/badge/Enes%20%C3%96zt%C3%BCrk-imzal%C4%B1-EA4338?style=for-the-badge&logo=badge&logoColor=white)](https://github.com/EnesBinMalik)

<img src="docs/rozet-enes-ozturk.png" alt="Enes Öztürk imzalı tasarım rozeti" width="420">

</div>

---

## Hakkında

Bu sistem, etkinliklerde yapılan değişikliklerin tüm bağlı istemcilere anında iletilmesini sağlar. Express + `ws` ile kurulan sunucu, yeni etkinlik ve katılımcı olaylarını yayınlar; arayüzdeki canlı akış paneli ve çift ekran simülatörü gerçek zamanlı davranışı görsel olarak doğrular.

> Bu proje **Enes Öztürk** tarafından tasarlanmış, geliştirilmiş ve imzalanmıştır.

---

## Öne çıkan özellikler

| Özellik | Açıklama |
| --- | --- |
| **WebSocket sunucusu** | Anlık olay yayını ve otomatik yeniden bağlanma. |
| **Canlı akış paneli** | Tüm istemci olaylarını zaman damgasıyla listeler. |
| **Çift ekran test** | İki ayrı istemciyi yan yana simüle eder. |
| **1-tıkla test** | Hazır canlı etkinlik ile senaryoyu başlatır. |
| **Katılımcı yönetimi** | Etkinliğe katılım ve katılımcı listesi. |
| **Kategori filtreleri** | Yazılım, yapay zekâ, tasarım, girişimcilik. |

---

## Canlı sistem

| Ölçü | Değer |
| --- | --- |
| Protokol | WebSocket |
| İstemci | Çoklu |
| Mod | Çift ekran |
| Test | 1 tık |

---

## Galeri

<img src="docs/02-ekran.png" alt="Gerçek Zamanlı Etkinlik Takibi ana ekran" width="100%">

<img src="docs/03-ekran.png" alt="Gerçek Zamanlı Etkinlik Takibi etkileşimli görünüm" width="100%">

<img src="docs/04-ekran.png" alt="Gerçek Zamanlı Etkinlik Takibi detay görünümü" width="100%">

---

## Kurulum

**Gereksinim:** Node.js 20+

```bash
git clone https://github.com/EnesBinMalik/gercek-zamanli-etkinlik.git
cd gercek-zamanli-etkinlik
npm install
npm run start
```

> Sunucu ve istemci aynı süreçte başlatılır; ek kurulum gerekmez.

Diğer komutlar:

```bash
npm run build     # Üretim derlemesi
npm run preview   # Derlemeyi önizle
npm run lint      # TypeScript tip kontrolü
```

---

## Teknik mimari

```text
server.ts                    WebSocket + REST sunucusu
src/context/RealtimeContext.tsx  Bağlantı ve olay durumu
src/components/SplitScreenSimulator.tsx  Çift ekran test
src/components/LiveActivityDrawer.tsx    Canlı akış
src/components/CreateEventModal.tsx      Etkinlik oluşturma
```

---

## İmza

<div align="center">

[![Geliştirici](https://img.shields.io/badge/Geli%C5%9Ftirici-Enes%20%C3%96zt%C3%BCrk-EA4338?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik)
[![İmza](https://img.shields.io/badge/%C4%B0mza-Enes%20%C3%96zt%C3%BCrk-FFD700?style=for-the-badge&logo=verified&logoColor=white)](https://github.com/EnesBinMalik)

**Bu kod, tasarım ve deneyim Enes Öztürk'ün kişisel imzasını taşır.**

© 2026 Enes Öztürk — Tüm hakları saklıdır.

</div>
