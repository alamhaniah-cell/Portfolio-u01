Del 2: Reflektion
Du skriver reflektionen i din README, tillsammans med länken till den publicerade sidan. Max 1 000 ord.
Det här är inte en sammanfattning av vad du gjort, utan en förklaring av varför. Utgå från din egen kod och hänvisa konkret till den.
Reflektionen ska svara på:
Från skiss till kod. Hur gick du tillväga? Var det något i skissen som var svårt att översätta till HTML och CSS, och hur löste du det?


Jag började med att studera Pawans design i Figma för att förstå  hur sidan skulle se ut. Jag valde att arbeta med mobilverisionen först eftersom uppgifterna utgick från mobile first. Jag byggde upp HTML-strukturenm och använde sedan CSS för att anpassa färger, avstånd, bilder och placeringar.


Det svåraste var att få sidan att se rätt ut på både mobil och desktop. Jag hade bland annat problem med menyn, profilbilden och placeringen av mina projekt. Jag löste detta genom att testa olika CSS-regler och använda mobile queries för att anpassa layouten efter skärmstorleken.


Semantik. Vilka HTML-element valde du för sidans olika delar, och varför just de? Var landade du i ett div för att inget bättre fanns?


Jag använde olika HTML-element beroende på deras funktion. Till exempel använde jag nav för navigationsmenyn eftersom den innehåller länkar till sidans olika delar.


Jag använde section för att dela upp innehållet i bland annat About Me, Tech Stack, Work, Experience och Projects. Jag använde även h1, h2 och h3 för rubriker eftersom det skapar en tydlig struktur


Jag använde div när jag behövde gruppera element som hör ihop, till exempel i mina projektkort med klassen project-card. Där behövde jag en behållare för att kunna styra hur bild, text och länkar skulle placeras med CSS.


Layout. Var använde du Flexbox, var använde du Grid, och vad avgjorde valet? Hur gjorde du sidan responsiv, och varför lade du brytpunkterna där du gjorde?


Jag använde både Flexbox och Grid eftersom de passar för olika typer av layout. Flexbox använde jag bland annat i navigationsmenyn och för att placera element brevid varandra eller under varandra. Det gjorde det enklare att kontrollera avstånd och centrering.


Grid använde jag för mina projekt eftersom jag ville kunna visa flera projektkort i kolumnar på desktop.


Jag arbetade med mobile first, vilket innebär att jag först skrev CSS för mindre skärmar och sedan använde @media för att ändra layouten på större skärmar. JAg valde detta eftersom mobilskärmen har mindre utrymme och innehållet därför behöver placeras annorlunda.


Tillgänglighet. Vad har du gjort för att sidan ska gå att använda för fler? Hur testade du det, och vad visade testet? Vad återstår?


Jag har försökt göra sidan tydlig genom att använda rubriker, vanliga länkar och beskrivande texter. Jag har även använt alt på bilder för att beskriva deras innehåll.


Jag har testat sidan genom att använda utvecklarvertygen i Chrome och växla mellan mobil-desktopsstorlek. Det hjälpte mig att upptäcka problem med bland annat placeringar och bilder.


Det jag skulle vilja testa mer är om sidan fungerar bra med tangentbord och skärmläsare. Jag skulle även vilja kontrollera färgkontrasterna för att säkerställa att texten går att läsa.


Användbarhet. Vilka UX- eller UI-principer känner du igen i Pawans design? Är det något du hade gjort annorlunda, och varför?


I Pawans design känner jag igen flera principer som gör en hemsida enkel att använda. Navigationsmenyn gör det lätt att hitta mellan olika delar och rubrikerna visar tydligt vad varje sektion handlar om


Designen har också återkommande färger och liknande avstånd, vilket gör att sidan känns sammanhängande. Jag tycker att det är bra eftersom användaren lättare kan förstå sidans struktur. 


Om jag fick ändra något skulle jag vilja göra mobilmenyn mer användarvänlig, exempelvis genom en menyknapp. Det skulle kunna göra navigeringen enklare på mindre skärmar.


Styrkor och brister. Vad blev bra, och vad skulle du bygga om med mer tid?


JAg tycker att det som blev bäst var att jag lyckades skapa både mobil- och desktopversionen av min portfolio. Jag är också nöjd med projektsektionen och hur jag fick bilder, rubriker och länkar att fungera tillsammans. Även att man kan trycka på exempelvis About och komma till den sidan


Det jag hade mest problem med var CSS och media queries. Ibland ändrades mobilverisionen när jag försökte fixa desktopversionen. Jag lärde mig därför att det är viktigt att förstå vilka CSS-regler som påverkar olika skärmstorlekar.


Om jag hade mer tid skulle jag vilja struktura min CSS och minska upprepande regler. Det skulle göra koden enklare att förstå och ändra i framtiden.


AI-verktyg. Om du använt dem: till vad, och vad ändrade du i det som genererades?
Jag har använt ChatGPT som stöd under arbetet frsmförallt när jag fastnat i HTML och CSS för länge. Ai har hjälpt mig komma vidare men har förstått att man inte bara ska kopieran de som står utan be ai förklara så man även förstår koden och felen. Ibland har ai gett mig felaktiga koder då har jag behövt gå in testa annat och försöka igen.

Länk till hemsidan: [Sätt in publicerad länk här]
