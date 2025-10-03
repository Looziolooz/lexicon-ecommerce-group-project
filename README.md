# 🏪 E-handelsplattform i Next.js

En modern, responsiv e-handelsplattform utvecklad som grupprojekt i Lexicon Frontend Development 2025.

---

## 📦 Innehållsförteckning

- [Om projektet](#-om-projektet)
- [Funktioner](#-funktioner)
- [Teknologier](#-teknologier)
- [Installation](#%EF%B8%8F-installation)
- [Användning](#-användning)
- [Projektstruktur](#-projektstruktur)
- [Arbetsflöde](#-arbetsflöde)
- [Sprintplan](#-sprintplan)
- [API Integration](#-api-integration)
- [Bidra](#-bidra)
- [Lärdomar](#-lärdomar)
- [Team](#-team)
- [Licens](#%EF%B8%8F-licens)
- [Kontakt](#-kontakt)

---

## 📖 Om projektet

Detta är ett grupprojekt i kursen **Lexicon Frontend Development 2025** där målet var att skapa en fullständig e-handelsplattform med moderna webbteknologier.

Plattformen visar produkter från ett externt API ([DummyJSON](https://dummyjson.com/)), är fullt responsiv och innehåller interaktiva funktioner som produktfiltrering, dynamisk routing och administratörspanel. Projektet gav praktisk erfarenhet av att arbeta med Next.js 15 App Router, Server och Client Components, samt agilt teamarbete med SCRUM-metodik.

### Design och Attribution

Designen är baserad på och anpassad från [SHOP.CO - eCommerce Website Template](https://www.figma.com/community/file/1273571982885059508) av Muhammad Bilal Akbar på Figma Community. Vi har:
- Använt layoutstrukturen som grund
- Anpassat färgschema och typografi
- Modifierat komponenter för våra specifika behov
- Lagt till egna funktioner och sektioner
- Använt vissa produktbilder och grafiska element från originalmallen

**Original Design Credit:** [SHOP.CO by Muhammad Bilal Akbar](https://www.figma.com/community/file/1273571982885059508)

**Utbildning**: Lexicon Frontend Development 2025  
**Projekttyp**: Grupparbete (4 personer)  
**Tidsram**: 4 sprintar (4 veckor)

---

## 🗹 Funktioner

### Användarfunktioner
- ✅ **Startsida** med hero-sektion och utvalda produkter
- ✅ **Produktkatalog** med responsiv grid-layout
- ✅ **Produktfiltrering** med kategorier och underkategorier
- ✅ **Produktdetaljer** med dynamisk routing
- ✅ **Sökfunktionalitet** för produkter
- ✅ **Om oss-sida** med företagsinformation
- ✅ **Kontaktsida** med formulär

### Administratörsfunktioner
- ✅ **Admin-panel** för produkthantering
- ✅ **Skapa produkter** via formulär
- ✅ **Redigera produkter** med förifyllda fält
- ✅ **Ta bort produkter** med bekräftelse
- ✅ **Produktlista** i adminvy

### Tekniska funktioner
- ✅ Server Components för optimal prestanda
- ✅ Client Components för interaktivitet
- ✅ Dynamisk metadata för SEO
- ✅ Responsiv design för alla enheter
- ✅ Tillgänglighetsoptimering (WAVE-testad)
- ✅ TypeScript för typsäkerhet
- ✅ Error boundaries och felhantering

---

## ✨ Teknologier

### Ramverk & Bibliotek
- **[Next.js 15](https://nextjs.org/)** - React-ramverk med App Router, server-side rendering (SSR), statisk generering (SSG) och optimering för SEO och prestanda
- **[React 18+](https://react.dev/)** - JavaScript-bibliotek för att bygga interaktiva och återanvändbara användargränssnitt med komponenter och Virtual DOM
- **[TypeScript 5.0](https://www.typescriptlang.org/)** - Typsäker JavaScript för bättre kodkvalitet och utvecklarupplevelse
- **[Tailwind CSS 3.4](https://tailwindcss.com/)** - Utility-first CSS-ramverk för snabb och responsiv design med fördefinierade klasser

### UI Components & Icons
- **[Shadcn/ui](https://ui.shadcn.com/)** - Samling anpassningsbara och tillgängliga React-komponenter och stylade med Tailwind CSS
- **[Lucide React](https://lucide.dev/)** - Öppen källkod-bibliotek med enkla, skalbara ikoner optimerade för React och Next.js
- **[Sonner](https://sonner.emilkowal.ski/)** - Toast notifications library för använderfeedback

### Verktyg & Kvalitetssäkring
- **[ESLint](https://eslint.org/)** - Linting för kodkvalitet
- **[Git](https://git-scm.com/)** - Versionshantering
- **[GitHub](https://github.com/)** - Kod-hosting och samarbete
- **[WAVE](https://wave.webaim.org/)** - Web Accessibility Evaluation Tool för tillgänglighetstestning enligt WCAG-riktlinjer

### Projekthantering
- **[Figma](https://figma.com/)** - Design och prototyper
- **[Trello](https://trello.com/)** - Kanban-board för sprint planning
- **[Miro](https://miro.com/)** - Retrospektiv och brainstorming
- **[Slack](https://slack.com/)** - Teamkommunikation

### Externa API:er
- **[DummyJSON](https://dummyjson.com/)** - REST API för produktdata med CRUD-stöd

### Hosting & Deployment
- **[Vercel](https://vercel.com/)** - Deployment platform 

---

## 🛠️ Installation

### Förutsättningar
```bash
Node.js >= 18.x
npm >= 9.x eller yarn >= 1.22.x
Git >= 2.x
```

### Steg-för-steg

1. **Klona repository**
```bash
git clone https://github.com/BlackestDawn/lexicon-ecommerce-groupproject.git
cd lexicon-ecommerce-groupproject
```

2. **Installera beroenden**
```bash
npm install
```
eller med yarn:
```bash
yarn install
```

3. **Starta utvecklingsserver**
```bash
npm run dev
```
eller:
```bash
yarn dev
```

4. **Öppna i webbläsare**
```
http://localhost:3000
```

### Bygga för produktion

```bash
# Skapa optimerad build
npm run build

# Starta produktionsserver
npm start
```

### Kodkvalitet

```bash
# Kör ESLint
npm run lint
```

---

## 🚀 Användning

### Navigation

| Sida | URL | Beskrivning |
|------|-----|-------------|
| **Startsida** | `/` | Hero-sektion, utvalda produkter, kategorier |
| **Produkter** | `/products` | Alla produkter med filtrering |
| **Produktdetalj** | `/products/[id]` | Detaljerad produktinformation |
| **Om oss** | `/about` | Information om företaget |
| **Kontakt** | `/contact` | Kontaktformulär och information |
| **Admin** | `/admin` | Översikt för administratörer |
| **Produkthantering** | `/admin/products` | Lista och hantera produkter |
| **Lägg till produkt** | `/admin/products/add-product` | Skapa ny produkt |
| **Redigera produkt** | `/admin/products/[id]` | Redigera befintlig produkt |

### Produktfiltrering

Använd sidomenyn på `/products` för att filtrera efter:
- **Alla produkter**
- **Herr** - Skjortor, Skor, Klockor
- **Dam** - Klänningar, Skor, Väskor, Smycken, Klockor
- **Accessoarer** - Solglasögon, Klockor, Smycken, Väskor

### Admin-funktioner

1. Navigera till `/admin`
2. Välj "Products" för att hantera produkter
3. Använd "Add Product" för att skapa nya produkter
4. Klicka på en produkt för att redigera eller ta bort

---

## 🧱 Projektstruktur

```
lexicon-ecommerce-groupproject/
│
├── src/
│   ├── app/                           # Next.js App Router
│   │   ├── page.tsx                  # Startsida
│   │   ├── layout.tsx                # Root layout
│   │   ├── globals.css               # Globala styles
│   │   │
│   │   ├── about/
│   │   │   └── page.tsx              # Om oss-sida
│   │   │
│   │   ├── contact/
│   │   │   └── page.tsx              # Kontaktsida med formulär
│   │   │
│   │   ├── products/
│   │   │   ├── page.tsx              # Produktlista med filter
│   │   │   └── [id]/
│   │   │       └── page.tsx          # Dynamisk produktdetalj
│   │   │
│   │   └── admin/
│   │       ├── page.tsx              # Admin-översikt
│   │       ├── components/           # Admin-komponenter
│   │       ├── lib/                  # Admin actions
│   │       └── products/
│   │           ├── page.tsx          # Admin produktlista
│   │           ├── add-product/
│   │           │   └── page.tsx      # Skapa produkt
│   │           └── [id]/
│   │               └── page.tsx      # Redigera produkt
│   │
│   ├── components/                    # Återanvändbara komponenter
│   │   ├── Header.tsx                # Navigation header
│   │   ├── Footer.tsx                # Footer
│   │   ├── Navbar.tsx                # Navigationsmeny
│   │   ├── Hero.tsx                  # Hero-sektion
│   │   ├── FilterProducts.tsx        # Produktfilter
│   │   ├── FeaturedProducts.tsx      # Utvalda produkter
│   │   ├── CategorySection.tsx       # Kategorisektioner
│   │   └── Newsletter.tsx            # Nyhetsbrev
│   │
│   ├── data/                          # Datahantering
│   │   ├── products.ts               # API-funktioner
│   │   └── consts.ts                 # Konstanter
│   │
│   ├── hooks/                         # Custom React hooks
│   │
│   └── lib/                           # Utilities
│       └── interfaces.ts             # TypeScript interfaces
│
├── public/                            # Statiska filer
│   ├── hero-image.jpg
│   └── ...
│
├── .eslintrc.json                     # ESLint config
├── .gitignore                         # Git ignore
├── next.config.js                     # Next.js config
├── package.json                       # Dependencies
├── tailwind.config.ts                 # Tailwind config
├── tsconfig.json                      # TypeScript config
└── README.md                          # Dokumentation
```

---

## 📝 Arbetsflöde

### Agil utveckling med SCRUM

**Dagliga aktiviteter:**
- 🌅 Dagliga standup-möten (15 min)
- 💬 Slack för löpande kommunikation
- 📋 Trello för uppgiftshantering

**Sprint-struktur:**
- 📅 2 veckors sprintar
- 🎯 Sprint planning vid start
- 📊 Sprint review vid slut
- 🔄 Sprint retrospective med Miro

**Utvecklingsprocess:**
1. Välj uppgift från backlog
2. Skapa feature-branch från `main`
3. Utveckla funktionalitet
4. Commit och push till GitHub
5. Skapa Pull Request
6. Code review av minst 1 teammedlem
7. Merge till `main` efter godkännande

**Branching-strategi:**
```
main (produktion)
├── feature/navbar
├── feature/product-filter
├── feature/admin-panel
└── bugfix/image-loading
```

**Git-konventioner:**
- `feature/` - Nya funktioner
- `bugfix/` - Buggfixar
- `refactor/` - Kodförbättringar
- `docs/` - Dokumentation

---

## 🔄 Sprintplan

### Sprint 1 - Grundläggande struktur (Vecka 1-2)
**Mål:** Sätta upp projektet och skapa grundstruktur

✅ **Genomfört:**
- Skapat Next.js-projekt med TypeScript
- Konfigurerat Tailwind CSS
- Designat i Figma
- Valt DummyJSON som API
- Skapat GitHub repository med branch protection
- Implementerat fetch-funktioner för produkter
- Byggt startsida med hero-sektion
- Skapat grundläggande Header och Footer
- Dokumenterat i README

**Lärdomar:**
- Next.js 15 App Router struktur
- TypeScript konfiguration
- API-integration grundläggande

---

### Sprint 2 - Dynamisk routing & Interaktion (Vecka 3-4)
**Mål:** Implementera produktvisning och filtrering

✅ **Genomfört:**
- Skapat produktkort-komponenter
- Implementerat dynamisk routing för produkter (`/products/[id]`)
- Byggt produktlista med responsiv grid
- Utvecklat FilterProducts-komponent
- Implementerat Server/Client Component pattern
- Lagt till CTA-knappar som länkar till produktsidan
- Skapat sidonavigering för kategorier
- Integrerat kategorifiltrering med URL-parametrar

**Lärdomar:**
- Dynamic routing i Next.js
- Server vs Client Components
- State management med URL params
- Responsiv design med Tailwind

---

### Sprint 3 - Admin & Produkthantering (Vecka 5-6)
**Mål:** Skapa admin-panel för CRUD-operationer

✅ **Genomfört:**
- Byggt admin-layout och navigation
- Skapat admin produktlista
- Implementerat "Lägg till produkt"-formulär
- Utvecklat "Redigera produkt"-funktionalitet
- Lagt till "Ta bort produkt" med bekräftelse
- Skapat dynamisk metadata för SEO
- Byggt kontaktsida med formulär
- Implementerat formulärvalidering
- Lagt till success/error meddelanden

**Lärdomar:**
- Form handling i Next.js
- Server Actions
- Data mutation
- Optimistic UI updates

---

### Sprint 4 - Slutförande & Optimering (Vecka 7-8)
**Mål:** Färdigställa, testa och dokumentera

✅ **Genomfört:**
- Merge av alla features till main
- Kodrefaktorering och cleanup
- Tillgänglighetstestning med WAVE
- Fixat accessibility-problem
- Optimerat bildladdning
- Implementerat error boundaries
- Uppdaterat README med komplett dokumentation
- Lagt till kommentarer i kod
- Performance-optimering
- Cross-browser testning
- Mobile responsiveness-test

**Lärdomar:**
- Web accessibility (WCAG)
- Performance optimization
- Error handling best practices
- Documentation importance

---

## 🔌 API Integration

### DummyJSON API

**Base URL:** `https://dummyjson.com/`

**Endpoints som används:**

| Endpoint | Metod | Beskrivning |
|----------|-------|-------------|
| `/products` | GET | Hämta alla produkter |
| `/products/category/{category}` | GET | Hämta produkter per kategori |
| `/products/{id}` | GET | Hämta specifik produkt |
| `/products/search?q={query}` | GET | Sök produkter |
| `/products/categories` | GET | Hämta alla kategorier |

**Kategorier:**
- Herr: `mens-shirts`, `mens-shoes`, `mens-watches`
- Dam: `womens-dresses`, `womens-shoes`, `womens-bags`, `womens-jewellery`, `womens-watches`
- Accessoarer: `sunglasses`

**Exempel request:**
```typescript
const response = await fetch('https://dummyjson.com/products/category/mens-shirts');
const data = await response.json();
```

---

## 🤝 Bidra

Vill du bidra till projektet?

### Steg för bidrag:

1. **Forka projektet**
```bash
git clone https://github.com/YOUR-USERNAME/lexicon-ecommerce-groupproject.git
```

2. **Skapa en feature-branch**
```bash
git checkout -b feature/amazing-feature
```

3. **Gör dina ändringar**
```bash
git add .
git commit -m "Add: Amazing feature"
```

4. **Push till din fork**
```bash
git push origin feature/amazing-feature
```

5. **Skapa en Pull Request**
- Gå till GitHub
- Klicka på "New Pull Request"
- Beskriv dina ändringar tydligt
- Vänta på code review

### Commit-konventioner:
- `Add:` Ny funktionalitet
- `Fix:` Buggfix
- `Update:` Uppdatering av befintlig kod
- `Refactor:` Kodförbättring utan funktionsändring
- `Docs:` Dokumentation
- `Style:` Formatering och stiländringar

### Code Review Process:
- Minst en teammedlem granskar PR
- Konstruktiv feedback och diskussion
- Godkännande krävs innan merge till main
- Branch protection aktiverad på main

### Design Attribution:
Om du använder grafiska element, vänligen respektera att designen är baserad på [SHOP.CO template](https://www.figma.com/community/file/1273571982885059508) av Muhammad Bilal Akbar.

---

## 👨‍🏫 Lärdomar

### Tekniska färdigheter

**Frontend:**
- ⚛️ Next.js 15 App Router och Server Components
- 📘 TypeScript för typsäker utveckling
- 🎨 Tailwind CSS för responsiv design
- 🔄 Async/await och Promise-hantering
- 🌐 RESTful API-integration
- 🧩 Komponentbaserad arkitektur
- 🎯 React Hooks (useState, useSearchParams, usePathname)
- 📱 Mobile-first responsive design
- ♿ Web Accessibility (WCAG)

**Verktyg & Processer:**
- 🔀 Git workflow och versionshantering
- 👥 Samarbete på GitHub med Pull Requests
- 📋 Agil utveckling med SCRUM
- 🎯 Sprint planning och backlog management
- 🔄 Code reviews och par-programmering
- 📊 Retrospektiv och kontinuerlig förbättring
- 🐛 Debugging och problemlösning

### Teamwork & Mjuka färdigheter

**Kommunikation:**
- Dagliga standup-möten
- Effektiv slack-kommunikation
- Tydlig dokumentation
- Konstruktiv feedback

**Samarbete:**
- Uppgiftsfördelning
- Ansvar för egna features
- Hjälpa teammedlemmar
- Dela kunskap och lösningar

**Problemlösning:**
- Analytiskt tänkande
- Kreativa lösningar
- Felsökning som team
- Anpassning till utmaningar

---

## 👥 Team

Detta projekt utvecklades av:

| Namn | GitHub | Fokusområden |
|------|--------|--------------|
| **Federico Barberi** | [@fdrcbrbr](https://github.com/fdrcbrbr) | Responsive Design, Testing |
| **Isabelle Wincrantz** | [@Discokatten](https://github.com/Discokatten) | UI/UX, Frontend Components |
| **Alexander Stauch** | [@BlackestDawn](https://github.com/BlackestDawn) | Project Lead, Backend Integration |
| **Lorenzo Nava** | [@Looziolooz](https://github.com/Looziolooz) | Admin Panel, CRUD Operations |

**Kurs:** Lexicon Frontend Development 2025  
**Institution:** Lexicon  
**Handledare:** [Lägg till handledarens namn]  
**Projektperiod:** [Lägg till datum]

---

## ™️ Licens

Detta projekt är utvecklat i utbildningssyfte som en del av Lexicon Frontend Development 2025.

**Licens:** CC0 1.0 Universal  
Projektet är tillgängligt för allmänheten och kan användas, modifieras och distribueras fritt.

---

## 📫 Kontakt

**Team-medlemmar:**
- Federico Barberi - [@fdrcbrbr](https://github.com/fdrcbrbr)
- Isabelle Wincrantz - [@Discokatten](https://github.com/Discokatten)
- Alexander Stauch - [@BlackestDawn](https://github.com/BlackestDawn)
- Lorenzo Nava - [@Looziolooz](https://github.com/Looziolooz)

**Repository:** [https://github.com/BlackestDawn/lexicon-ecommerce-groupproject](https://github.com/BlackestDawn/lexicon-ecommerce-groupproject)

**Live Demo:** [Lägg till deployment-länk här]

---

## 🙏 Tack till

- **Lexicon** för utbildning och stöd
- **Muhammad Bilal Akbar** för [SHOP.CO design template](https://www.figma.com/community/file/1273571982885059508) på Figma Community
- **DummyJSON** för gratis API
- **Next.js Team** för utmärkt dokumentation
- **Open Source Community** för verktyg och bibliotek
- **Våra handledare** för vägledning och feedback

---

## 📄 Licens & Attribution

**Licens:** CC0 1.0 Universal  
Detta projekt är utvecklat i utbildningssyfte som en del av Lexicon Frontend Development 2025.

**Design Attribution:**  
Design baserad på [SHOP.CO - eCommerce Website Template](https://www.figma.com/community/file/1273571982885059508) av Muhammad Bilal Akbar.  
Vi har anpassat och modifierat designen för våra specifika projektbehov.

---

**Skapad med ❤️ av Lexicon Frontend Development 2025**