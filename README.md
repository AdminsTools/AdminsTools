<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/wordmark-dark.png"><img src="assets/wordmark-light.png" width="420" alt="AdminsTools"></picture></p>

<p align="center"><b>Türkçe</b> &nbsp;·&nbsp; <a href="docs/en/README.md">English</a> &nbsp;·&nbsp; <a href="docs/de/README.md">Deutsch</a> &nbsp;·&nbsp; <a href="docs/ru/README.md">Русский</a> &nbsp;·&nbsp; <a href="docs/zh/README.md">中文</a></p>

<p align="center">Ağ ve sistem yöneticisinin tek pencerelik araç çantası: keşif, yol ve hız, DNS, web, posta, uzaktan yönetim — kurulum, sürücü ve hesap gerektirmeden.</p>

<p align="center">✓ Tek dosya, kurulum yok &nbsp;·&nbsp; ✓ Yönetici hakkı gerekmez &nbsp;·&nbsp; ✓ Windows · macOS · Linux &nbsp;·&nbsp; ✓ Veriler bilgisayarda kalır</p>

## Ekran görüntüleri

### Keşif

#### Ping taraması

Bir /24 tek turda: gecikme, ARP, kayıp, ad ve MAC üreticisi; tek adrese 5 ping ya da sürekli.

![Ping taraması](assets/screens/tr/ping.svg)

#### Port tarama

Hazır profiller, servis karşılamaları, UDP sondaları; riskli portlar işaretli.

![Port tarama](assets/screens/tr/port.svg)

#### IP kimliği

"Bu IP ne?" Ping, portlar, SNMP, web ve MAC birleşip gerekçeli, puanlı tahmin.

![IP kimliği](assets/screens/tr/ident.svg)

#### MAC üretici

Her biçimde MAC → üretici; IP yazılırsa MAC bulunur. Sanal ve yerel adresler işaretli.

![MAC üretici](assets/screens/tr/mac.svg)

#### Komşuluk (LLDP/CDP)

Switch'ten switch'e keşif; port adları, LAG, yedi yerleşim, SVG / PNG / PDF.

![Komşuluk (LLDP/CDP)](assets/screens/tr/nbr.svg)

### Yol ve hız

#### Traceroute / MTR

Ağ şeritleri, her atlamada kayıp ve gecikme, dünya haritası.

![Traceroute / MTR](assets/screens/tr/trace.svg)

#### Hız testi

İnternete ya da kendi sunucunuza indirme / yükleme ölçümü.

![Hız testi](assets/screens/tr/speed.svg)

#### Wi-Fi

Sinyal ölçer, kanal görünümü ve kapsama haritası.

![Wi-Fi](assets/screens/tr/wifi.svg)

#### Dosya indirici

Paralel bağlantılı hızlı indirme, doğrudan İndirilenler klasörüne; SHA-256 doğrulama.

![Dosya indirici](assets/screens/tr/download.svg)

#### MTU bulma

Parçalanmadan geçen en büyük paket; kara delik tespiti.

![MTU bulma](assets/screens/tr/mtu.svg)

### DNS ve adres

#### DNS sorgu

Kayıt türleri, birden çok sunucuyu yan yana karşılaştırma, DNSSEC, AXFR.

![DNS sorgu](assets/screens/tr/dns.svg)

#### Whois

RDAP ve klasik whois: kayıt şirketi, kişiler, AS, konum, ham kayıt.

![Whois](assets/screens/tr/whois.svg)

#### Genel IP'm

Genel adres, servis sağlayıcı ve DNS yönlendirmesinin tespiti.

![Genel IP'm](assets/screens/tr/myip.svg)

### Web

#### HTTP/HTTPS özeti

Durum kodu, yönlendirme, güvenlik başlıkları ve ürün tahmini.

![HTTP/HTTPS özeti](assets/screens/tr/http.svg)

#### HTTP istek (curl)

DNS, TCP, TLS, ilk bayt ayrı ayrı; JavaScript ile çalışan sayfalar da.

![HTTP istek (curl)](assets/screens/tr/curl.svg)

#### API istemcisi

Postman gibi, ama sade: koleksiyonlar, değişkenler, kimlik.

![API istemcisi](assets/screens/tr/api.svg)

#### Sertifika

Zincir, bitiş tarihi, güven ve TLS sürümleri.

![Sertifika](assets/screens/tr/cert.svg)

#### SSL denetimi

SSL Labs ölçütlerine yakın A+ … F notu ve nedenleri.

![SSL denetimi](assets/screens/tr/ssl.svg)

### Yönetim

#### Toplu işlem

SSH / WinRM ile yüzlerce makinede komut; şablonlar, birden çok kimlik.

![Toplu işlem](assets/screens/tr/exec.svg)

#### Mail

SMTP, MX + SPF / DMARC, IMAP / POP3, deneme iletisi ve relay testi.

![Mail](assets/screens/tr/mail.svg)

#### SNMP

Walk / get, v1–v3; yayın kipinde bilgisayar bir SNMP cihazı gibi yanıt verir.

![SNMP](assets/screens/tr/snmp.svg)

#### Syslog

İleti gönder ya da sunucu olup gelenleri dinle.

![Syslog](assets/screens/tr/syslog.svg)

#### Port mesaj / dinle

TCP / UDP portuna mesaj gönder, yanıtı ya da gelenleri izle.

![Port mesaj / dinle](assets/screens/tr/send.svg)

#### Paket yakalama

Npcap'siz hafif yakalama, protokol özeti ve pcap kaydı.

![Paket yakalama](assets/screens/tr/capture.svg)

#### Wake-on-LAN

Sihirli paketle uyandır, açılmasını ping ile izle.

![Wake-on-LAN](assets/screens/tr/wol.svg)

### Hesap ve bilgi

#### Alt ağ hesap

Ağ, yayın, kullanılabilir aralık, maske ve bölme.

![Alt ağ hesap](assets/screens/tr/subnet.svg)

#### Bu bilgisayar

Arayüzler, adresler, ağ geçidi, DNS ve VPN.

![Bu bilgisayar](assets/screens/tr/local.svg)

## Neden AdminsTools

- **Hızlı, ama bilgisayarı kasmaz** — Pingler düzenli akışla gider: anahtarlama cihazları yorulmaz, yanıt kaybolmaz. Program düşük öncelikte ve birkaç çekirdekle çalışır.
- **Güçlü süzgeç** — Hazır düğmeler, sayılı değer listeleri, aralıklar ve kısa arama dili: `vendor:hp rtt>20 -down`. Satırlar yerinden oynamaz.
- **Sonuç geçmişi ve dışa aktarma** — Her çalıştırma saklanır, adıyla kaydedilir. Excel, CSV, pcap, SVG / PNG / PDF; dosyalar doğrudan İndirilenler'e.
- **Şifre kasası** — SSH, WinRM, SNMP v3 ve mail şifreleri Argon2id + AES-GCM ile şifreli kasada; ayar ve sonuç dosyalarına yazılmaz.
- **Veri bilgisayarınızda** — Hesap, bulut, telemetri yok. Arayüz yalnızca 127.0.0.1'de ve oturum anahtarıyla açılır.
- **5 dil, 9 tema** — Türkçe, English, Deutsch, Русский, 中文. Açık ve koyu temalar; sütun genişlikleri ve görünümler hatırlanır.

## İndir

Sürüm 2.20.0 · Tek dosya: indirin ve çalıştırın. Ayarlar tek bir dosyada; exe'nin yanına `PowerAdminTool.json` koyarsanız USB bellekten taşınabilir çalışır.

**Windows** — `AdminsTools-2.20.0.exe · ~16 MB`

- Windows 10 / 11, 64 bit
- Kurulum ve yönetici hakkı gerekmez
- Ping ve traceroute sürücü istemez

**macOS** — `AdminsTools-2.20.0-macos-arm64.zip · -macos-amd64.zip`

- Apple Silicon (M1 ve sonrası) ya da Intel
- İmzasız: ilk açılışta sağ tık › Aç
- Paket yakalama macOS'ta yok

**Linux** — `adminstools-2.20.0-linux-amd64 · ~15 MB`

- x86-64, tek ikili dosya
- `-listen 0.0.0.0:8090` ile atlama sunucusunda tarayıcıdan
- Ping için `ping_group_range` ya da `cap_net_raw`

---

© 2026 Mehmet Göğebakan
