# Da Sergio — Demo

Concept website demo progettato e sviluppato da Punto Due Studio per Da Sergio, Colorno (PR).

> Concept dimostrativo non commissionato · Punto Due Studio

## Creative thesis

**La Bassa, servita con misura.**

La demo evita sia il rusticismo generico sia l'estetica da ristorante fine dining impersonale. La direzione visuale nasce dalla tavola apparecchiata, dalla cucina emiliana e dal contesto di Colorno: composizione ordinata, porcellana, tovaglia, menu stampato, verde salvia, bordeaux e una tipografia più classica.

È volutamente diversa dalle altre demo Punto Due Studio: niente materia/farina di Sanafollia, niente spatial minimal di Sój, niente gig-poster/nightlife di Vicolo Stretto.

## Dati verificati utilizzati

Verifica effettuata il 15/09/2026.

- Nome: Da Sergio / Ristorante da Sergio
- Indirizzo: Via Giuseppe Mazzini 21, 43052 Colorno PR
- Telefono principale usato: +39 0521 892758
- Cucina: italiana, emiliana
- Tripadvisor: 4,2/5, 240 recensioni, n. 2 di 26 ristoranti a Colorno al momento della verifica
- Restaurant Guru: fascia indicativa €20–30 a persona; aggiornato 12/08/2026
- Facebook pubblico: https://www.facebook.com/dasergiocolorno
- Presenza web proprietaria forte: non emersa; directory recenti rimandano a Facebook

## Cucina e piatti

La demo non inventa un menu corrente. Usa categorie e piatti ricorrenti in fonti pubbliche recenti, tra cui:

- tortelli / ravioli / anolini
- salumi, prosciutto crudo, culaccia e Parmigiano Reggiano
- carni e proposte stagionali
- sbrisolona e zabaione

Restaurant Guru e recensioni Tripadvisor recenti citano anche i Tortél Dóls. La demo li presenta come elemento territoriale e potenzialmente stagionale, non come piatto garantito sempre disponibile.

## Tortél Dóls — contesto territoriale

Fonti ufficiali della Confraternita e di Colorno Turismo descrivono il Tortél Dóls come piatto tipico della Bassa Parmense e in particolare di Colorno, con ricetta tradizionale legata a mostarda, pere nobili, mele cotogne e vino cotto. È un prodotto stagionale.

## Conflitti tra fonti

### Telefono
Fonti recenti come Tripadvisor e Restaurant Guru convergono su **0521 892758**. Directory più vecchie riportano anche **0521 815148**. La demo usa il numero più recente e meglio confermato.

### Orari
Tripadvisor e Restaurant Guru riportano fasce simili ma non identiche; altre directory mostrano orari più vecchi o generici. Per questo la demo non pubblica una tabella orari definitiva e invita a chiamare prima della visita.

## Fonti principali

- Tripadvisor — Ristorante da Sergio, Colorno
- Restaurant Guru — Da Sergio, Colorno
- Sluurpy — Ristorante Da Sergio, Colorno
- Tortél Dóls di Colorno — sito ufficiale della Confraternita
- Colorno Turismo — Tortél Dóls / tradizione gastronomica
- TuttiAffari / Mapstr — usati per confronto contatti e presenza Facebook

## Distinctive decisions

1. Hero costruito come tavola apparecchiata astratta, non come hero fotografico.
2. Sistema visuale più classico e misurato: paper / porcelain / sage / burgundy.
3. Sezione cucina trattata come sequenza di portate, non come card standard.
4. Sezione territorio costruita con archi grafici e Colorno come elemento narrativo.
5. Nessuna fotografia di terzi re-hostata: visual principale originale in HTML/CSS.

## Funzionalità

- responsive navigation
- click-to-call
- Google Maps
- Facebook
- mobile action dock
- progressive reveal
- `prefers-reduced-motion`
- keyboard focus states
- Schema.org `Restaurant`
- SEO / Open Graph base
- custom 404
- Netlify configuration
- security headers

## QA eseguito

Controlli strutturali completati:

- JavaScript valido con `node --check`
- nessun anchor interno mancante
- nessun asset locale mancante
- CSS con parentesi bilanciate
- gerarchia semantica principale presente

Il rendering Chromium locale in questa sessione non ha prodotto screenshot affidabili, quindi il responsive visual QA completo va effettuato sul deploy Netlify reale.

## Deploy Netlify

Sito statico senza build step.

- Base directory: vuota
- Build command: vuoto
- Publish directory: `.`
- Functions directory: vuota

Dopo il deploy aggiungere canonical, `og:url`, sitemap e `og:image` definitivo.
