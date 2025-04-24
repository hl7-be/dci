# dci
Data Capabilities + Data Innovation
# 🤝 Règles de contribution aux remarques sur les profils FHIR / Richtlijnen voor feedback op FHIR-profielen

Bienvenue dans ce dépôt collaboratif dédié à la collecte de retours sur les **profils FHIR** utilisés ou développés dans différents projets.  
Welkom in deze gezamenlijke repository voor het verzamelen van feedback over gebruikte of ontwikkelde **FHIR-profielen** binnen diverse projecten.

---

## ✅ Objectif / Doelstelling

**FR**  
Ce dépôt sert à :
- Collecter des remarques techniques et métier sur les profils FHIR
- Identifier les points bloquants ou perfectibles
- Favoriser la cohérence et l'interopérabilité entre projets

**NL**  
Deze repository dient om:
- Technische en functionele opmerkingen over FHIR-profielen te verzamelen
- Blokkades of verbeterpunten te identificeren
- Coherentie en interoperabiliteit tussen projecten te bevorderen

---

## 🧭 Règles générales / Algemene regels

**FR**
1. Soyez clair, constructif et respectueux.
2. Ouvrez une *issue* distincte pour chaque remarque.
3. Indiquez toujours :
   - Le **CareSet concerné** (si connu)
   - Le **profil FHIR concerné** (nom et version)
   - Le **contexte d’usage**
   - Une **description précise** du problème ou de la proposition
4. Utilisez les **labels** : `technique`, `métier`, `amélioration`, `bug`, `question`, etc.
5. Ne mettez jamais de données personnelles ou confidentielles.

**NL**  
1. Wees duidelijk, constructief en respectvol.
2. Maak een aparte *issue* per opmerking.
3. Vermeld steeds:
   - De betrokken **CareSet** (indien bekend)
   - Het **FHIR-profiel** (naam en versie)
   - De **gebruikerscontext**
   - Een **duidelijke beschrijving** van het probleem of de suggestie
4. Gebruik **labels** zoals: `technisch`, `functioneel`, `verbetering`, `bug`, `vraag`, enz.
5. Plaats geen persoonlijke of vertrouwelijke gegevens.

---

## 📝 Structure recommandée pour une issue / Aanbevolen structuur voor een issue

```markdown
### CareSet concerné / Betrokken CareSet
`HospitalSummary` (v1.1)

### Profil FHIR concerné / Betrokken FHIR-profiel
`Observation - Vital Signs` (v1.2.0)

### Type de remarque / Type opmerking
Technique / Technisch

### Contexte / Context
Utilisé dans le projet XYZ pour monitorer la saturation.  
Gebruikt in project XYZ om zuurstofsaturatie te monitoren.

### Remarque / Opmerking
Le champ `Observation.component.code` impose un code LOINC, mais nous utilisons un système local.  
Het veld `Observation.component.code` vereist een LOINC-code, maar wij gebruiken een lokaal systeem.

### Impact
Bloquant / Blokkerend

### Proposition / Voorstel
Permettre l'utilisation d'un code alternatif ou documenter une extension.  
Sta gebruik van een alternatief coderingssysteem toe of documenteer een extensie.
```

---

## 📆 Suivi des tickets / Opvolging van tickets

**FR**  
- Une **réunion de suivi** a lieu **chaque vendredi** pour :
  - Revoir les nouvelles issues
  - Prioriser les remarques ouvertes
  - Valider les propositions retenues
- Un **tableau de bord GitHub Projects** sera utilisé pour le suivi avec les colonnes :
  - `À analyser`, `En discussion`, `Décision prise`, `À implémenter`, `Clôturé`

**NL**  
- Er is een **wekelijkse opvolgvergadering op vrijdag** om:
  - Nieuwe issues te bekijken
  - Openstaande opmerkingen te prioriteren
  - Goedgekeurde voorstellen te valideren
- Er wordt een **GitHub Projects-dashboard** gebruikt met de kolommen:
  - `Te analyseren`, `In bespreking`, `Beslist`, `Te implementeren`, `Afgesloten`

---

Merci pour votre contribution ! / Bedankt voor je bijdrage!
