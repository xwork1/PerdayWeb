# PerdayWeb

Perday alışkanlık takip uygulamasının web sitesi — **statik HTML**, build
adımı yok. Coolify'da "Static" build pack ile `perday.appouse.dev` üzerinde
yayınlanır.

## Yapı

| Yol | İçerik |
|-----|--------|
| `/` | Landing (TR) — `/en/` İngilizce |
| `/privacy/` | Gizlilik Politikası (store zorunlu) |
| `/terms/` | Kullanım Koşulları |
| `/account-deletion/` | Hesap silme adımları (Play Console zorunlu) |
| `/support/` | Destek + SSS (App Store zorunlu) |
| `assets/` | style.css + logo |

Marka: dark `#11161F`, gold `#F4B82A`, orange `#FB7A3C`. Tipografi:
Archivo (display) + Inter (gövde) + JetBrains Mono (sayaç/etiket).
İmza öğesi: hero'daki animasyonlu çentik (tally) panosu.

## Güncelleme

Sayfalar saf HTML — düzenle, commit'le, push'la; Coolify otomatik yayınlar.
Legal metinlerde değişiklikte sayfadaki "Son güncelleme" tarihini de değiştir.

Ayrıntılı spec: `notch` repo → `document/PERDAY_WEBSITE_SPEC.md`
