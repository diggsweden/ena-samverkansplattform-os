# Idébeskrivning till den förvaltningsgemensamma digitala infrastrukturen Samverkansplattform Öppen Programvara 

## 1 Identifierat behov

### Bakgrund

En av alla de byggstenar som möjligör effektiv modern digitalisering är samverkan kring Öppen Programvara/Källkod.
Flera myndighet och andra aktörer i offentlig sektor arbetar alltmer aktivt med det, både som producent, konsument och i samverkansform. Många avänder idag utom-Europeiska molntjänster som exempvis GitHub som har en del brister. Det finns också idag ett identifierat  gemensamt behov av att  samtidigt minimera de trösklar som idag har identifierats inom myndighetssamverkan för att säkert och effektivt kunna arbeta på dessa, och hur vi delar.

## Identifierade problem

Här kommer en beskrivning av några identifierade problem.
Där ingår en del konkreta exempel, som utgår vi hur man arbetar på GitHub-ytan DiggSweden för att det inte ska bli alltför övergripande. Egentligen är det samma problem för alla.

### Problem, risker och konsekvenser
- Uteslutning av medarbetare i offentlig sektor som inte får använda utomeuropeiska molntjänster.
- Snabba ändringar i tjänsten och risk för inlåsning.
- Otydlighet kring projektägarskap om knutet till viss myndighet. Exempelvis DiggSweden
- Begränsade resurser att hantera samverkansplattformar, ingen skalbarhet.

#### Risk för uteslutna medarbetare i offentlig sektor
Medarbetare i offentlig sektor utesluts från att samverka kring samverkansprojekt på GitHub om deras interna policy ej tillåter att de använder utomeuropeiska molntjänster. Det kan innebära att en del stängs ute från samverkansprojekt kring öppen källkod.

#### Risk för hastigt ändrade tjänsteförutsättningar och inlåsning
Ägarförhållanden, utom-Europeiska politiska förändringar som påverkar tjänster, prissättningar, tillgänglighet skulle kunna förändras med mycket kort varsel, och tvinga fram oplanerade negativa förändringar i tjänsten.

#### Risk för otydlighet av projektägarskap
Externa eller medborgare blandar ihop ägandeskapandet av projekten om del ligger under en samverkansplattform knuten till en viss myndighet i dagsläget; man antar exempelvis att det som ligger under Digg's GitHub är ju Digg's egna projekt. Det blir oklart, en extra support, men framför allt en förvirring för den vill använda eller bidra till projektet. 

#### Ingen har i uppdrag (och avsatta resurser för) uppdrag att hantera samverkansplattform annat än för interna behov, ej skalbart.
Digg's befintliga GitHub-ytor är i första hand avsedda för Digg's egna projekt och inte från början tänkta som officiella samverkansytor för andra aktörer i offentlig sektor; i dagsläget sker sådan samverkan något slumpartad utifrån behov, god vilja. Den tid Digg kan lägga på detta är redan idag begränsad och frivillig, när/om tid finnes. Det är inte skalbart långsiktigt.

### Förvaltningsgemensamt behov
En öppen samverkansplattform för Öppen Programvara löser de beskrivna problem och främjar det förvaltningsgemensamma grundläggande behovet att kunna samverka kring återanvändbara lösningar. 

I dialoger med olika aktörer har man sett behovet av att kunna erbjuda en samverkansplattform för att kunna främja samverkan mellan offentliga organisationer. Särskilt mindre aktörer ser detta behov och hänvisar till brist på kapacitet, prioriteringar, kunskap samt resurser.

En gemensamt förvaltad samverkansplattform för öppen programvara löser flera långsiktiga behov, och främjar även kunskapsdelning genom praktisk samverkan och learning-by-doing. Detta i sin ur är en viktig pusselbit för att uppfylla Interoperabilitetetsförordningen som markerar en tydlig inriktning mot öppen programvara-lösningar.

I grunden behöver det säkerställas en hållbar lösning för nationella såväl som Europeiska samarbeten över förvaltningar.

## 2 Hypotes 
I interoperabilitetsförordningen adresseras kataloger för öppen programvara, byggstenar, som utvecklas och används inom europeiska offentliga förvaltningar. Flera länder har därför valt nationella samverkansplattformar för öppen programvara för att lättare kunna samla och kommunicera kring de byggstenar som tas fram. Två exempel är 
- Tyskland: https://opencode.de/en 
- EU-kommissionen: https://code.europa.eu/info/about.

Flera av de identifierade svenska utmaningarna skulle lösas med denna typ av nationella samarbetsplattform. 
- Genom samverkansplattformen får Sverige bättre förutsättningar att uppfylla interoperabilitetsförordningen. 
- Plattformen underlättar inte bara teknisk samverkan i projekt, utan stödjer även förändringsarbetet mot ökad samverkan kring kod, data och tjänster inom offentlig sektor.
- En annan fördel är att plattformen främjar användningen av olika standarder, som säkerhetsstandarder och standarder för offentlig kod. Det blir också en kunskapsspridande plattform inom dessa områden.

## 3 Målgrupp
Berörda intressenter 
1. Myndigheter och/eller samverkansaktörer som arbetar med öppen programvara. 
2. Byggblock inom den förvaltningsgemensamma digitala infrastrukturen.

## 4 Förväntade nyttor och effekter
- Ökad delaktighet och samutveckling
- Bättre delning och återanvändning av digitala resurser.
- Ökad kunskapsdelning om öppen programvara.
- Ökade förutsättningar för att katalogisera öppen programvara
- Underlätta samverkan i byggblock inom den digitala infrastrukturen.
- Ökat och gemensamt fokus på säkerhet i offentliga kodbaser
- Ökade förutsättningar att realisera interoperabilitetsförordningen i Sverige

## 5 Övergripande kostnadsuppskattning
I första fasen innebär arbetet endast att de inblandade aktörerna avsätter viss tid för projektet. Kanske någon dag i månaden. Beroende på vilken aktör som ansvarar för att sätta upp en stabil test/demo-leverans (Digg eller annan aktör) krävs också senare teknisk arbetstid. Om exempelvis Digg ansvarar för detta kan det ta några veckor på heltid, inklusive beställningar, tester och beroende på utförarens erfarenhet och organisationens förutsättningar.

I denna utforskande fas ska även en rekommendation tas fram om kostnader för en långsiktig lösning samt löpande drift och administration.

En lyckad leverans av det här är som förslag två komponenter:
- En fungerande demo/test-uppsättning av en befintlig samverkansplattform (exempelvis en GitLab (likt Tysklands https://opencode.de/en).
- En rapport om den befintliga lösningen, med rekommendationer och förslag om ett nästa steg, beskrivning av anslutningskostnader, långsiktig förvaltning och administration.

## 6 Bemanning
Digg är färdledare och samordnar en arbetsgrupp bestående av både anslutna ENA-medlemmar, men också samarbete med övriga samverkansaktörer, som exempelvis eSam, Sambruk, Hav och vatten med mera.

Utryckt intresse har bland annat representanter för Trafikverket, Bolagsverket, Hav- och Vatten, Arbetsförmedlingen, Försäkringskassan.

Kontakt Digg: <ospo@digg.se>

## 7 Tidplan
Leveransförslag:
Senvåren Q2 2025 för rekommendationsrapport/sammanställning (förutsättningar: inofficiell uppstart påbörjas + den som får ansvaret för demo-leverans sätter upp den kan prioritera in det sin verksamhet under höst 2024/25 q1,q2.)