# DSGO RFCs


Deze repository bevat de RFCs (Requests for Change) voor het DSGO (Digitaal Stelsel Gebouwde Omgeving).
Het RFC proces zelf staat beschreven op de [DSGO webpagina](https://afsprakenstelseldsgo.atlassian.net/wiki/spaces/DSGO/pages/316971872/Change+en+release+management).

Het RFC overzicht kan weergegeven worden als [issue board](https://github.com/orgs/nl-digigo/projects/10) of als [lijst](https://github.com/orgs/nl-digigo/projects/10/views/6).

Ingelogde gebruikers op Github kunnen comments toevoegen aan bestaande RFC.

RFCs zijn beschreven volgens een [vast template](https://github.com/nl-digigo/DSGO/blob/main/.github/ISSUE_TEMPLATE/rfc.md), en kunnen de volgende kenmerken hebben:

### Status

### Labels

### Priority

| Prioriteit | Omschrijving | Voorbeeld | Prioriteit en opvolging |
| ---------- | ------------ | --------- | ----------------------- |
| blocker | Meerdere ketenprocessen kunnen niet functioneren. Het issue is een showstopper voor de digitale infrastructuur. | Issue met identifiers, Issue in OAuth implementatie | Direct opvolging aan geven. In geval van een blocker op een geïmplementeerde gegevensdienst gaat Incident Management in werking. | 
| critical | Een ketenproces kan niet volwaardig functioneren zolang de wijziging niet is doorgevoerd. Het issue is een showstopper voor het ketenproces.| Endpoint ontbreekt, Transactiepatroon is niet werkbaar, Kritiek attribuut ontbreekt | Direct opvolging aan geven. |
| major | In de bestaande versie of door een extensie is er een workaround waardoor het issue uit de RFC verholpen is. De workaround is echter niet wenselijk voor de lange termijn. | Optioneel veld verplicht maken, Ontbrekend item voor waardelijst, Ontbrekend attribuut, Wijziging in regelgeving| Het issue beschreven in de RFC is geen showstopper maar dermate belangrijk of van toegevoegde waarde dat de wijziging voorrang dient te krijgen. |
| minor | De RFC betreft een uitbreiding, wijziging of verbetering van een gegevensdienst. | Wijziging in standaard waarnaar verwezen wordt, Nieuw object, Nieuwe API| Opvolging zodra de RFC’s met een hogere prioriteit verwerkt zijn. |
| trivial | De impact is nihil en de wijziging zal niet leiden tot nieuwe of gewijzigde functionaliteit. | Typefout, YAML bug | Periodiek of wanneer er tijd over is. |

## Impact
