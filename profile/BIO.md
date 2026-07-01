# GitHub Profil Alanları — Kopyala Yapıştır

GitHub → **Settings** → **Profile** veya profil sayfasında **Edit profile**

---

## Bio (Background) — max 160 karakter

GitHub bio alanı **160 karakter** sınırı var. Aşağıdan birini seç.

### Önerilen (İngilizce — global işverenler için)

```
Computer Engineering @ MCÜ · Software Developer @ OverBlock · 40K+ users in production · Platform/SRE path · Java · Python · Docker
```

*(159 karakter)*

### Alternatif 1 — Web3 ağırlıklı

```
Software Developer · Production Web3 & backend (40K+ users) · npm author · CENG @ MCÜ · Java · Python · TypeScript · Docker
```

### Alternatif 2 — Platform/SRE odaklı

```
CENG student → Platform/SRE · Production systems (40K+ users) · Linux · Docker · observability · Java · Python · Izmir
```

### Alternatif 3 — Kısa ve net

```
Building production systems · Web3 & backend · learning Platform/SRE · Java · Python · Docker · Open to internships
```

### Türkçe (LinkedIn veya kişisel kullanım; GitHub’da İngilizce önerilir)

```
Bilgisayar Mühendisliği @ MCÜ · Yazılım Geliştirici @ OverBlock · 40K+ kullanıcılı prod sistemler · Platform/SRE yolunda
```

---

## Diğer profil alanları

| Alan | Önerilen değer |
|------|----------------|
| **Name** | Cem Ayyıldız |
| **Company** | OverBlock |
| **Location** | Izmir, Turkey |
| **Website** | https://cemayyildiz.github.io/ |
| **Social** | https://www.linkedin.com/in/ayyildizcem/ |

**Twitter/X** (istersen): `https://x.com/lykanbtc`

---

## Repoların — hangisi ne?

| Repo | Ne işe yarar |
|------|----------------|
| **[CemAyyildiz.github.io](https://github.com/CemAyyildiz/CemAyyildiz.github.io)** | Ana portföy — `index.html` + `README.md` burada |
| **[CV](https://github.com/CemAyyildiz/CV)** | Eski / ayrı CV sitesi (Vercel) — ana portföy değil |
| **CemAyyildiz** *(yok)* | Sadece `github.com/CemAyyildiz` profil sayfasında README göstermek için (opsiyonel) |

**Senin ana repon:** `CemAyyildiz.github.io` → README’yi oraya push et.

---

## Pin'lenecek 6 repo (öneri)

Profil sayfasında **Customize your pins**:

1. `CemAyyildiz.github.io` — portföy (ana)
2. `mantle-402` — npm
3. `bountylane` — AI
4. `WriteBlock` — blockchain
5. `order-system` — full-stack
6. `TelegramBot` veya `MovieManegament`

`CV` pin’leme — `github.io` zaten portföy.

---

## Opsiyonel: profil ana sayfasında README

`github.com/CemAyyildiz` açılınca büyük README istiyorsan → ayrı repo **`CemAyyildiz/CemAyyildiz`** oluşturman gerekir. Detay: [SETUP.md](SETUP.md)

---

## Bio güncelleme (terminal — gh CLI)

`gh` kurulu ve login ise:

```bash
gh api -X PATCH user -f bio='Computer Engineering @ MCÜ · Software Developer @ OverBlock · 40K+ users in production · Platform/SRE path · Java · Python · Docker'
gh api -X PATCH user -f company='OverBlock'
gh api -X PATCH user -f location='Izmir, Turkey'
gh api -X PATCH user -f blog='https://cemayyildiz.github.io/'
```

---

## Eski bio (değiştirilecek)

```
Computer Engineer with a passion for Web3, Blockchain, and Software Development. Experienced in SQL, Java, OOP, and Data Structures.
```

**Sorun:** Güncel deneyimi (OverBlock, 40K users, npm, Platform yönü) yansıtmıyor. Yukarıdaki önerilen bio ile değiştir.
