# Oppgave: Universell utforming og WCAG

## Mål med oppgaven

Du skal lage en enkel nettside som handler om universell utforming, samtidig som nettsiden selv skal følge kravene til universell utforming. Du skal altså både *lære om* temaet og *praktisere* det i koden din.

## Ressurser

Du må lese deg opp selv før du svarer på spørsmålene under. Bruk disse kildene:

* [Uutilsynet.no](https://www.uutilsynet.no/) — les om hva tilsynet er og hva de jobber med.
* NDLA-lenken fra forrige oppgave — bruk denne til å dypdykke i tematikken universell utforming.
* [W3.org — Web Accessibility Initiative (WAI)](https://www.w3.org/WAI/) — for å forstå WCAG og hvor standarden kommer fra.

## Tekniske krav til nettsiden

Disse kravene skal være oppfylt uansett hvordan siden ser ut:

1. **Kontrast skal være godkjent.** Bruk et kontrastverktøy (f.eks. inspiser-verktøyet i nettleseren, eller en WCAG-kontrastsjekker som WebAIM Contrast Checker) og dokumenter at all tekst oppfyller WCAG AA-krav (minst 4,5:1 for normal tekst, 3:1 for stor tekst).
2. **Alle bilder skal ha alt-tekst** som beskriver innholdet eller funksjonen til bildet — ikke bare filnavnet eller en tom streng.
3. **HTML-koden skal være semantisk skrevet.** Bruk riktige HTML-elementer for det de er ment for (f.eks. `<header>`, `<section>`, `<article>`, `<nav>`, `<h1>`–`<h3>`, `<p>`, `<img>` osv.). Minimer bruken av `<div>` — en `<div>` er kun lov når det ikke finnes et mer beskrivende semantisk element å bruke.

## Innhold — 3 spørsmål, 3 deler

Nettsiden skal deles inn i **tre deler**, én del per spørsmål. Hver del skal inneholde spørsmålet, svaret ditt, og et bilde som er relevant for spørsmålet/svaret.

1. Hva menes med universell utforming, og hva står WCAG for?
2. Hva kan være en konsekvens dersom vi lar være å forholde oss til universell utforming (enten på nett eller i virkeligheten)?
3. Hvem er Uutilsynet, og hva er deres primæroppgaver?

## Designkrav — "stygg, men universelt utformet"

Dette er den morsomme utfordringen i oppgaven:

* Hver av de tre delene **skal ha ulik bakgrunnsfarge og ulik tekstfarge**.
* **Svart og hvit er ikke tillatt** — verken som bakgrunn eller tekstfarge, i noen av delene.
* Fargevalgene bør være vanskelige å kombinere (det er meningen at siden skal se litt stygg/skjemmende ut), men **kontrasten skal likevel være WCAG-godkjent** i alle tre delene.

Dette tvinger deg til å faktisk teste og justere farger, i stedet for å bruke sikre standardvalg som svart tekst på hvit bakgrunn.

## Leveranse

* Jobb i VSCode via Git/Github Desktop. Lever link til repository i Teams, enten satt som public eller der jeg er lagt til som collaborator (dette har du eget ansvar for å kontrollere at jeg får tilgang)

## Vurderingskriterier

| Kriterium | Hva jeg ser etter |
|---|---|
| Kontrast | Alle tre deler oppfyller WCAG AA, dokumentert med verktøy |
| Alt-tekst | Alle bilder har beskrivende alt-tekst |
| Semantisk HTML | Riktig bruk av semantiske elementer, minimal og begrunnet bruk av div |
| Innhold | Alle tre spørsmål er besvart med egne ord og faglig korrekt |
| Design | Ulike farger per del, ingen svart/hvit, men fortsatt lesbart og tilgjengelig |
