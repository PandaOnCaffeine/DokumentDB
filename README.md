# Reflekstion

## Hvordan var din oplevelse med at arbejde med en dokumentdatabase sammenlignet med en relationel database?

Min oplevelse med at arbejde med dokumentdatabaser har været meget god, meget lærerigt og spændende.
RavenDB har været nemt og en del anderledes fra relationel databaser.

I fremtiden ville jeg nok tænkte mere over om jeg skal bruge en dokumentdatabase eller relationel database til fremtidige projecter.

Jeg kan helt klart se fordele ved dokumentdatabaser til bestemte projecter, men også ulemper til andre projecter, hvor en relationel database ville være bedre.

Synes det har været lærerigt at arbejde med databaser fra en anden vinkel og vil helt klart arbejde vidre med det.
## Hvilke fordele og udfordringer så du ved at bruge en dokumentdatabase til denne type data?
### Fordele:

#### Fleksibilitet: 
Dokumentdatabaser tillader skema-fri lagring af data, hvilket giver mulighed for en fleksibel datastruktur, der kan tilpasses ændringer i applikationskravene.

#### Hurtig udvikling:
På grund af deres skema-frie karakter kan udviklere hurtigt prototypere og ændre applikationer uden at skulle bekymre sig om skemaændringer og migrationsproblemer.

#### Let læselig struktur: 
Dokumenter gemmes normalt i JSON- eller lignende formater, hvilket gør dataene lette at læse og forstå, selv for dem uden dybdegående databaseerfaring.
 

### Ulemper:

#### Manglende komplekse relationer: 
I forhold til relationelle databaser kan dokumentdatabaser have svært ved at håndtere komplekse relationer og transaktioner, hvilket kan begrænse anvendeligheden i visse applikationsscenarier.

#### Mindre avancerede spørgsmål: 
Da dokumentdatabaser normalt ikke understøtter avancerede SQL-spørgsmål som JOIN, kan komplekse dataanalyse og rapporteringskrav være vanskelige at imødekomme.

#### Skalering af ydeevne: 
Mens dokumentdatabaser kan skalere horisontalt, kan ydeevnen af ​​nogle typer af spørgsmål og operationer blive forringet ved stor dataskalering.

#### Datakonsistens: 
På grund af deres distribuerede natur kan dokumentdatabaser nogle gange opleve konsistensproblemer, hvilket kræver specifikke strategier for at håndtere og opretholde datakonsistens.


## Hvordan føler du, at denne oplevelse har påvirket din forståelse af databaser generelt?

Ved at have arbejdet med dokumentdataber, kommer jeg til at tænke på de ting der ikke ville fungere i MsSQL eller at de ting skulle laves på en anden måde for at virke.

Så jeg synes min forståelse er blevet bedre generalt i forhold til databaser.

## Hvorfor RavenDB?

Vi søgte lidt rundt på nettet om generalt information om Dokumentdatabaser, og fandt en der hed RavenDB, som vi ikke havde hørt om før.

Efter lidt undersøgning i hvad RavenDB var og fungerede blev den valgt.

### Hvem Bruger RavenDB
![Query](/Pictures/UsesRavenDB.png)

## Setup og Andet

### [RavenDB Getting Started Guide](https://ravendb.net/docs/article-page/6.0/csharp/start/getting-started)

Hentede RavenDB Server zip file fra RavenDBs hjemmeside, og extractede den i en mappe hvor jeg ville ha den.

I de filer der blev extractet ligger der en Run.ps fil. man Højre klikker og vælger `"Run With Powershell"` for at begynde sin setup.

Efter filen er kørt bliver der åbnet en fane i browseren med en Setup Wizard, hvor man kan Vælge forskellige options.

### Efter Setup Wizard
Når den er færdig gir den mulighed for at åbne en GUI til RavenDB, Hvor man kan oprette databaser og mange andre functioner

### Good to go
Nu er RavenDB oppe og køre og klar til at blive brugt.


## Querys

### Get: All Cakes
###### RQL
![Query](/Pictures/GetCakes%20Query.png)

#### Result
![Query](/Pictures/GetCakes%20Query%20Result.png)

### Get: Under 30 min
###### RQL
![Query](/Pictures/GetUnder30Time%20Query.png)

#### Result
![Query](/Pictures/GetUnder30Time%20Query%20Result.png)

### Get: Med KageNavn
###### RQL
![Query](/Pictures/GetByName%20Query.png)

#### Result
![Query](/Pictures/GetByName%20Query%20Result.png)

### Put: UpdateData
###### RQL
![Query](/Pictures/Update%20Query.png)

#### Result
![Query](/Pictures/Update%20Query%20Result.png)


### Delete: FjernData
###### RQL
Den version jeg installerede har de fjernet DELETE RQL functions så her er et billede hvor man kan se hvor man manuelt kan gøre det
![Query](/Pictures/Delete%20Pic.png)

