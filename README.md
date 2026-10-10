# Jaktlaget 1.2.7

Polerad mobilversion byggd vidare från funktionerna i 1.2.1 och djurslagsmodellen i 1.2.2.

## Förbättringar
- Sidhuvudet är större och visar endast jaktlagets namn samt årsparet, exempelvis 2026/2027.
- Jaktåret har tagits bort från första kortet för att undvika dubbelinformation.
- Första kortet heter Aktuell fördelning och innehåller KPI-värden och ett större diagram.
- Inställningsknappen ligger säkrare innanför skärmkanten.
- Registreringsknappen har bättre textpassning och större klickyta.
- Sidfoten är högre med större och jämnare fördelade knappar.
- Fördelningstabellen har tydligare kolumner, högerställda siffror, större radhöjd och bättre mobilrullning.
- Rådjur, Vildsvin, Dovhjort, Kronhjort och Älg med detaljerade typer finns kvar.
- Försök till migrering av lokalt sparad data från version 1.2.1 och 1.2.2 ingår.

Ersätt alla filer i GitHub-repositoryts rot med innehållet i ZIP-filen.

## Anpassningar i 1.2.7
- Horisontell sidscrollning är borttagen på appnivå.
- Kort, diagram, formulär och knapprader anpassas till smala mobilskärmar.
- Inställningsknappen är flyttad längre åt vänster och tar hänsyn till säkra skärmkanter.
- Den stora registreringsknappen har smalare maximal bredd och säkrare textradbrytning.
- Sidfoten har ny bakgrund, jämnare knappfördelning, större klickytor och mer balanserad central registreringsknapp.
- Fördelningstabellen är kompaktare. Endast tabellen kan rullas horisontellt när skärmen är mycket smal.

## Nytt i 1.2.7
- Djur kan registreras utan tilldelning.
- Tilldelning kan göras senare från Historik.
- Grön status visar Fördelning klar.
- Orange status visar Ej fördelad.
- Ofördelade djur ingår i antalsstatistik men inte i medlemmarnas fördelningsstatistik.

## Nytt i 1.2.7
- Det senaste bytet av jaktår kan ångras under Inställningar.
- Ångra ändrar endast vilket jaktår som är aktivt. Inga registreringar raderas eller flyttas.
- Djur som hunnit registreras i det nya jaktåret ligger kvar på det året och kan visas via Historik.
- När det gamla jaktåret avslutas igen återgår appen till det redan påbörjade nya jaktåret med dess registreringar kvar.

## Nytt i 1.2.7
- Innan ett årsbyte ångras visas en tydlig lista över djur som registrerats efter årsbytet.
- Listan visar datum, djurslag, typ, vuxenekvivalent, skytt samt om djuret är fördelat eller inte.
- Samma djur listas också i bekräftelserutan innan användaren genomför ångringen.
- Inga djur raderas eller flyttas när årsbytet ångras.
