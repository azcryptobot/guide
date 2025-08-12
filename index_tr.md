---
layout: default
title: Bot Starter Guide - Türkçe
---

[🇻🇳 Tiếng Việt](index_vi.md) | [🇬🇧 English](index.md) | [🇩🇪 Deutsch](index_de.md) | [🇷🇺 Русский](index_ru.md) | [🇹🇷 Türkçe](index_tr.md) | [🇮🇳 हिन्दी](index_hi.md) | [🇪🇸 Español](index_es.md) | [🇨🇳 中文](index_zh.md) | [🇮🇩 Bahasa Indonesia](index_id.md) | [🇦🇪 العربية](index_ae.md)

# 🚀 Bot Başlangıç Kılavuzu

Hoş geldiniz! Bu bot size **kripto fiyatlarını takip etme 📊, piyasaları analiz etme 📈, alarm kurma 🔔 ve daha fazlasını 🎯** — hepsini Telegram 💬 içinde yapma imkânı verir.  
Komutlar kısa ve esnektir. Sadece `/komut` yazın veya parametre ekleyin.  

<hr>

## 📌 1. Temel Fiyat Kontrolleri 💰

Komut | Örnek | Açıklama
---|---|---
**/p** | `/p btc eth` | Hızlı fiyat al ⚡. `-4Y` ekleyerek geçmişi görüntüle ⏳.
**/pl** | `/pl` | Kaydedilmiş fiyat listesini göster 💾.
**/pp** | `/pp bnb xrp` | Detaylı fiyat 🔍.
**/pa** | `/pa` | Tüm ana çiftlerin fiyatı 🌍.
**/pf** | `/pf eth` | Vadeli işlem fiyatı 📉.
**/ppf** | `/ppf eth` | Vadeli işlem detay fiyatı 📄.
**/ps** | `/ps VNM` | Vietnam hisse fiyatı 🇻🇳.
**/psw** | `/psw MSFT` | ABD hisse fiyatı 🇺🇸.

<hr>

## 📌 2. İzleme Listeleri ve Uyarılar 👀

Komut | Örnek | Açıklama
---|---|---
**/wt** | `/wt btc 10` | Token’ı miktarıyla izle 👁️.
**/custom** | `/custom btc` | İzleme listesi için özel sinyaller 🎯.
**/notif** | `/notif btc 30000` | Fiyat hedefe ulaşınca uyar 🚨.
**/alarm** | `/alarm 30m wake up` | Genel alarm/zamanlayıcı ⏰.

<hr>

## 📌 3. Ticaret Araçları 📈

Komut | Örnek | Açıklama
---|---|---
**/buy** | `/buy btc 20000` | Bu fiyattan alınca kâr/zarar 💹.
**/sell** | `/sell btc 50000` | Bu fiyattan satınca kâr/zarar 💸.
**/tp** | `/tp ada` | Fibonacci’ye göre TP & DCA 🎯.
**/rsi** | `/rsi btc` | RSI göstergesi 📊.
**/macd** | `/macd eth` | MACD verisi 📶.
**/fib** | `/fib ETH 180` | X günlük Fibonacci fiyatları 🔢.
**/lsratio** | `/lsratio btc` | Long/Short oranı ⚖️.
**/oi** | `/oi btc` | Açık pozisyon 📜.
**/fdr** | `/fdr btc` | Fonlama oranı 💵.

<hr>

## 📌 4. Piyasa Analizi 🌎

Komut | Örnek | Açıklama
---|---|---
**/trending** | `/trending` | Popüler aramalar (CoinGecko) 📈.
**/tpp** | `/tpp 30` | 24 saatte en çok yükselen 🚀.
**/tdd** | `/tdd 20` | 24 saatte en çok düşen 📉.
**/topvol** | `/tvv` | En yüksek hacimli coinler 🏆.
**/market** | `/market` | Binance pump/dump analizi 🔄.
**/dom** | `/dom d1` | Bitcoin dominansı 👑.
**/total** | `/total h4` | Toplam piyasa değeri 🏬.
**/etf** | `/etf` | Bitcoin ETF verileri 📑.

<hr>

## 📌 5. Grafikler 📊

Komut | Örnek | Açıklama
---|---|---
**/ch** | `/ch btc h1` | Binance/MEXC/Gate grafiği 📈.
**/cc** | `/cc bnb h4` | Binance grafiği (eski) 📉.
**/cf** | `/cf eth h1` | Vadeli işlem grafiği 💯.
**/ccc** | `/ccc btc` | CoinGecko grafiği 🌐.
**/ideas** | `/ideas bnb` | TradingView fikirleri 💡.

<hr>

## 📌 6. Araçlar ve Eğlence 🎉

Komut | Örnek | Açıklama
---|---|---
**/calc** | `/calc 1+2*3` | Hesap makinesi ➗.
**/translate** | `/trans vi hello` | Metin çevir 🌍.
**/gif** | `/gif haha` | Rastgele gif 😂.
**/emoj** | `/emoj smile` | Rastgele emoji 😁.
**/fun** | `/fun` | Kripto mizahı 🤣.
**/wallpaper** | `/wallpaper` | Rastgele duvar kağıdı 🖼️.
**/music** | `/music faded` | SoundCloud müzik indir 🎵.
**/youtube** | `/youtube song name` | YouTube video indir ▶️.

<hr>

## 📌 7. Bilgi ℹ️

Komut | Örnek | Açıklama
---|---|---
**/info** | `/info bnb` | Coin bilgisi (CoinMarketCap) 🗒️.
**/desc** | `/desc btc` | Coin açıklaması 📄.
**/alinks** | `/alinks btc` | İlgili bağlantılar 🔗.
**/contracts** | `/contracts chess` | Token sözleşme adresleri 📜.
**/events** | `/events 7` | Yaklaşan etkinlikler 📅.
**/updates** | `/updates ARB` | Proje güncellemeleri 📰.
**/fgi** | `/fgi` | Korku & Açgözlülük endeksi 😱.

<hr>

✅ **İpucu:** `/help` veya `/commands` yazarak tüm komutları görebilirsiniz.  
🔥 Önce `/p btc eth` deneyin, anında canlı fiyat görün! ⚡
