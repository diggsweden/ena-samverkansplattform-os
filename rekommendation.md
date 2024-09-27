# SPÖP - samverkansplattform för öppen programvara

## Målbild

Det finns en uppsatt samverkansplattform för öppen programvara man som myndighet eller annan representant i offentlig sektor kan ansluta till.

Det är enkelt att komma igång med att samverka kring ett öppet källkod-projekt.

Det finns för den som ansluter en enkelhet och en tydlighet i:

- hur man kommer igång
- info om eventuella kostnader
- dokumenterade säkerhetsaspekter
- tydliga rekommendationer om best praxis för projekten, vad gäller öppen programvara, licens, säkerhet.

Effekter:

- På så sätt slipper myndighet (annan aktör), kommun sätta upp egen infratstruktur eller använda en utom-europeisk molntjänst, (om man så inte önskar sköta det själv). Det underlättar om man har ett eller ett fåtal projekt man vill dela med andra, eller i en utforskande/kompetensbyggande fas.
- Det uppstår en naturlig delningsyta som inte är bundet till enskild myndighet/aktör.
- Det uppstår en naturlig kunskapsbas  om ÖP-arbetsätt, säkerhet, compliance.
- Man använder inte en utom-europeisk molntjänst.

## Avgränsningar

Vi diskuterar en plattform avseed för projekt som är publika eller tänkt att bli publika. En arbetsyta för stängda projekt ställer högre krav.

Punkter märkta med Implementationsdetalj är inte är viktiga i detta arbete förrän senare eller inte alls, eller vid en beställning/realisation av rekommendationen.

## Terminologi

- Samverkansplattform för öppen programvara:

  En av de tillgänglig plattformar för kodfokuserade samarbeteb som finns som SaaS och on-prem: - exempelvis: GitLab, Gitea med mera.

- Öppen källkod/Öppen Programvara/Open Source:

  Synonymer. Kort och gott en juridisk licensform och ett samarbetssätt.

## Krav o diskussionspunkter

### Övergripande

- Styrning:
  - En återkommande styrning med representanter från varje myndighet: DISKUSSION

- Kostnadsdelningsmodell:
  - Kostnadsfördelning baserat på användare eller schablon: DISKUSSION

- Användarpolicy:
  - Riktlinjer för projektskapande och -hantering: DISKUSSION, Implementationsdetalj
  - Standarder för kodkvalitet och granskningsprocesser: DISKUSSION, Implementationsdetalj

- Onboardingprocess:
  - Dokumentation för nya användare: DISKUSSION, Implementationsdetalj

- Support och underhåll:
  - Roller och ansvar för systemadministration: DISKUSSION

- Efterlevnad och juridiska frågor:
  - Efterlevnad av relevanta förordningar (t.ex. dataskyddslagar): DISKUSSION
  - Immaterialrättsliga frågor för delade projekt: DISKUSSION

- GemenskapU/Community-policy:
  - Externa bidragsgivare till öppen källkodsprojekt: DISKUSSION
  - Externa bidragsgivare till öppen källkodsprojekt: DISKUSSION
  - Process för att hantera offentliga ärenden och merge-förfrågningar: DISKUSSION

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

- Hantering av externa bidragsgivare:
  - Hantera behörigheter för bidragsgivare utanför myndigheterna

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

### Teknikfokuserade

- Rekommenderad plattformen:
  - GitLab, Gitea/Foregjo, GitHub enterprise: FÖR DISKUSSION

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

- Integration och CI/CD:
  - Sätt upp delade runners för CI/CD-pipelines: DISKUSSION
  - Integration med andra verktyg (ärendehanteringssystem, chattsystem): DISKUSSION

- Övervakning och loggning:
  - Implementera övervakningsverktyg för systemhälsa: Implementationsdetalj
  - Loggning för felsökning: Implementationsdetalj
