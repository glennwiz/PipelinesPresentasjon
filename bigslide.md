## Azure DevOps Pipelines

Azure DevOps Pipelines er en skybasert tjeneste som gir deg muligheten til å planlegge, spore, teste og deploye applikasjoner. Med Azure DevOps Pipelines har du verktøy for å administrere og automatisere kodeflyter, inkludert bygg, test og deploy.

I denne presentasjonen skal vi se på de ulike verktøyene og funksjonene som finnes i Azure DevOps Pipelines, inkludert:

- Byggverktøy: Mulighetene for å kompilere kildekoden og lage byggkonfigurasjoner
- Testverktøy: Mulighetene for å automatisere tester og få oversikt over testresultatene
- Deployverktøy: Mulighetene for å deployere koden til ulike plattformer
- Integrasjonsverktøy: Mulighetene for å integrere med andre tjenester og verktøy

CI (Continuous Integration) handler om å integrere koden din med et git-repository ofte, for eksempel hver gang du gjør en endring eller push til repositoryet. Formålet med CI er å sørge for at koden din alltid er i en deploybar tilstand, slik at du kan deploye den når som helst.

CD (Continuous Deployment) handler om å automatisere deployprosessen for applikasjonen din, slik at den blir deployet så snart den er klar. Formålet med CD er å sørge for at ny kode blir tilgjengelig for brukerne så raskt som mulig, uten at du trenger å gjøre noe manuelt.

---

## Byggverktøy

Azure DevOps Pipelines inneholder en rekke verktøy for å bygge og kompilere kildekoden din. Du kan bruke en eksisterende byggkonfigurasjon, eller lage en selv.

Muligheter med byggverktøyene inkluderer:

- Muligheten for å trigge en byggjobb ved hjelp av hendelser som f.eks. push til et git-repository
- Muligheten for å kjøre forskjellige byggverktøy, f.eks. Maven, Gradle eller MSBuild
- Muligheten for å samle inn bygglogger og andre byggrelaterte data, slik at du kan finne og løse byggfeil

---

## Testverktøy

Azure DevOps Pipelines inneholder en rekke verktøy for å teste koden din automatisk. Du kan bruke eksisterende tester, eller lage egne.

Muligheter med testverktøyene inkluderer:

- Muligheten for å kjøre enheter- og integrasjonstester på forskjellige plattformer, f.eks. Windows, Linux eller macOS
- Muligheten for å samle inn testresultater o
- Muligheten for å deployere koden til ulike plattformer, f.eks. Azure, AWS, kunde servere, interne test servers osv.
- Muligheten for å spore deployhistorikk, slik at du kan se hvilken kode som har blitt deployet og når
- Muligheten for å lage ulike utgivelsesmiljøer, f.eks. for testing, staging og produksjon, slik at du kan teste koden din før den blir tilgjengelig for alle

---

## Integrasjonsverktøy

Azure DevOps Pipelines inneholder en rekke verktøy for å integrere med andre tjenester og verktøy. Du kan integrere med GitHub, Jenkins, Docker og mange andre.

Muligheter med integrasjonsverktøyene inkluderer:

- Muligheten for å få varsel om hendelser i andre tjenester, f.eks. når det blir gjort en push til et git-repository
- Muligheten for å kjøre eksterne verktøy som en del av en bygg- eller deployjobb, f.eks. for å generere dokumentasjon eller lage en docker-image
- Muligheten for å integrere med andre verktøy for å få oversikt over kodekvalitet, f.eks. ved å kjøre kodeanalyseverk:tøy eller statisk kodeanalyse

---

## Andre Options
- Muligheten for å lage forskjellige pipelines for forskjellige applikasjoner eller komponenter, slik at du kan ha ulike bygg- og deployprosesser for ulike deler av koden din
- Muligheten for å lage ulike steg i en pipeline, f.eks. for å kjøre enheter- og integrasjonstester, lage en docker-image eller deploye koden til ulike miljøer
- Muligheten for å integrere Azure DevOps Pipelines med andre verktøy og tjenester, f.eks. for å få varsel om hendelser eller kjøre eksterne ver
- Muligheten for å se statistikk og overvåke pipelines i Azure DevOps Pipelines, f.eks. ved å se på bygg- og deployhistorikk, samle inn loggdata eller få varsel om feil
- Muligheten for å lage ulike tilgangsrettigheter og kontroller for å sikre at riktig personer kan gjøre endringer i pipelines og kode
- Muligheten for å bruke Azure DevOps Pipelines med ulike programmeringsspråk og plattformer, f.eks. Java, .NET, Python, Node.js, Android og iOS

![image](https://user-images.githubusercontent.com/195927/211021233-8ef0d041-a2cd-495a-ac6f-f55247725c7a.png)
