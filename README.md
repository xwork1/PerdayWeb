# PerdayWeb

Perday alışkanlık takip uygulamasının web sitesi — **statik HTML**, build
adımı yok. Coolify'da "Static" build pack ile `perday.appouse.dev` üzerinde
yayınlanır.

## Yapı

| Yol | İçerik |
|-----|--------|
| `/` | Landing (EN, varsayılan) — `/tr/` Türkçe |
| `/privacy/` | Privacy Policy (store zorunlu) — TR: `/tr/privacy/` |
| `/terms/` | Terms of Use — TR: `/tr/terms/` |
| `/account-deletion/` | Hesap silme adımları (Play Console zorunlu) — TR: `/tr/account-deletion/` |
| `/support/` | Destek + SSS (App Store zorunlu) — TR: `/tr/support/` |
| `/en/*` | Eski EN yollarından köke meta-refresh yönlendirmeleri (silme) |
| `assets/` | style.css + logo |

Marka: dark `#11161F`, gold `#F4B82A`, orange `#FB7A3C`. Tipografi:
Archivo (display) + Inter (gövde) + JetBrains Mono (sayaç/etiket).
İmza öğesi: hero'daki animasyonlu çentik (tally) panosu.

## Güncelleme

Sayfalar saf HTML — düzenle, commit'le, push'la; Coolify otomatik yayınlar.
Legal metinlerde değişiklikte sayfadaki "Son güncelleme" tarihini de değiştir.

Ayrıntılı spec: `notch` repo → `document/PERDAY_WEBSITE_SPEC.md`
