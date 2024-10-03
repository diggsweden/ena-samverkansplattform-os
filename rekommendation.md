# SPÖP - Samverkansplattform för Öppen Programvara

## Målbilden

Det finns en uppsatt samverkansplattform för öppen programvara myndighet eller annan representant i offentlig sektor kan ansluta till.

Det finns för den som ansluter en enkelhet och en tydlighet i:

- hur man kommer igång
- info om eventuella kostnader
- dokumenterade säkerhetsaspekter
- tydliga rekommendationer om best praxis för projekten, vad gäller öppen programvara, licens, säkerhet.

Det är lätt att komma igång med att samverka kring ett öppet källkod-projekt.

## Effekter

- En organisation slipper börja med att sätta upp egen infrastruktur. Det underlättar om man har ett eller ett fåtal projekt man vill dela med andra, eller som organisation är i en utforskande/kompetensbyggande fas kring delning/samarbete ÖP.
- Det uppstår en naturlig delningsyta som inte är bundet till enskild myndighet/aktör.
- Det uppstår en naturlig kunskapsbas  om ÖP-arbetsätt, säkerhet, compliance.
- Man slipper skriva sin egen lösningsvariant hos varje myndighet.
- Man använder inte en utom-europeisk molntjänst.

??: Hur mäter vi effekterna på ett sätt som har lite vikt i verkligheten. Här kan vi använda fall från verkligheten, från från konkreta exempel som gjorts på diggsweden med fk, hav, af, skv.

## Avgränsningar

Vi diskuterar en plattform avsedd för projekt som är direkt publika eller som ska bli publika. En arbetsyta för stängda projekt skulle ställa högre krav på sekretess med mera, i och med att det där förekommer information som inte ska bli publik.
Att projekten ska bli publika innebär inte att det behöver vara det intialt  (t.ex. under kompetenslärande fas eller en uppstädningsfas), men att det ska finns en tänkt plan för en nära framtid då de ska bli det.

## Terminologi

- Samverkansplattform för öppen programvara:

  En av de tillgänglig plattformar för kodfokuserade samarbeten som finns som SaaS samt on-prem: - exempelvis: GitLab, Gitea med mera.

- Öppen källkod/Öppen Programvara/Open Source:

  Synonymer. Kort och gott en juridisk licensform och ett samarbetssätt.

## Krav o diskussionspunkter

Här följer en lista med ämnespunkter/krav och ett försök till att gruppera dessa.
En del av dem är märkta med *Implementationsdetalj*, de är inte är viktiga i detta arbete förrän långt senare vid en beställning/realisation.

En dynamisk lista över punkter vi behöver arbeta oss igenom.

### Övergripande

- Styrning:
  - En återkommande styrning med representanter från varje myndighet: DISKUSSION

- Kostnadsdelningsmodell:
  - Kostnadsfördelning baserat på användare eller schablon: DISKUSSION

- Användarpolicy:
  - Riktlinjer för projektskapande och -hantering: DISKUSSION, Implementationsdetalj
  - Standarder för kodkvalitet och granskningsprocesser: DISKUSSION, Implementationsdetalj

- Roller
  - klargör, se "Issues" här på GitHub.

- Onboardingprocess:
  - Dokumentation för nya användare: DISKUSSION, Implementationsdetalj

- Support och underhåll:
  - Roller och ansvar för systemadministration: DISKUSSION

- Efterlevnad och juridiska frågor:
  - Efterlevnad av relevanta förordningar (t.ex. dataskyddslagar): DISKUSSION
  - Immaterialrättsliga frågor för delade projekt: DISKUSSION

- Gemenskap/Community-policy:
  - Process för att hantera offentliga ärenden och merge-förfrågningar: DISKUSSION

- Bidrag till ett projekt:
  - Ägandeskap : Vem äger bidraget
      Bidraget äger upphovsmannen. Det finns en norm som open source-världen kalla inbound=outbound. I bidragsguider för projektet näms detta. Genom bidraget godkänner upphovsmannen/ägande organisation att det bidrag man tillför kan släppas under projektets huvudlicens.

  - Skrivrättigheter till Projektet (Pull Requests)

    Vem ska ha skrivrättigheter till projekten? 
    De flesta myndigheter säkerhetsklassar idag sin personal. Det ska vara en säkerhetsklassad person som har skrivrättigheter i projekten eller är involverad i att godkänna PR. 

  - Externa bidragsgivare till öppen källkodsprojekt:
      Det ska vara möjligt för externa (medborgare) att skaffa ett konto och lägga ett ärende till ett projekt,felrapport, ärende.
        ??: ska detta kräva eleg eller ska man kunna registrera en anonymt konto, likt GitHub?

- Dokumentation:
  - Underhåll uppdaterad systemarkitekturdokumentation, användarguider: DISKUSSION, Implementationsdetalj

- Kontinuerlig förbättring:
  - Processer och policyer, feedback: DISKUSSION

- API-för plattformen:
  - API-åtkomst: DISKUSSION

- Datalagring och arkivering:
  - Policy för arkivering,datalagring: DISKUSSION
  - Hantera inaktiva projekt: DISKUSSION  

- Licensefterlevnad:
  - Verktyg och processer för att spåra användning av öppen källkodslicenser: DISKUSSION,

- Resursavgränsningar:
  - Projekt- CI/CD och grupplagringssgränser: DISKUSSION, Implementationsdetalj

- Kunskapsdelning:
  - Uppmuntra samarbete och delning av bästa praxis mellan myndigheter: DISKUSSION

- Loggning, audit:
  - Granskning av åtkomstloggar och användaraktiviteter: DISKUSSION

- Beroendehantering:
  - Paket- och container-register (t.ex. NPM, Maven, Docker): DISKUSSION

- Incidentresponsplan:
  - Säkerhetsincidenter i plattform: DISKUSSION
  - Säkerhetsincidenter i projekt på plattform: DISKUSSION

- Internationalisering och lokalisering:
  - Språk, språklag: DISKUSSION

- Projekt/kodkvalitet:
  - Övergripande riktlinjer för kodstandarder: DISKUSSION

- Tillgänglighetsefterlevnad:
  - Säkerställa att GitLab-instansen uppfyller tillgänglighetsstandarder
  - Regelbundna tillgänglighetsgranskningar och förbättringar


- Projektlivscykelhantering:
  - Policyer för arkivering eller borttagning av inaktiva projekt
  - Processer för projektöverlämnanden mellan myndigheter

- Efterlevnadsrapportering:
  - Regelbundna revisioner för att säkerställa efterlevnad av policyer

- GitLab runner-hantering:
  - Dela och allokera CI/CD-runners

- Datamigrering: Ej aktuellt

- Användarupplevelsekonsistens:
  - Standardiserade tillgängliga projektmallar: DISKUSSION, Implementationsdetalj

- Kapacitetsuppbyggnad:
  - Kompetensdelning och utbildning mellan myndigheter: DISKUSSION

- Gallring, arkivering: DISKUSSION
- Diarieföring: Klassas om arbetsmaterial och undvika diarieföring. Communityforum.

- Säkerhetsfokus som krav på produktleverantör

    Organisation som tillhandahåller plattformen ska kunna visa att man arbetar adekvat och brett med säkerhet, med exempel - (arbetar leverantöre med ISO 2700x ? med mera).

        Här uppfyller exempelvis GitLab, GitHub
        GitLab: https://about.gitlab.com/security/
        GitHub https://github.com/security

      medan flera andra samverkaansplattformar för öppen Källkod-lösningar som exempelvis Gitea, Forjego och Gogs inte uppfyller detta.

- Kraven på Öppen kod och transperans för själva samverkansplattformen

    Är lösningen är Öppen källkod i sig eller tillgänglig som källkod-för-granskning? Man vill ha en långsiktig lösning, och kunna upphandla på kompetens på produkten, inte produkten i sig. Exempel: GitHub för On-Prem stängd kod.
    GitLabs kod är helt öppet för granskning även om inte alla öppna delar sedan är Open Source.
 
### Teknikfokuserade

- Infrastruktur och värdskap:
  - Värdskap: Diskutera demoinstans med mera: FÖR DISKUSSION
  - Självhostat eller GitLab SaaS: Grundidén är självhostat.
  - Serverkrav (CPU, RAM, lagring): Implementationsdetalj,.
  - Skalbarhet: Implementationsdetalj
  - Kommunikationsplan för uppdateringar och underhåll: Implementationsdetalj

- Säkerhet:
    Användarkonton:
      - Tvåfaktorsautentisering (2FA)
      - Regelbundna säkerhetsgranskningar och uppdateringar av värd

  - SSL/TLS-kryptering
  - Upprätta lämpliga brandväggsregler

- Åtkomstkontroll:

  - Anonymitet:
      Det kan finnas behov av att hantera ett alias för ett konto, t.ex. för program om görs för brottsförebyggande mål eller annat känsligt, där det kan finnas en potentiell hotbild mot enskild utveckare.
      Det kan man lösa genom att arbeta med alias i dessa fall.
      Det gäller då att bara driftande myndighet har uppgifterna om vem om kontot tillhör.En lösning där man har ett konto för alla commitare bör undvikas då det inte ger någon spårbarhet för adminstratör.

  - Metoder för användarautentisering: FÖR DISKUSSION
  - Standard per projekt: offentlig, privat: FÖR DISKUSSION
  - Standard per användare: FÖR DISKUSSION
  - Metoder för användarautentisering (LDAP, SAML, OAuth): FÖR DISKUSSION
  - Standard Grupp- och projektbehörigheter: FÖR DISKUSSION

- Säkerhetskopiering och katastrofåterställning:
  - Regelbundet schema för säkerhetskopiering: Implementationsdetalj
  - Offsite-lagring av säkerhetskopior: Implementationsdetalj
  - Plan för katastrofåterställning och testning: Implementationsdetalj

- Prestandaoptimering:
  - Lastbalansering för hög tillgänglighet: Implementationsdetalj

- Körbara projekt-artefakter:
  - Ett projekt kan vilja levera körbara artefakter i en mängd format. Binär, paket, container.
    ?? Ska vi rekommendera att man publicerar den på samverkansplattformens registry? Eller hos en tredjepartsaktör som exempelvis dockerhub, npmjs etc?
    ?? Vilken rekommendation ställer vid för verifiering av artefakterna. Signerade hashkontroller av binärer etc.
    ?? Att byggprocssens uppfyller SLSA?

- Integration och CI/CD:
  - Sätt upp delade runners för CI/CD-pipelines: DISKUSSION
  - Integration med andra verktyg (ärendehanteringssystem, chattsystem): DISKUSSION

- Övervakning och loggning:
  - Implementera övervakningsverktyg för systemhälsa: Implementationsdetalj
  - Loggning för felsökning: Implementationsdetalj
