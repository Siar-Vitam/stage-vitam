# Stage-eisen — Afstudeerstage BIM, Vitam

> Referentiebestand voor cross-referencing binnen deze repo. Dit document bevat de formele kaders van de stage
> (opdracht, scope, beoordelingscriteria, deadlines) zodat commits, PR's en documentatie hiernaar kunnen verwijzen.
> Status: **levend document** — open punten worden bijgewerkt zodra ze bevestigd zijn (zie sectie 6).

Laatst bijgewerkt: 10 september 2026

---

## 1. Metadata

| | |
|---|---|
| Student | Siar Poyan |
| Opleiding | HBO Business IT & Management (BIM), Avans Hogeschool |
| Organisatie | Vitam |
| Team | BI & Data, onderdeel van IT Development |
| Periode | 31 augustus 2026 – 29 januari 2027 (~20 weken, incl. ~2 weken verlof) |
| Bedrijfsbegeleider | Lex Beekmans — IT Directeur (bij Vitam sinds 01-09-2025) |
| Docentbegeleider | Erik Melsbach — wekelijks 15 min Teams-overleg (vrijdagochtend) |
| Voorganger | Rik van der Ven — eindadviesrapport, 3 juni 2026 |

---

## 2. Opdracht

**Titel:** Datakwaliteit inzichtelijk maken met Power BI binnen Vitam

**Probleemstelling:**
Binnen Vitam zijn datakwaliteitsproblemen binnen het locatie-aanmaakproces nog onvoldoende structureel
inzichtelijk, waardoor afwijkingen, handmatige controles en opvolging door data-eigenaren niet optimaal
worden ondersteund.

**Hoofdvraag:**
Hoe kan Vitam met behulp van een Power BI-dashboard datakwaliteitsproblemen binnen het
locatie-aanmaakproces structureel inzichtelijk maken en de opvolging hiervan ondersteunen?

**Deelvragen:**
1. Welke datakwaliteitsproblemen, business rules en CDE's (Critical Data Elements) zijn relevant?
2. Welke KPI's en criteria uit het Data Quality Framework zijn geschikt?
3. Hoe wordt dit vertaald naar een bruikbaar dashboardontwerp?
   ⚠️ *Spanning: het dashboardontwerp bestaat al (ontworpen door Rik van der Ven) en is gevalideerd —
   mogelijk herformulering van deze deelvraag nodig, nog te bepalen.*
4. Hoe wordt tijdens ontwikkeling getoetst of het dashboard aansluit op de informatiebehoefte?

### Scope

| Onderdeel | Status |
|---|---|
| **Hoofdadvies A** — 54 preventieve business rules van testdata naar productie brengen (via silver model) | ✅ In scope — kerntaak |
| **Vervolgadvies B** — notificaties bij lage datakwaliteit | ❓ Nog te bevestigen |
| **Vervolgadvies C** — starten met verbijzonderingscodes/prijslijsten | ❓ Nog te bevestigen |
| **Vervolgadvies D** — detective rules, rest van startproces | ❌ Buiten scope — belegd bij BI Specialist |

Harde afspraak: **minimaal 80%** van de stagetijd aan hoofdopdracht BI & Data, **maximaal 20%** overige werkzaamheden.

---

## 3. Beoordelingskader (Avans BIM, ATD Informatica)

**Competenties (5):**
1. Planmatig werken
2. Probleemoplossend vermogen / beroepsprestaties — **telt dubbel** in eindcijfer
3. Onderzoekend vermogen
4. Samenwerken & communiceren
5. Professionele houding

**Norm:** cijfer 7. Elke competentie moet **afzonderlijk voldoende** zijn — anders eindcijfer 5,0.

**Rapportage:**
- Eindrapport: max. 10 pagina's
- Onderzoeksverslag: apart document, max. 30 pagina's
  - Onderzoekscomponent: minimaal 2 weken
  - Max. 2x feedbackronde met docentbegeleider
- Portfolio: Melsbach-Mutsaers matrix (bestand × competentie)
- Verantwoording individuele bijdrage: **n.v.t.** (solostage)

**Proces:**
- 3 fasegesprekken + eindpresentatie/zitting
- 4 reflecties (per fasegesprek + einde stage)

**Deadline:** eindportfolio, eindreflectie, verantwoording en beoordelingsadvies bedrijfsbegeleider —
**zondag 10 januari 2027, 23:59** (vóór einde stage op 29 januari 2027).

---

## 4. Stakeholders

| Naam | Rol |
|---|---|
| Lex Beekmans | IT Directeur, bedrijfsbegeleider |
| Auke Koreman | BI Specialist — primaire technische sparringpartner |
| Ralf Martens, Timo van Liempt, Karsten Hermes | Business Analisten |
| Freek Böhm | Manager ICT Operations |
| Marco Strik | ICT projectcoördinator |
| Yorick Groeneveld | IT procesanalist |
| Sandra Verhulst, Daan Everts | ICT servicedesk |
| Bjorn Dekker *(vermoedelijk, te bevestigen)* | Opstartmanager, team Operations Support |
| Britt Ofman | Manager Operations Support (leidinggevende Bjorn Dekker) |
| Jasper Offringa | Implementatiemanager, Operations Support |
| Nancy Berkel, Maria van Tongeren-Baaljens | Planningsmedewerkers, Operations Support |

Organogram: ICT valt onder de CFO, samen met Business Control, Finance en Inkoop.

---

## 5. Bronnen

- Eindadviesrapport Rik van der Ven (3 juni 2026) — bevat het Data Quality Framework met 712 business rules
- Onderzoeksverslag (2 maart 2026) — 5-stappenframework, hoofdvraag en 9 deelvragen van het vooronderzoek
- Goedgekeurde stageaanvraag

---

## 6. Open punten (nog te verifiëren)

- [ ] Toegankelijkheid silver model (momenteel geblokkeerd, reden onbekend)
- [ ] Status aanstelling Data Engineer (was vacant)
- [ ] Inhoudelijke validatie van de 54 productie-rules — staat dit los van de validatiestatus van de overige 658?
- [ ] Keuze Power Query vs. Excel voor de business-rules-laag
- [ ] Welke vervolgadviezen (B en/of C) exact binnen scope vallen
- [ ] Wekelijkse check-in ritme met Lex — bevestigen bij start stage
- [ ] Rol Bjorn Dekker als opstartmanager — bevestigen (onderzoeksverslag noemt meerdere opstartmanagers)
