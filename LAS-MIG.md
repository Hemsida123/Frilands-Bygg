# Frilands Bygg — ny webbdesign

15 färdiga HTML-sidor inklusive 404, sju tjänstesidor, kontakt, om företaget, omdömen och bildgalleri. Innehållet i dist är hela webbplatsen. Ingen installation eller byggprocess behövs för webbhotell eller GitHub Pages.

## Publicering
Ladda upp ALLT innehåll i dist (HTML, styles.css, script.js, assets, robots.txt, sitemap.xml och .nojekyll). Alla interna länkar är relativa och fungerar även i en GitHub-projektmapp.

Designförhandsvisningen har noindex för att inte konkurrera med företagets riktiga webbplats. Vid slutlig publicering: ändra domänen ORIGIN i build.py till den riktiga domänen, ändra meta robots från noindex,follow till index,follow och kör python3 build.py. Då uppdateras canonical, Open Graph och sitemap. Behåll alla bilder i assets. Kontrollera företagets kontaktuppgifter och godkännande före byte av livesida. SEO-grund är implementerad; sökplaceringar kan inte garanteras.

## Kontakt
Telefon och e-post är klickbara. Kontaktverktyget öppnar användarens mejlprogram med vald tjänst och meddelande. Det skickar inte mejl från servern och visar ingen falsk skickat-bekräftelse. Ingen bokningskalender eller betalning ingår.

## Bilder och källor
Egna bilder och befintlig logotyp hämtade från frilandsbygg.se/services och /about. Ursprungliga källor och urval dokumenteras i research/assets-manifest.json. Mallbilder från projektsidan och bilden med Styleroom-vattenstämpel används inte. Fotografiernas ursprungliga collage har bevarats. Galleri visar hela bilden vid klick. Inga videofiler hittades på de granskade sidorna.

Reco: https://www.reco.se/frilands-bygg-montage — 5,0 av 5, 1 omdöme, Dzemila S, juli 2026; omdömet är markerat okontrollerat. Hitta: https://www.hitta.se/verksamhet/frilands-bygg-montage-fhggbhjp — korta citatutdrag från Eva L. och Louise S. Ingen sammanblandning av betyg eller påhittade antal. Kontrollerat 2026-11-18. Betyg och citat är statiska med tydlig källänk, ingen påstådd officiell widget. Rating-schema används inte.

## Kontroller
Alla lokala sidlänkar/bilder kontrollerade, JSON-LD validerad och JavaScript syntaxkontrollerad. Mobilmeny, bildgalleri, FAQ och förvald tjänst på kontakt fungerar. Alla innehållssidor kontrollerade vid 320px utan horisontellt överflöde. Visuell granskning vid 390px och datorstorlek. Lighthouse-poäng har inte mätts.

Förhandsvisning: https://frilands-bygg-design.carlzzon121.chatgpt.site (privat).
