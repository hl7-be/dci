# DCI
Data Capabilities & Innovations
# 🤝 Règles de contribution aux remarques sur les CareSets et les profils FHIR / Richtlijnen voor feedback op CareSets en FHIR-profielen

Bienvenue dans ce dépôt collaboratif dédié à la collecte de retours sur les **CareSets** et les **profils FHIR** utilisés ou développés dans différents projets.  
Welkom in deze gezamenlijke repository voor het verzamelen van feedback over gebruikte of ontwikkelde **CareSets** en **FHIR-profielen** binnen diverse projecten.

---

## ✅ Objectif / Doelstelling

**FR**  
Ce dépôt sert à :
- Collecter des remarques techniques et métier sur les CareSets et les profils FHIR
- Identifier les points bloquants ou perfectibles
- Favoriser la cohérence et l'interopérabilité entre projets

**NL**  
Deze repository dient om:
- Technische en functionele opmerkingen over CareSets en FHIR-profielen te verzamelen
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

## 🆕 Comment créer une issue / Hoe een issue aanmaken

**FR**  
Si vous n'avez jamais utilisé GitHub, pas de panique ! Voici comment soumettre une remarque étape par étape :

1. La première étape est de vous créer un compte utilisateur sur le site GitHub, à l’aide de votre e-mail et en activant la double authentification.
2. Rendez-vous sur la page des remarques du projet :  
   👉 [https://github.com/hl7-be/dci/issues](https://github.com/hl7-be/dci/issues)

3. Cliquez sur le bouton vert **"New issue"** (nouvelle remarque).

4. Remplissez :
   - **Le titre**, en suivant ce format :  
     `[DC ou DI][Abbréviation de votre projet] Résumé de la remarque`  
     *(ex. : `[DI][BSS] Donnée manquante dans Patient`)*  
   - **La description**, en suivant le modèle proposé plus bas ou en copiant-collant l'exemple recommandé.

5. Si vous connaissez le **CareSet** ou le **profil FHIR** concerné, indiquez-les.

6. Cliquez sur **"Submit new issue"** en bas de la page pour envoyer.

C’est tout ! Votre remarque sera analysée lors de la réunion hebdomadaire du vendredi.

**NL**  
Als u GitHub nog nooit heeft gebruikt, geen probleem! Zo dient u stap voor stap feedback in:

1. De eerste stap is het aanmaken van een gebruikersaccount op de GitHub-website. Gebruik hiervoor uw e-mailadres en schakel tweefactorauthenticatie in.
2. Ga naar de opmerkingenpagina van het project:  
   👉 [https://github.com/hl7-be/dci/issues](https://github.com/hl7-be/dci/issues)

3. Klik op de groene knop **"New issue"** (nieuwe opmerking).

4. Vul in:
   - **De titel**, volgens dit formaat:  
     `[DC of DI][Project abbreviatie] Samenvatting van de opmerking`  
     *(bv. : `[DI][BSS] Ontbrekend gegeven in Patient`)*  
   - **De beschrijving**, gebruik het aanbevolen sjabloon hierbeneden of kopieer het voorbeeld.

5. Vermeld indien mogelijk de **CareSet** of het betrokken **FHIR-profiel**.

6. Klik onderaan op **"Submit new issue"** om uw opmerking in te dienen.

Klaar! Uw issue wordt besproken tijdens de wekelijkse vergadering op vrijdag.

---

## 🗂 Contenu des issues et format du titre / Inhoud van issues en titelnotatie

**FR**  
Chaque remarque ou retour doit être formalisé dans une *issue*. 
Le contenu de l'issue doit respecter la structure recommandée ci-dessous.  
**Important :** Le **titre** de l'issue doit commencer par le **type de projet** (`DC` pour Data Capabilities ou `DI` pour Data Innovations), suivi de **l'abréviation du projet**, puis d’un court résumé de la remarque.  
Exemples :
- `[DC][BSS] Extension non reconnue dans Observation`
- `[DI][MONA] Problème d'élément obligatoire dans CareSet XYZ`

Cela permet une meilleure classification et un suivi plus efficace pendant les réunions hebdomadaires.

**NL**  
Elke opmerking of feedback wordt ingediend als een *issue*. 
De inhoud van de issue volgt best de aanbevolen structuur hierbeneden.  
**Belangrijk:** De **titel** van de issue moet beginnen met het **projecttype** (`DC` voor Data Capabilities of `DI` voor Data Innovations), gevolgd door de **afkorting van het project**, en daarna een korte samenvatting van de opmerking.  
Voorbeelden:
- `[DC][BSS] Extensie wordt niet herkend in Observation`
- `[DI][MONA] Verplicht element ontbreekt in CareSet XYZ`

Dit vergemakkelijkt de classificatie en opvolging tijdens de wekelijkse vergaderingen.

---

## 📝 Structure recommandée pour une issue / Aanbevolen structuur voor een issue
**FR**  
Vous pouvez copier l’exemple ci-dessous en cliquant sur l’icône de copie (en haut à droite du bloc), puis le coller dans la description de votre *issue*. Il vous suffit ensuite de modifier le contenu selon votre remarque spécifique.

Merci d'indiquer un maximum de détails et de bien décrire le contexte.

**NL**  
U kunt het onderstaande voorbeeld kopiëren door op het kopieericoontje te klikken (rechtsboven in het blok), en het vervolgens plakken in de beschrijving van uw *issue*. Pas daarna de inhoud aan volgens uw specifieke opmerking.

Geef zoveel mogelijk details en beschrijf de context duidelijk.

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
- Une **réunion de suivi** (avec la présence de BeSafeShare, eHealth Platform et le SPF) a lieu **chaque vendredi** pour :
  - Revoir les nouvelles issues
  - Prioriser les remarques ouvertes
  - Valider les propositions retenues
- Un **tableau de bord GitHub Projects** sera utilisé pour le suivi avec les colonnes :
  - `À analyser`, `En discussion`, `Décision prise`, `À implémenter`, `Clôturé`

**NL**  
- Er is een **wekelijkse opvolgvergadering op vrijdag** (met de aanwezigheid van BeSafeShare, het eHealth-platform en de FOD) om:
  - Nieuwe issues te bekijken
  - Openstaande opmerkingen te prioriteren
  - Goedgekeurde voorstellen te valideren
- Er wordt een **GitHub Projects-dashboard** gebruikt met de kolommen:
  - `Te analyseren`, `In bespreking`, `Beslist`, `Te implementeren`, `Afgesloten`

---

Merci pour votre contribution ! / Bedankt voor je bijdrage!
