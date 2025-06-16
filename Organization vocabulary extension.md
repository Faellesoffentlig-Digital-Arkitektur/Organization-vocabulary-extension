# Bilag C - Organization vocabulary extension

Vokabularet indeholder et antal elementer der er fundet relevante til
beskrivelse af organisation og organisatoriske forhold. Vokabularet kan
ses som et supplement til W3Cs Organization Ontology[^1].

| **præfiks** | **navnerum**                                 | **titel**                         |
| ----------- | -------------------------------------------- | --------------------------------- |
| ovx         | https://data.gov.dk/model/core/orgextension/ | Organization vocabulary extension |

## Klasser

### Relation

![](media/image1.emf){width="1.9739129483814524in"
height="0.7469936570428697in"}

| URI                   | https://data.gov.dk/model/core/orgextension/Relation                                                     |
| --------------------- | -------------------------------------------------------------------------------------------------------- |
| Term                  | Relation                                                                                                 |
| Foretrukken term (da) | Relation                                                                                                 |
| Foretrukken term (en) | Relation                                                                                                 |
| Definition (da)       | måden, hvorpå to eller flere aktører er forbundet; en aktørs indvirkning på eller relevans for en anden. |
| Definition (en)       | the way in which two or more agents are connected; an agent\'s effect on or relevance to another.        |

## Objektegenskaber

![](media/image2.emf){width="4.668533464566929in"
height="1.2869564741907262in"}

### har relation

| URI                   | https://data.gov.dk/model/core/orgextension/hasRelation                                    |
| --------------------- | ------------------------------------------------------------------------------------------ |
| Term                  | has relation                                                                               |
| Foretrukken term (da) | har relation                                                                               |
| Foretrukken term (en) | has relation                                                                               |
| Definition (da)       | angiver en kvalificeret relation subjektet (aktøren) har til en eller flere andre aktører. |
| Definition (en)       | indicates a qualified relationship the subject (agent) has to one or more other agents.    |
| Domæne                | foaf:Agent                                                                                 |
| Udfaldsrum            | ovx:Relation                                                                               |

### relation til

| URI                   | https://data.gov.dk/model/core/orgextension/relationTo             |
| --------------------- | ------------------------------------------------------------------ |
| Term                  | relation to                                                        |
| Foretrukken term (da) | relation til                                                       |
| Foretrukken term (en) | relation to                                                        |
| Definition (da)       | angiver en aktør der er objekt i den kvalificerede relation        |
| Definition (en)       | indicates an agent that is an object in the qualified relationship |
| Domæne                | ovx:Relation                                                       |
| Udfaldsrum            | foaf:Agent                                                         |

![](media/image3.emf){width="2.8521741032370955in"
height="2.477489063867017in"}

### har øvre enhed

##### 

| URI                   | https://data.gov.dk/model/core/orgextension/hasUpperUnit                         |
| --------------------- | -------------------------------------------------------------------------------- |
| Term                  | har øvre enhed                                                                   |
| Definition            | Angiver en enhed der er øverst i den formelle organisations hierarkiske struktur |
| Domæne                | org:FormalOrganization                                                           |
| Udfaldsrum            | org:OrganizationalUnit                                                           |
| Underegenskab af      | org:hasUnit                                                                      |
| Modsatrettet egenskab | ovx:upperUnitOf                                                                  |

### øvre enhed i  {#øvre-enhed-i}

| URI                   | https://data.gov.dk/model/core/orgextension/upperUnitOf                                                        |
| --------------------- | -------------------------------------------------------------------------------------------------------------- |
| Term                  | upper unit of                                                                                                  |
| Foretrukken term (da) | øvre enhed i                                                                                                   |
| Definition            | Angivelse af den formelle organisation hvori enheden er placeret på øverste niveau i den hierarkiske struktur. |
| Domæne                | org:OrganizationalUnit                                                                                         |
| Udfaldsrum            | org:FormalOrganization                                                                                         |
| Underegenskab af      | org:unitOf                                                                                                     |
| Modsatrettet egenskab | ovx:hasUpperUnit                                                                                               |

## Datatypeegenskaber

![](media/image4.emf){width="3.66956583552056in"
height="1.3645166229221348in"}

### cvr-nummerreference

| URI                   | https://data.gov.dk/model/core/orgextension/cvrCodeReference |
| --------------------- | ------------------------------------------------------------ |
| Term                  | cvr code reference                                           |
| Foretrukken term (da) | cvr-nummerreference                                          |
| Foretrukken term (en) | cvr code reference                                           |
| Definition (da)       | reference til objekt der har et cvr-nummer                   |
| Definition (en)       | reference to object that has a cvr code                      |
| Domæne                | rdfs:Resource                                                |
| Udfaldsrum            | xsd:string                                                   |

### p-nummerreference

| URI                   | https://data.gov.dk/model/core/orgextension/pUnitCodeReference |
| --------------------- | -------------------------------------------------------------- |
| Term                  | p-unit code reference                                          |
| Foretrukken term (da) | p-nummerreference                                              |
| Foretrukken term (en) | p-unit code reference                                          |
| Definition (da)       | reference til objekt der har et p-nummer                       |
| Definition (en)       | reference to object that has a p-number                        |
| Domæne                | rdfs:Resource                                                  |
| Udfaldsrum            | xsd:string                                                     |

### myndighedskodereference

| URI                   | https://data.gov.dk/model/core/orgextension/authCodeReference |
| --------------------- | ------------------------------------------------------------- |
| Term                  | authority code reference                                      |
| Foretrukken term (da) | myndighedskodereference                                       |
| Foretrukken term (en) | authority code reference                                      |
| Definition (da)       | reference til objekt der har en myndighedskode                |
| Definition (en)       | reference to object that has an authority code                |
| Domæne                | rdfs:Resource                                                 |
| Udfaldsrum            | xsd:string                                                    |

[^1]: <https://www.w3.org/TR/vocab-org/>
