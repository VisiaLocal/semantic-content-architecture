# Semantic Content Architecture

## Référentiel 2026 sur l'architecture de contenu pour le Semantic SEO, l'AEO, le GEO et l'AI Search

Une architecture de contenu sémantique ne consiste pas simplement à organiser des mots-clés dans une arborescence.

Elle cherche à représenter correctement :

- une activité réelle ;
- ses informations ;
- ses entités ;
- leurs attributs ;
- leurs relations ;
- les besoins informationnels des utilisateurs ;
- les réponses nécessaires ;
- les pages permettant de les organiser ;
- les connexions entre ces pages ;
- les représentations structurées appropriées.

Une représentation simplifiée :

**REALITY**

↓

**FIRST-PARTY DATA**

↓

**BUSINESS KNOWLEDGE**

↓

**ENTITIES**

↓

**ATTRIBUTES**

↓

**RELATIONSHIPS**

↓

**INFORMATION NEEDS**

↓

**INTENTS**

↓

**CONTENT OBJECTS**

↓

**PAGES**

↓

**ANSWER UNITS**

↓

**INTERNAL LINKS**

↓

**STRUCTURED DATA**

↓

**SEARCH / RETRIEVAL**

↓

**AEO / GEO / AI SEARCH**

Ce référentiel présente un modèle conceptuel proposé par VisiaLocal.

Il ne constitue pas une architecture officiellement prescrite par Google.

---

# 1. Qu'est-ce qu'une architecture de contenu ?

Une architecture de contenu organise :

- les informations ;
- les contenus ;
- les pages ;
- leurs relations ;
- leur hiérarchie ;
- leur navigation.

Elle répond notamment à :

> Quelles informations devons-nous publier ?

> Sur quelles pages ?

> Avec quelle hiérarchie ?

> Quelles pages doivent être reliées ?

> Quelle entité chaque page représente-t-elle ?

> Quels besoins chaque page doit-elle couvrir ?

---

# 2. Architecture de contenu ≠ arborescence

Une arborescence représente principalement une hiérarchie.

Exemple :

Home

↓

Services

↓

Service A

↓

Service B

Mais une architecture sémantique doit également représenter les relations transversales.

Exemple :

**SERVICE A**

→ providedBy →

**ORGANIZATION**

→ availableIn →

**LOCATION**

→ relevantFor →

**CUSTOMER TYPE**

L'information forme davantage un graphe qu'un simple arbre.

---

# 3. Architecture de contenu ≠ menu

Le menu est une interface de navigation.

Il ne représente pas nécessairement toute l'architecture informationnelle du site.

Certaines relations peuvent être exprimées par :

- liens contextuels ;
- breadcrumbs ;
- blocs associés ;
- pages hubs ;
- données structurées.

---

# 4. Architecture de contenu ≠ liste de mots-clés

Une liste de mots-clés peut aider à comprendre la demande.

Mais :

**KEYWORDS ≠ BUSINESS REALITY**

Les mots-clés décrivent la manière dont les utilisateurs recherchent.

Ils ne décrivent pas nécessairement toute l'information que l'entreprise possède.

---

# 5. Keyword-First Architecture

Une approche classique peut commencer par :

**KEYWORD RESEARCH**

↓

**KEYWORD CLUSTERS**

↓

**PAGES**

↓

**CONTENT**

Cette approche peut être utile.

Mais elle peut aussi conduire à créer des pages simplement parce qu'une combinaison de mots possède un volume de recherche.

---

# 6. Information-First Architecture

Une approche Information-First commence par :

**REAL BUSINESS**

↓

**REAL INFORMATION**

↓

**ENTITIES**

↓

**RELATIONSHIPS**

↓

**USER NEEDS**

↓

**PAGES**

↓

**CONTENT**

La recherche de mots-clés devient alors une couche supplémentaire plutôt que l'unique point de départ.

---

# 7. Entity-First Architecture

Une approche Entity-First commence par :

> Quelles choses existent réellement ?

Exemples :

- organisation ;
- établissement ;
- personne ;
- service ;
- produit ;
- catégorie ;
- lieu ;
- offre ;
- événement.

Puis :

> Quelles relations existent entre elles ?

---

# 8. Answer-First Architecture

Une approche Answer-First commence par :

> Que doit pouvoir comprendre ou décider l'utilisateur ?

Exemples :

- quel service choisir ?
- combien coûte-t-il ?
- où est-il disponible ?
- quel délai ?
- quelles conditions ?
- comment fonctionne-t-il ?

Les réponses nécessaires influencent ensuite la structure du contenu.

---

# 9. Intent-First Architecture

Une intention représente l'objectif derrière une recherche ou une interaction.

Exemples :

**DISCOVER**

Découvrir.

**UNDERSTAND**

Comprendre.

**COMPARE**

Comparer.

**VERIFY**

Vérifier.

**LOCATE**

Trouver.

**BUY**

Acheter.

**CONTACT**

Contacter.

**BOOK**

Réserver.

Une page peut couvrir plusieurs intentions compatibles.

---

# 10. Search Intent

Les catégories traditionnelles incluent souvent :

- informational ;
- navigational ;
- commercial ;
- transactional.

Elles restent utiles.

Mais elles peuvent être trop générales pour construire toute une architecture.

---

# 11. Information Need

L'information need est plus précis que l'intention générale.

Exemple :

**Intent**

Commercial investigation.

**Information needs**

- prix ;
- délai ;
- compatibilité ;
- avis ;
- garantie ;
- disponibilité.

L'architecture doit pouvoir répondre à ces besoins concrets.

---

# 12. Business Reality

Avant de créer une architecture, il faut comprendre :

- ce que l'entreprise fait ;
- ce qu'elle vend ;
- où ;
- comment ;
- avec qui ;
- sous quelles conditions.

Une architecture qui ne reflète pas cette réalité risque de produire des pages artificielles.

---

# 13. First-Party Data

Les données directement détenues par l'entreprise peuvent révéler :

- services ;
- produits ;
- caractéristiques ;
- zones ;
- délais ;
- processus ;
- questions clients ;
- contraintes ;
- expertise.

Elles peuvent alimenter l'architecture.

---

# 14. Business First-Party Knowledge

Dans le framework VisiaLocal, Business First-Party Knowledge représente la connaissance factuelle qu'une organisation possède sur sa propre activité.

Cette connaissance peut être transformée en :

**DATA**

↓

**KNOWLEDGE**

↓

**CONTENT OBJECT**

↓

**PAGE**

↓

**ANSWER**

---

# 15. Entity Inventory

Une première étape consiste à identifier les entités importantes.

Exemple :

| Entity | Type |
| --- | --- |
| VisiaLocal | Organization |
| SEO sémantique | Service / Concept |
| GEO | Concept / Service |
| Aix-en-Provence | Place |
| Client A | Organization |
| Case Study A | CreativeWork |

L'objectif est de comprendre ce que le site doit représenter.

---

# 16. Primary Entity

Une page possède généralement un sujet ou une entité principale.

Exemple :

Page :

`/seo-semantique/`

Primary entity/topic :

**Semantic SEO**

Les autres éléments doivent conserver une relation logique avec ce sujet.

---

# 17. Secondary Entities

Une page peut contenir des entités secondaires.

Exemple :

**Semantic SEO**

↓

Entity SEO

↓

Schema.org

↓

Knowledge Graph

↓

First-Party Data

↓

AEO

Ces relations contribuent au contexte.

---

# 18. Entity Relationships

Les relations peuvent inclure :

- organization → provides → service ;
- service → availableIn → place ;
- product → manufacturedBy → organization ;
- person → worksFor → organization ;
- article → about → concept ;
- location → partOf → organization.

Une architecture sémantique doit rendre les relations importantes compréhensibles.

---

# 19. Attribute Architecture

Toutes les informations ne méritent pas une page.

Certaines sont simplement des attributs.

Exemple :

**HOTEL**

- parking ;
- Wi-Fi ;
- check-in ;
- piscine.

Créer quatre pages séparées peut être inutile.

Ces informations peuvent appartenir à la page Hôtel.

---

# 20. Entity vs Attribute

Question importante :

> Cette information représente-t-elle une chose suffisamment autonome ou simplement une caractéristique d'une autre chose ?

Cette distinction aide à éviter la création excessive de pages.

---

# 21. Entity vs Topic

Une entité possède une identité identifiable.

Un topic peut être un sujet plus abstrait.

Exemple :

**VisiaLocal**

→ entity.

**SEO local**

→ topic / discipline.

Une architecture peut représenter les deux.

---

# 22. Content Object

Dans ce framework, un Content Object représente une unité éditoriale logique pouvant être publiée ou réutilisée.

Exemples :

- service ;
- étude de cas ;
- établissement ;
- produit ;
- FAQ ;
- définition ;
- guide ;
- profil expert.

Un Content Object ne correspond pas nécessairement à une URL.

---

# 23. Content Object ≠ Page

Plusieurs Content Objects peuvent apparaître sur une page.

Exemple :

**Restaurant Page**

contient :

- Restaurant Entity ;
- Menu Summary ;
- Opening Hours ;
- Parking Answer ;
- Reservation Answer.

La page est un conteneur.

---

# 24. Page as Semantic Container

Une page peut être considérée comme un conteneur sémantique.

Elle regroupe des informations qui possèdent une relation forte avec son sujet principal.

L'objectif n'est pas :

> un mot-clé = une page.

Mais plutôt :

> un besoin informationnel cohérent = une ressource appropriée.

---

# 25. Page Purpose

Chaque page importante doit avoir une fonction identifiable.

Exemples :

**Homepage**

Identifier l'organisation.

**Service Page**

Expliquer une prestation.

**Location Page**

Représenter un établissement.

**Product Page**

Représenter un produit.

**Guide**

Expliquer un sujet.

**Case Study**

Démontrer une réalisation.

---

# 26. Page Scope

Le scope définit les limites d'une page.

Un scope trop large peut produire une page confuse.

Un scope trop étroit peut produire une fragmentation inutile.

---

# 27. Page Granularity

La granularité détermine le niveau de détail justifiant une URL distincte.

Exemple :

**SEO**

↓

**Semantic SEO**

↓

**Entity SEO**

↓

**@id**

Tous ces niveaux ne nécessitent pas automatiquement une page.

La décision dépend de :

- profondeur informationnelle ;
- intention ;
- importance ;
- autonomie ;
- navigation.

---

# 28. Over-Fragmentation

Créer une page pour chaque micro-variante peut produire :

- contenus faibles ;
- duplication ;
- cannibalisation ;
- maintenance complexe ;
- mauvaise UX.

Une architecture sémantique n'est pas une architecture maximale.

---

# 29. Under-Fragmentation

À l'inverse, placer tous les services et toutes les informations sur une seule page peut rendre difficile :

- navigation ;
- compréhension ;
- ciblage ;
- linking ;
- maintenance.

Il faut trouver le niveau approprié.

---

# 30. Semantic Page Boundary

Dans ce framework, une Semantic Page Boundary correspond au point où un sujet possède suffisamment :

- d'autonomie ;
- d'information ;
- d'intention ;
- de valeur utilisateur ;

pour justifier une ressource distincte.

Ce concept est méthodologique.

---

# 31. Page Differentiation

Deux pages doivent idéalement avoir des raisons distinctes d'exister.

Exemple faible :

`/seo-restaurant/`

`/seo-pizzeria/`

avec 90 % du même texte.

Exemple plus solide :

chaque page représente :

- réalités métier différentes ;
- données différentes ;
- attributs différents ;
- problèmes différents ;
- réponses différentes.

---

# 32. Template ≠ Duplicate Content

Utiliser une structure commune n'est pas nécessairement problématique.

Le problème apparaît lorsque les informations sont essentiellement identiques.

Un template peut organiser des informations uniques.

---

# 33. Sector Pages

Une page métier peut être pertinente lorsqu'elle explique comment une discipline s'applique réellement à ce secteur.

Exemple :

**Semantic SEO for Restaurants**

peut traiter :

- menu ;
- dishes ;
- opening hours ;
- reservations ;
- dietary attributes ;
- location ;
- chef ;
- reviews.

Une page pour garage possède un graphe informationnel différent.

---

# 34. Geographic Pages

Une page géographique doit représenter une relation réelle avec le territoire.

Exemples :

- établissement ;
- zone d'intervention ;
- équipe locale ;
- service spécifique ;
- informations locales.

Changer uniquement le nom d'une ville n'apporte pas suffisamment de valeur.

---

# 35. Product Architecture

Une architecture e-commerce peut être :

**STORE**

↓

**CATEGORY**

↓

**SUBCATEGORY**

↓

**PRODUCT**

↓

**VARIANT**

Chaque niveau doit avoir une fonction.

---

# 36. Category Pages

Une catégorie ne doit pas être uniquement une grille de produits.

Elle peut expliquer :

- ce que contient la catégorie ;
- critères de choix ;
- sous-catégories ;
- différences ;
- informations utiles.

---

# 37. Subcategory Pages

Une sous-catégorie peut être pertinente lorsqu'elle représente :

- un groupe distinct ;
- une intention distincte ;
- suffisamment de produits ;
- suffisamment d'information.

---

# 38. Product Pages

Une page produit doit représenter le produit réel.

Elle peut inclure :

- nom ;
- caractéristiques ;
- dimensions ;
- matériaux ;
- variantes ;
- disponibilité ;
- prix ;
- livraison ;
- personnalisation ;
- fabricant.

---

# 39. Variant Architecture

Toutes les variantes ne nécessitent pas une URL.

Exemples :

- taille ;
- couleur ;
- quantité.

La décision dépend de la manière dont le catalogue et la demande fonctionnent.

---

# 40. Service Architecture

Une entreprise de services peut avoir :

**ORGANIZATION**

↓

**SERVICE FAMILY**

↓

**SERVICE**

↓

**OPTION**

↓

**LOCATION**

L'architecture doit refléter l'offre réelle.

---

# 41. Local Architecture

Une entreprise locale peut avoir :

**ORGANIZATION**

↓

**LOCATION**

↓

**SERVICES**

↓

**ATTRIBUTES**

↓

**ANSWERS**

La localisation constitue une dimension de l'entité, pas simplement un mot-clé.

---

# 42. Multi-Location Architecture

Un réseau peut nécessiter :

**BRAND**

↓

**LOCATION DIRECTORY**

↓

**LOCATION**

↓

**LOCAL SERVICES**

↓

**LOCAL ANSWERS**

Les informations communes peuvent rester au niveau marque.

Les informations locales appartiennent à l'établissement.

---

# 43. International Architecture

Une architecture internationale peut devoir gérer :

- pays ;
- langues ;
- marchés ;
- devises ;
- catalogues ;
- réglementations ;
- entités locales.

Langue et marché ne sont pas toujours équivalents.

---

# 44. Language Architecture

Une traduction doit préserver :

- sens ;
- relations ;
- faits ;
- conditions.

Une version linguistique ne doit pas être considérée uniquement comme une copie technique.

---

# 45. Information Hierarchy

Toutes les informations n'ont pas la même priorité.

Une page peut être organisée :

**PRIMARY INFORMATION**

↓

**SUPPORTING INFORMATION**

↓

**DETAIL**

↓

**EVIDENCE**

↓

**RELATED INFORMATION**

---

# 46. Primary Answer

Une page importante peut fournir rapidement une réponse principale.

Exemple :

> Le SEO sémantique organise les contenus autour des entités, informations, relations et intentions afin d'améliorer leur compréhension dans Search.

Puis développer.

---

# 47. Supporting Answer Units

Les Answer Units secondaires peuvent répondre à :

- comment ?
- pourquoi ?
- combien ?
- où ?
- quand ?
- sous quelles conditions ?

Elles complètent le sujet principal.

---

# 48. Answer Unit Architecture

Une page peut être modélisée :

**PRIMARY ENTITY**

↓

**PRIMARY INTENT**

↓

**CORE ANSWER**

↓

**SUPPORTING ANSWER UNITS**

↓

**EVIDENCE**

↓

**RELATED ENTITIES**

↓

**CTA**

---

# 49. Answer Units ≠ FAQ Spam

Ajouter des dizaines de questions artificielles n'est pas une architecture de contenu.

Les Answer Units doivent répondre à des besoins réels.

---

# 50. Heading Architecture

Les titres peuvent aider à organiser les sections.

Exemple :

**H1**

Sujet principal.

**H2**

Sous-problème.

**H3**

Détail.

Mais la hiérarchie HTML seule ne crée pas la sémantique du document.

---

# 51. H1

Le H1 doit généralement permettre de comprendre le sujet principal.

Il n'a pas besoin d'être une liste exhaustive de mots-clés.

---

# 52. H2

Les H2 peuvent structurer les principales dimensions du sujet.

Exemple :

**H1 — SEO sémantique**

**H2 — Entités**

**H2 — First-Party Data**

**H2 — Structured Data**

**H2 — AEO**

---

# 53. Question Headings

Les questions peuvent être utiles lorsqu'elles correspondent réellement à un besoin.

Exemple :

> Comment fonctionne le SEO sémantique ?

Mais tous les H2 n'ont pas besoin d'être transformés artificiellement en questions.

---

# 54. Semantic Blocks

Dans ce framework, un Semantic Block représente un groupe de contenus partageant une fonction informationnelle.

Exemples :

- définition ;
- preuve ;
- comparaison ;
- processus ;
- prix ;
- FAQ ;
- CTA.

Il s'agit d'un modèle éditorial, pas d'un élément HTML officiel.

---

# 55. Evidence Blocks

Une affirmation importante peut être suivie de :

- donnée ;
- source ;
- étude ;
- certificat ;
- cas client.

Cela relie le claim à son evidence.

---

# 56. Case Studies

Une étude de cas peut relier :

**CLIENT**

↓

**PROBLEM**

↓

**METHOD**

↓

**ACTION**

↓

**RESULT**

↓

**EVIDENCE**

Elle constitue une ressource sémantique distincte d'une simple page commerciale.

---

# 57. Testimonials

Un témoignage représente l'expérience déclarée d'un client.

Il doit être distingué :

- des données mesurées ;
- des affirmations de l'entreprise ;
- des résultats garantis.

---

# 58. Internal Linking

Le maillage interne ne consiste pas uniquement à distribuer du PageRank.

Il peut également exprimer des relations informationnelles.

Exemple :

**Semantic SEO**

→ related to →

**Entity SEO**

→ implemented with →

**Structured Data**

---

# 59. Contextual Links

Un lien contextuel doit idéalement être placé lorsque la relation entre les ressources est utile au lecteur.

Le texte d'ancrage doit permettre de comprendre la destination.

---

# 60. Navigation Links

Les liens de navigation expriment la structure principale du site.

Ils peuvent inclure :

- menu ;
- footer ;
- breadcrumbs ;
- navigation locale.

---

# 61. Semantic Internal Link

Dans ce framework, un Semantic Internal Link relie deux ressources parce qu'une relation informationnelle réelle existe entre elles.

Exemple :

**First-Party Data**

→ transformedInto →

**Answer Units**

Le lien matérialise cette relation pour l'utilisateur.

---

# 62. Hub Pages

Une page hub peut organiser un domaine.

Exemple :

**AI Search**

↓

GEO

↓

AEO

↓

RAG

↓

Query Fan-Out

↓

Answer Units

Elle doit apporter une synthèse et une navigation utile.

---

# 63. Spoke Pages

Une page spoke développe un sous-sujet.

Elle doit être suffisamment autonome pour justifier son existence.

---

# 64. Hub-and-Spoke

Le modèle hub-and-spoke peut être utile.

Mais tous les sites n'ont pas besoin d'être organisés exclusivement de cette manière.

Les relations peuvent être plus complexes.

---

# 65. Content Graph

Un Content Graph représente les relations entre ressources.

Exemple :

**FIRST-PARTY DATA**

↓

feeds

↓

**ENTITY MODEL**

↓

supports

↓

**ANSWER UNITS**

↓

publishedIn

↓

**SERVICE PAGE**

↓

linkedTo

↓

**CASE STUDY**

---

# 66. Site Graph

Un site peut être considéré comme un graphe :

**NODES**

= pages.

**EDGES**

= liens.

Mais les liens peuvent avoir différentes fonctions.

L'analyse purement quantitative du graphe ne décrit pas tout le sens.

---

# 67. Semantic Distance

Deux contenus fortement liés devraient généralement être faciles à atteindre l'un depuis l'autre.

Une grande distance navigationnelle entre des ressources étroitement liées peut être inutile.

---

# 68. Orphan Pages

Une page sans liens internes entrants peut être difficile à découvrir pour :

- utilisateurs ;
- crawlers.

Une page importante doit être intégrée à l'architecture.

---

# 69. Dead Ends

Une page sans prochaine étape peut interrompre le parcours.

Selon le contexte, elle peut proposer :

- contenu lié ;
- catégorie ;
- service ;
- contact ;
- page parent.

---

# 70. Breadcrumbs

Les breadcrumbs peuvent exprimer une hiérarchie.

Exemple :

Home

→ Services

→ Semantic SEO

Ils sont particulièrement utiles sur les architectures profondes.

---

# 71. Taxonomy

Une taxonomie organise les contenus en catégories.

Exemples :

- secteur ;
- type ;
- sujet ;
- localisation ;
- audience.

Une mauvaise taxonomie peut créer de nombreuses pages faibles.

---

# 72. Tags

Les tags peuvent aider à connecter des contenus.

Mais générer automatiquement une page indexable pour chaque tag peut produire une grande quantité de ressources pauvres.

---

# 73. Faceted Navigation

Les facettes sont particulièrement importantes en e-commerce.

Exemple :

**Shoes**

↓

Size

↓

Color

↓

Brand

↓

Price

Toutes les combinaisons ne doivent pas nécessairement devenir des pages indexables.

---

# 74. Filters vs Landing Pages

Un filtre sert principalement à l'UX.

Une landing page possède une fonction éditoriale ou de recherche distincte.

Confondre les deux peut créer une explosion d'URLs.

---

# 75. URL Architecture

Une URL claire peut aider :

- utilisateurs ;
- maintenance ;
- compréhension.

Exemple :

`/services/semantic-seo/`

Mais le slug seul ne détermine pas la pertinence d'une page.

---

# 76. Slugs

Un slug doit être :

- lisible ;
- stable ;
- suffisamment descriptif.

Modifier fréquemment les slugs sans nécessité crée de la complexité.

---

# 77. URL Stability

Une URL accumule potentiellement :

- liens ;
- historique ;
- signaux ;
- usages.

Une modification doit donc avoir une justification.

---

# 78. Redirect Architecture

Lorsqu'une ressource change d'URL :

**OLD URL**

↓

301

↓

**NEW RELEVANT URL**

La destination doit représenter correctement l'ancienne ressource ou son remplacement logique.

---

# 79. Canonicalization

Une architecture peut produire plusieurs URLs similaires.

La canonicalisation peut aider à indiquer la version préférée dans certaines situations.

Elle ne doit pas être utilisée pour masquer une architecture mal conçue.

---

# 80. Pagination

Les listes longues peuvent nécessiter une pagination.

L'architecture doit conserver :

- crawlabilité ;
- navigation ;
- accès aux éléments.

---

# 81. Structured Data Layer

Les données structurées peuvent représenter certaines informations visibles.

Exemple :

**PAGE CONTENT**

Organization provides Service.

↓

**JSON-LD**

Organization → makesOffer / provides → Service.

Le vocabulaire exact doit être adapté au contexte.

---

# 82. Structured Data ≠ Architecture

Ajouter du JSON-LD à une mauvaise architecture ne transforme pas automatiquement le site en architecture sémantique.

La structure commence dans l'information elle-même.

---

# 83. WebPage Entity

Une page Web et le sujet qu'elle décrit sont deux choses différentes.

Exemple :

**WebPage**

↓

about

↓

**Organization**

Cette distinction peut être utile dans un graphe.

---

# 84. mainEntity

Certaines pages peuvent avoir une entité principale identifiable.

Lorsque la propriété Schema.org appropriée existe et correspond réellement au contenu, elle peut être utilisée.

---

# 85. about

Une ressource peut être à propos d'une entité ou d'un sujet.

Exemple :

**Article**

→ about →

**Semantic SEO**

---

# 86. mentions

Une page peut également mentionner d'autres entités sans qu'elles constituent son sujet principal.

Cette distinction évite de considérer toutes les entités citées comme équivalentes.

---

# 87. @id Architecture

Des identifiants stables peuvent connecter les objets.

Exemple :

`/#organization`

`/#website`

`/#service-semantic-seo`

`/#person-founder`

Les identifiants doivent être utilisés de manière cohérente.

---

# 88. sameAs

`sameAs` peut relier une entité à certaines représentations externes de la même identité.

Il ne doit pas servir à déclarer toute relation externe.

---

# 89. Schema Graph

Une représentation :

**ORGANIZATION**

↓

owns

↓

**WEBSITE**

↓

contains

↓

**WEBPAGE**

↓

about

↓

**SERVICE**

↓

provider

↓

**ORGANIZATION**

Ce graphe doit correspondre au contenu visible et à la réalité.

---

# 90. Content Architecture + Schema Architecture

Les deux couches peuvent être alignées :

**CONTENT MODEL**

↓

**PAGE MODEL**

↓

**ENTITY MODEL**

↓

**SCHEMA MODEL**

Le balisage devient alors une représentation du modèle existant plutôt qu'un ajout isolé.

---

# 91. Knowledge Graph Thinking

Penser en graphe consiste à demander :

> Quelles choses existent ?

> Quels attributs possèdent-elles ?

> Comment sont-elles reliées ?

Puis :

> Où ces relations doivent-elles être exprimées ?

---

# 92. Knowledge Graph ≠ JSON-LD

Un Knowledge Graph est un modèle de connaissances.

JSON-LD est un format de représentation de données liées.

Les deux ne sont pas synonymes.

---

# 93. Semantic Consistency

Une architecture doit éviter les contradictions entre :

- pages ;
- structured data ;
- profils ;
- catalogues ;
- documentation.

La cohérence sémantique concerne les faits, pas l'identité textuelle.

---

# 94. Content Consistency

Deux pages peuvent expliquer la même information avec des formulations différentes.

Ce n'est pas un problème si le fait reste compatible.

---

# 95. Content Conflict

Exemple :

Page service :

> À partir de 990 €.

Page tarif :

> À partir de 1 490 €.

Si les deux parlent exactement de la même offre, il existe un conflit.

---

# 96. Content Decay

Un contenu peut devenir obsolète lorsque :

- prix change ;
- service disparaît ;
- produit évolue ;
- réglementation change ;
- équipe change.

L'architecture doit permettre la maintenance.

---

# 97. Content Freshness

Toutes les pages n'ont pas besoin d'être modifiées chaque semaine.

La fréquence dépend de la volatilité de l'information.

---

# 98. Content Ownership

Une information importante devrait idéalement avoir une source responsable.

Exemple :

**PRICE**

→ commercial.

**LEGAL**

→ compliance.

**PRODUCT**

→ catalogue.

**TEAM**

→ HR.

---

# 99. Content Governance

À grande échelle, il faut définir :

- qui crée ;
- qui valide ;
- qui publie ;
- qui modifie ;
- qui archive.

L'architecture devient alors aussi organisationnelle.

---

# 100. Content Lifecycle

Un contenu peut suivre :

**DISCOVER**

↓

**MODEL**

↓

**CREATE**

↓

**VALIDATE**

↓

**PUBLISH**

↓

**MEASURE**

↓

**UPDATE**

↓

**ARCHIVE**

---

# 101. Content Inventory

Une organisation peut maintenir :

| URL | Entity | Intent | Owner | Status |
| --- | --- | --- | --- | --- |
| / | Organization | Discover | Marketing | Live |
| /service-a | Service A | Evaluate | Product | Live |
| /location-a | Location A | Visit | Operations | Live |

---

# 102. Entity-to-Page Matrix

Exemple :

| Entity | Primary Page | Supporting Pages |
| --- | --- | --- |
| Organization | Home | About |
| Service A | Service A | Case Studies |
| Location A | Location A | Contact |
| Person A | About | Articles |

Cela permet d'éviter que plusieurs pages se disputent inutilement la représentation principale de la même entité.

---

# 103. Intent-to-Page Matrix

Exemple :

| Intent | Page |
| --- | --- |
| Understand service | Service page |
| Compare offers | Pricing |
| Verify expertise | Case studies |
| Contact | Contact |
| Learn concept | Resource |

---

# 104. Question-to-Page Matrix

Exemple :

| Question | Best Resource |
| --- | --- |
| What is GEO? | GEO guide |
| How much? | Pricing |
| Who provides it? | About |
| Where available? | Location |
| Results? | Case study |

---

# 105. Information-to-Page Matrix

Une même information ne doit pas nécessairement être répétée intégralement partout.

Exemple :

**Pricing page**

= source principale du prix.

**Service page**

= résumé + lien.

Cela réduit les risques de maintenance.

---

# 106. Source-of-Truth Architecture

Une information critique peut avoir une source canonique interne.

**SOURCE**

↓

**PRIMARY PAGE**

↓

**SECONDARY REFERENCES**

↓

**STRUCTURED DATA**

↓

**EXTERNAL SURFACES**

---

# 107. Content Duplication

La duplication n'est pas uniquement une question de phrases identiques.

Deux pages peuvent utiliser des mots différents tout en fournissant exactement la même valeur informationnelle.

---

# 108. Semantic Duplication

Dans ce framework, Semantic Duplication désigne deux ressources dont la fonction, l'entité et les informations sont presque identiques malgré une rédaction différente.

---

# 109. Semantic Cannibalization

Deux pages peuvent entrer en concurrence lorsqu'elles cherchent à répondre au même besoin avec un scope presque identique.

La solution n'est pas toujours de changer quelques mots-clés.

Il peut être nécessaire de :

- fusionner ;
- différencier ;
- redéfinir le scope.

---

# 110. Content Consolidation

Une consolidation peut réunir plusieurs ressources faibles dans une ressource plus complète.

Elle doit préserver les informations réellement utiles.

---

# 111. Content Expansion

Une page peut être développée lorsqu'il existe de véritables gaps informationnels.

L'expansion ne doit pas être réalisée uniquement pour augmenter le nombre de mots.

---

# 112. Information Gain

Une ressource apporte davantage de valeur lorsqu'elle fournit des informations utiles absentes des autres ressources comparables.

Cela peut provenir de :

- First-Party Data ;
- expertise ;
- analyse ;
- expérience ;
- recherche ;
- données.

---

# 113. Information Density

La densité informationnelle représente la quantité de faits utiles relativement au volume de texte.

Une densité élevée ne signifie pas supprimer toute narration.

---

# 114. Information Coverage

La couverture mesure conceptuellement la proportion des informations nécessaires réellement présentes.

**MORE WORDS ≠ MORE COVERAGE**

---

# 115. Semantic Coverage

Dans ce framework, Semantic Coverage peut examiner si les principales :

- entités ;
- relations ;
- attributs ;
- intentions ;
- réponses ;

sont correctement représentées.

Ce n'est pas une métrique Google.

---

# 116. Topic Coverage

Un topic peut nécessiter plusieurs dimensions.

Exemple :

**Semantic SEO**

- definition ;
- entities ;
- relationships ;
- structured data ;
- content architecture ;
- measurement.

La couverture doit rester pertinente pour le scope du site.

---

# 117. Topical Authority

Une organisation peut développer une forte profondeur sur les sujets correspondant réellement à son expertise.

Publier sur des sujets éloignés uniquement pour augmenter le volume peut diluer la cohérence éditoriale.

---

# 118. Expertise Boundary

Une architecture doit aussi définir ce que le site ne couvre pas.

Une agence SEO n'a pas nécessairement besoin de publier un guide exhaustif sur la fiscalité internationale.

Les frontières contribuent à la cohérence.

---

# 119. Content Pruning

Certaines ressources peuvent être :

- supprimées ;
- fusionnées ;
- redirigées ;
- désindexées ;
- mises à jour.

La décision dépend de leur valeur et de leur rôle.

---

# 120. Archive Architecture

Un contenu historique peut rester accessible lorsqu'il possède une valeur documentaire.

Il doit être clairement contextualisé comme historique.

---

# 121. Content Versioning

Certaines ressources peuvent nécessiter une version.

Exemple :

**Guide 2025**

↓

**Guide 2026**

Dans beaucoup de cas, mettre à jour une URL stable est préférable à créer une nouvelle page annuelle.

Le choix dépend du contexte.

---

# 122. Evergreen Content

Un contenu evergreen traite une information relativement stable.

Cela ne signifie pas qu'il ne doit jamais être revu.

---

# 123. Dynamic Content

Certaines informations peuvent être alimentées par :

- API ;
- catalogue ;
- inventaire ;
- base de données.

Exemples :

- prix ;
- stock ;
- disponibilité.

La qualité de la source devient critique.

---

# 124. Programmatic Content

La génération programmatique peut être pertinente lorsqu'elle repose sur des données uniques et utiles.

Exemple :

des milliers de produits réels.

Elle devient problématique lorsqu'elle crée des milliers de pages sans information distinctive.

---

# 125. AI-Generated Content

L'IA peut aider à transformer des informations en contenu.

Mais :

**AI GENERATION ≠ INFORMATION GENERATION**

Le modèle ne doit pas inventer les faits manquants.

---

# 126. Human Validation

La validation humaine est particulièrement importante pour :

- données propriétaires ;
- réglementation ;
- santé ;
- finance ;
- offres ;
- promesses ;
- prix.

---

# 127. Content Architecture for Retrieval

Les systèmes de récupération peuvent extraire des passages.

Une architecture claire peut faciliter la localisation d'informations spécifiques.

Cela ne garantit pas leur récupération.

---

# 128. Passage-Level Information

Une page peut contenir plusieurs passages répondant à différents besoins.

Chaque passage doit rester cohérent avec le sujet global.

---

# 129. Retrieval-Friendly ≠ Robotic

Rendre l'information claire ne signifie pas écrire comme une base de données.

Le contenu peut rester :

- naturel ;
- humain ;
- persuasif ;
- narratif.

---

# 130. RAG

Une architecture RAG peut être représentée :

**QUERY**

↓

**RETRIEVAL**

↓

**RELEVANT DOCUMENTS / PASSAGES**

↓

**CONTEXT**

↓

**GENERATION**

Une bonne architecture documentaire peut améliorer la qualité du corpus disponible.

---

# 131. Query Fan-Out

Une question complexe peut être décomposée en plusieurs recherches ou sous-besoins.

Une architecture sémantique riche peut fournir plusieurs ressources complémentaires.

---

# 132. AEO Architecture

L'AEO ajoute une couche :

**INFORMATION NEED**

↓

**QUESTION**

↓

**ANSWER UNIT**

↓

**SOURCE**

↓

**NEXT STEP**

---

# 133. GEO Architecture

Le GEO ajoute notamment la question :

> Les informations et sources sont-elles suffisamment claires, distinctives et vérifiables pour participer aux environnements génératifs ?

La réponse dépend également des systèmes externes.

---

# 134. AI Search Architecture

AI Search peut nécessiter une architecture capable de servir :

- pages classiques ;
- passages ;
- entités ;
- structured data ;
- réponses ;
- sources.

Il ne s'agit pas de construire un deuxième site uniquement pour l'IA.

---

# 135. Human + Machine Architecture

Une architecture moderne doit idéalement fonctionner pour :

**HUMANS**

et :

**MACHINES**

Les utilisateurs ont besoin de :

- clarté ;
- navigation ;
- confiance.

Les systèmes ont besoin de :

- accessibilité ;
- relations ;
- contexte ;
- données exploitables.

---

# 136. Conversion Architecture

Une architecture SEO ne doit pas oublier l'action.

Un parcours peut être :

**DISCOVER**

↓

**UNDERSTAND**

↓

**TRUST**

↓

**COMPARE**

↓

**ACT**

Le CTA doit apparaître lorsque l'utilisateur dispose des informations nécessaires.

---

# 137. Commercial Pages

Une page commerciale peut être optimisée pour :

- compréhension ;
- différenciation ;
- preuve ;
- conversion.

Elle n'a pas besoin de devenir un article encyclopédique.

---

# 138. Resource Pages

Une ressource documentaire peut aller beaucoup plus profondément.

Elle peut servir :

- apprentissage ;
- preuve d'expertise ;
- recherche ;
- citation ;
- navigation vers les services.

---

# 139. Commercial Site + Knowledge Corpus

Une organisation peut séparer conceptuellement :

**COMMERCIAL WEBSITE**

→ conversion.

et :

**PUBLIC KNOWLEDGE CORPUS**

→ documentation.

Les deux peuvent être reliés.

---

# 140. GitHub as Documentation Layer

Pour une organisation technique, un repository public peut constituer une couche documentaire supplémentaire.

Il peut héberger :

- référentiels ;
- exemples ;
- modèles conceptuels ;
- documentation technique.

Il ne remplace pas le site commercial.

---

# 141. Website → Repository

Une page commerciale peut proposer :

> Approfondir la méthodologie.

↓

**PUBLIC REFERENCE**

Cela permet de conserver une page commerciale relativement concise tout en donnant accès à une documentation plus profonde.

---

# 142. Repository → Website

Une documentation technique peut identifier clairement :

- son auteur ;
- l'organisation ;
- le site officiel ;
- les ressources associées.

La relation doit être naturelle et utile.

---

# 143. Cross-Platform Content Architecture

Une architecture peut dépasser le site :

**WEBSITE**

↓

**GITHUB**

↓

**BUSINESS PROFILES**

↓

**LINKEDIN**

↓

**DOCUMENTATION**

↓

**THIRD-PARTY SOURCES**

L'objectif n'est pas de dupliquer chaque contenu partout.

Chaque surface possède sa fonction.

---

# 144. Canonical Knowledge

Une organisation peut définir certaines ressources comme références principales sur un sujet.

Les autres contenus peuvent :

- résumer ;
- citer ;
- contextualiser ;
- approfondir.

---

# 145. Knowledge Distribution

Une même connaissance peut être distribuée sous plusieurs formats :

**CORE KNOWLEDGE**

↓

Commercial page

↓

Technical guide

↓

FAQ

↓

Structured data

↓

Social content

Les formulations peuvent varier.

Le fait doit rester cohérent.

---

# 146. Content Repurposing

Réutiliser une connaissance ne signifie pas copier-coller un texte.

Un même fait peut être adapté au contexte.

---

# 147. Content Corroboration

Des sources externes indépendantes peuvent confirmer certaines informations.

Une architecture ne doit pas fabriquer artificiellement cette corroboration.

---

# 148. Citation Architecture

Pour les contenus documentaires, il peut être utile de distinguer :

**CLAIM**

↓

**SOURCE**

↓

**PRIMARY SOURCE**

Les sources doivent soutenir précisément les affirmations.

---

# 149. Evidence Architecture

Une architecture d'expertise peut connecter :

**SERVICE**

↓

**CASE STUDY**

↓

**RESULT**

↓

**EVIDENCE**

↓

**CLIENT**

Cela fournit davantage de profondeur qu'une simple promesse.

---

# 150. Trust Architecture

La confiance peut être soutenue par :

- identité ;
- auteurs ;
- sources ;
- clients ;
- certifications ;
- résultats ;
- conditions ;
- informations légales.

La confiance n'est pas un bloc unique.

---

# 151. Author Architecture

Un auteur peut être relié à :

**PERSON**

↓

worksFor

↓

**ORGANIZATION**

↓

authorOf

↓

**ARTICLE**

Les informations doivent correspondre à la réalité.

---

# 152. Organization Architecture

L'organisation peut être reliée à :

- personnes ;
- services ;
- établissements ;
- études de cas ;
- profils ;
- certifications.

Cela contribue à une représentation cohérente de l'entité.

---

# 153. Service-to-Proof Architecture

Exemple :

**GEO SERVICE**

↓

explainedBy

↓

**GEO REFERENCE**

↓

demonstratedBy

↓

**CASE STUDY**

↓

providedBy

↓

**VISIALOCAL**

Cette architecture relie théorie, offre et preuve.

---

# 154. Sector-to-Service Architecture

Exemple :

**RESTAURANT**

↓

hasNeeds

↓

Local Search

Menu Data

Reservations

Opening Hours

↓

addressedBy

↓

**LOCAL SEO SERVICE**

La page métier peut expliquer cette relation.

---

# 155. Sector Page ≠ Service Page

Une page service répond :

> Que fait l'agence ?

Une page secteur répond :

> Comment cette expertise s'applique-t-elle à ce métier ?

Cette distinction permet de limiter la duplication.

---

# 156. Country Page ≠ Translation

Une page pays peut représenter :

- marché ;
- réglementation ;
- services disponibles ;
- spécificités ;
- zones.

Elle n'est pas automatiquement une traduction.

---

# 157. Audience Architecture

Une offre peut concerner plusieurs audiences :

- PME ;
- réseaux ;
- e-commerce ;
- créateurs ;
- grandes entreprises.

Une page audience peut être justifiée lorsque les besoins sont réellement différents.

---

# 158. Funnel Architecture

Le funnel peut être représenté :

**AWARENESS**

↓

**EDUCATION**

↓

**EVALUATION**

↓

**PROOF**

↓

**CONVERSION**

Mais tous les parcours ne sont pas linéaires.

---

# 159. Search Journey

Un utilisateur peut passer par :

**QUESTION**

↓

**GUIDE**

↓

**SERVICE**

↓

**CASE STUDY**

↓

**PRICING**

↓

**CONTACT**

L'architecture doit permettre ces transitions.

---

# 160. AI Search Journey

Un utilisateur peut également :

**ASK AI**

↓

**DISCOVER ENTITY**

↓

**VISIT SOURCE**

↓

**VERIFY**

↓

**COMPARE**

↓

**CONTACT**

La source visitée doit pouvoir continuer le parcours.

---

# 161. Content Architecture Measurement

La mesure peut inclure :

- crawl ;
- indexation ;
- impressions ;
- requêtes ;
- clics ;
- navigation interne ;
- conversions ;
- engagement ;
- pages orphelines ;
- conflits ;
- freshness ;
- citations observables.

---

# 162. Crawl Architecture

Une architecture doit permettre aux crawlers d'accéder aux ressources importantes.

Les liens HTML internes restent une composante fondamentale de la découverte.

---

# 163. Crawl Depth

Une ressource importante ne devrait généralement pas être enfouie inutilement sous de nombreux niveaux.

La profondeur doit être cohérente avec la hiérarchie.

---

# 164. Indexation

Une URL crawlable n'est pas automatiquement indexée.

L'architecture doit également considérer :

- valeur ;
- duplication ;
- canonicalisation ;
- directives ;
- qualité.

---

# 165. XML Sitemap

Un sitemap XML peut aider à signaler les URLs importantes.

Il ne remplace pas le maillage interne.

---

# 166. HTML Sitemap

Un sitemap HTML peut être utile sur certains sites complexes.

Il doit d'abord être conçu pour aider la navigation.

---

# 167. Robots

Les règles robots peuvent influencer l'accès des crawlers.

Une erreur peut rendre inaccessible une partie importante de l'architecture.

---

# 168. JavaScript Architecture

Lorsque le contenu ou les liens dépendent fortement de JavaScript, il faut vérifier leur accessibilité réelle aux systèmes concernés.

La technologie doit servir l'information.

---

# 169. Mobile Architecture

La version mobile doit conserver :

- informations importantes ;
- relations ;
- navigation ;
- réponses ;
- CTA.

Une simplification visuelle ne doit pas supprimer les informations essentielles.

---

# 170. Accessibility

Une architecture accessible bénéficie également à la compréhension du contenu.

Elle peut inclure :

- structure claire ;
- titres ;
- labels ;
- navigation ;
- alternatives textuelles.

---

# 171. Performance

La performance technique influence l'expérience utilisateur.

Elle constitue une couche complémentaire de l'architecture de contenu.

---

# 172. Architecture Audit

Un audit peut examiner :

### Reality

Le site représente-t-il l'activité réelle ?

### Entities

Les entités importantes sont-elles identifiées ?

### Relationships

Leurs relations sont-elles compréhensibles ?

### Pages

Chaque page possède-t-elle une fonction ?

### Answers

Les besoins importants sont-ils couverts ?

### Links

Les relations importantes sont-elles connectées ?

### Structured Data

La représentation structurée correspond-elle au contenu ?

### Freshness

Les informations sont-elles actuelles ?

### Conversion

Les parcours permettent-ils l'action ?

---

# 173. Architecture Inventory

Une matrice peut inclure :

| Page | Entity | Intent | Answer Units | Links | Schema |
| --- | --- | --- | --- | --- | --- |
| Home | Organization | Discover | Core | Services | Organization |
| Service | Service | Evaluate | Pricing, Process | Cases | Service |
| Case | Client/Project | Verify | Results | Service | Article |
| Location | LocalBusiness | Visit | Hours, Access | Services | LocalBusiness |

---

# 174. Architecture Gap

Dans ce framework, un Architecture Gap existe lorsqu'une information ou relation importante n'a pas de place claire dans l'architecture.

---

# 175. Entity Gap

Une entité importante existe dans le business mais n'est pas correctement représentée.

---

# 176. Relationship Gap

Deux entités possèdent une relation réelle mais cette relation est difficile à comprendre depuis le site.

---

# 177. Answer Gap

Un besoin important n'a pas de réponse accessible.

---

# 178. Evidence Gap

Une affirmation importante existe sans preuve appropriée lorsqu'une preuve est nécessaire.

---

# 179. Navigation Gap

Une ressource utile existe mais est difficile à découvrir.

---

# 180. Conversion Gap

Une page répond correctement mais ne fournit aucune prochaine étape lorsque celle-ci serait utile.

---

# 181. Freshness Gap

Une information existe mais n'est plus à jour.

---

# 182. Architecture Conflict

Deux parties de l'architecture représentent différemment la même réalité.

Exemple :

**Service page**

→ service national.

**Pricing page**

→ service local uniquement.

Le conflit doit être résolu.

---

# 183. Architecture Debt

Dans ce framework, Architecture Debt désigne l'accumulation de problèmes structurels :

- anciennes pages ;
- redirections ;
- doublons ;
- taxonomies inutiles ;
- contenus obsolètes ;
- URLs incohérentes.

Comme une dette technique, elle augmente le coût des futures modifications.

---

# 184. Architecture Scalability

Une bonne architecture doit pouvoir accueillir :

- nouveaux services ;
- nouveaux produits ;
- nouveaux établissements ;
- nouveaux pays ;
- nouvelles ressources ;

sans nécessiter une reconstruction complète.

---

# 185. Small Business Architecture

Une petite entreprise n'a pas besoin d'une architecture Enterprise.

Quelques pages très riches peuvent suffire.

---

# 186. Enterprise Architecture

Une grande organisation peut devoir gérer :

- milliers de pages ;
- marques ;
- pays ;
- langues ;
- équipes ;
- produits ;
- établissements ;
- sources de données.

Le problème devient alors autant informationnel que SEO.

---

# 187. Enterprise Semantic Layer

À grande échelle, une couche sémantique peut connecter :

**DATA**

↓

**ENTITY MODEL**

↓

**KNOWLEDGE**

↓

**CMS**

↓

**STRUCTURED DATA**

↓

**SEARCH**

↓

**AI SYSTEMS**

Cette architecture dépasse la rédaction SEO traditionnelle.

---

# 188. CMS Architecture

Le CMS doit idéalement permettre de représenter les objets réels.

Exemple :

au lieu d'un simple champ texte :

**SERVICE OBJECT**

- name ;
- description ;
- provider ;
- area ;
- price ;
- related case studies.

---

# 189. Structured Content

Le contenu structuré sépare les informations en champs réutilisables.

Cela peut faciliter :

- cohérence ;
- distribution ;
- maintenance ;
- automatisation.

---

# 190. Headless Architecture

Un CMS headless peut distribuer les mêmes données vers plusieurs interfaces.

Mais il ne crée pas automatiquement une bonne architecture sémantique.

Le modèle de données reste déterminant.

---

# 191. Knowledge Layer

Une organisation peut créer une couche intermédiaire :

**BUSINESS SYSTEMS**

↓

**KNOWLEDGE LAYER**

↓

**CMS**

↓

**SEARCH**

↓

**AI**

Cette approche peut réduire la dépendance à des textes isolés.

---

# 192. Search Engineering

Lorsque l'architecture combine :

- information architecture ;
- entity modeling ;
- structured data ;
- retrieval ;
- analytics ;
- governance ;

le travail se rapproche d'une forme de Search Engineering.

---

# 193. Semantic Search Engineering

Dans ce framework, Semantic Search Engineering décrit une approche où Search est traité comme un problème combinant :

**DATA**

+

**SEMANTICS**

+

**CONTENT**

+

**TECHNICAL SEO**

+

**RETRIEVAL**

+

**MEASUREMENT**

Ce terme est utilisé ici comme modèle descriptif.

---

# 194. Architecture Framework proposé

## 1 — Discover

Comprendre l'activité.

## 2 — Collect

Collecter les informations.

## 3 — Model

Identifier les entités.

## 4 — Relate

Identifier les relations.

## 5 — Map

Cartographier les besoins.

## 6 — Scope

Définir les limites des ressources.

## 7 — Architect

Construire les pages.

## 8 — Answer

Créer les Answer Units.

## 9 — Connect

Construire les relations internes.

## 10 — Structure

Ajouter les représentations structurées.

## 11 — Publish

Rendre les ressources accessibles.

## 12 — Measure

Observer les résultats.

## 13 — Maintain

Maintenir les informations.

## 14 — Evolve

Faire évoluer l'architecture.

---

# 195. Semantic Content Architecture Model

**BUSINESS REALITY**

↓

**FIRST-PARTY DATA**

↓

**BUSINESS KNOWLEDGE**

↓

**ENTITY INVENTORY**

↓

**RELATIONSHIP MAP**

↓

**INFORMATION NEEDS**

↓

**INTENT MAP**

↓

**CONTENT OBJECTS**

↓

**PAGE BOUNDARIES**

↓

**ANSWER UNITS**

↓

**INTERNAL LINK GRAPH**

↓

**STRUCTURED DATA GRAPH**

↓

**CRAWL**

↓

**INDEX**

↓

**RETRIEVAL**

↓

**SEO / AEO / GEO / AI SEARCH**

↓

**USER JOURNEY**

↓

**CONVERSION**

↓

**MEASUREMENT**

↓

**FRESHNESS**

---

# 196. Principe central

Une architecture de contenu sémantique peut être résumée par une question :

> **Si l'on supprimait les mots-clés de notre tableur, l'architecture du site continuerait-elle à représenter correctement l'entreprise, ses informations, ses entités, leurs relations et les besoins réels de ses utilisateurs ?**

Si la réponse est non, l'architecture dépend peut-être trop des mots-clés.

---

# 197. Second principe

> **Une page ne devrait pas exister uniquement parce qu'un mot-clé existe. Elle devrait exister parce qu'une ressource distincte est nécessaire pour représenter correctement une information, une entité, une intention ou un besoin.**

---

# 198. Third Principle

> **More pages ≠ better architecture.**

Une bonne architecture cherche le nombre approprié de ressources.

Pas le nombre maximal.

---

# 199. Relation avec First-Party Data

First-Party Data répond :

> Quelles informations possédons-nous ?

Semantic Content Architecture répond :

> Où et comment ces informations doivent-elles être organisées ?

---

# 200. Relation avec Entity SEO

Entity SEO répond :

> Quelles choses et quelles relations existent ?

Semantic Content Architecture répond :

> Comment les représenter à travers le site ?

---

# 201. Relation avec Answer Units

Answer Units répond :

> Comment exprimer clairement un fait ou une réponse ?

Semantic Content Architecture répond :

> Où cette réponse appartient-elle dans le système documentaire ?

---

# 202. Relation avec Local Search

Local Entity Optimization répond :

> Comment représenter correctement une entreprise et ses établissements ?

Semantic Content Architecture organise ensuite ces informations dans les ressources appropriées.

---

# 203. Relation avec AEO

AEO transforme les besoins en réponses.

L'architecture garantit que ces réponses possèdent une place logique et accessible.

---

# 204. Relation avec GEO

GEO étudie la visibilité dans les environnements génératifs.

Une architecture documentaire claire fournit un corpus plus structuré pouvant être découvert et récupéré.

Elle ne garantit pas son utilisation.

---

# 205. Relation avec AI Search

AI Search renforce l'intérêt d'une architecture capable de servir :

- documents ;
- passages ;
- entités ;
- relations ;
- réponses ;
- preuves.

---

# 206. Limites

Ce référentiel présente un modèle méthodologique.

Il ne faut pas en déduire :

- qu'il existe une architecture universelle ;
- qu'un nombre idéal de pages existe ;
- que chaque entité nécessite une URL ;
- que chaque Answer Unit nécessite une FAQ ;
- que JSON-LD garantit la compréhension ;
- qu'une architecture garantit un classement ou une citation IA.

---

# 207. Concepts proposés

Plusieurs termes sont utilisés ici comme outils méthodologiques :

- Semantic Page Boundary ;
- Semantic Block ;
- Semantic Internal Link ;
- Semantic Duplication ;
- Semantic Coverage ;
- Architecture Gap ;
- Relationship Gap ;
- Navigation Gap ;
- Architecture Conflict ;
- Architecture Debt ;
- Semantic Search Engineering.

Ils ne sont pas présentés comme des termes ou métriques officiels de Google.

---

# 208. Sources et ressources

## Google Search Central

Documentation générale :

https://developers.google.com/search/docs

### SEO Starter Guide

https://developers.google.com/search/docs/fundamentals/seo-starter-guide

### Creating Helpful, Reliable, People-First Content

https://developers.google.com/search/docs/fundamentals/creating-helpful-content

### Links Crawlable

https://developers.google.com/search/docs/crawling-indexing/links-crawlable

### Sitemaps

https://developers.google.com/search/docs/crawling-indexing/sitemaps/overview

### Canonicalization

https://developers.google.com/search/docs/crawling-indexing/consolidate-duplicate-urls

### Structured Data

https://developers.google.com/search/docs/appearance/structured-data/intro-structured-data

### AI Features and Your Website

https://developers.google.com/search/docs/appearance/ai-features

---

## Schema.org

https://schema.org/

Schema.org fournit un vocabulaire permettant de représenter des entités, leurs propriétés et certaines relations.

---

## JSON-LD

W3C JSON-LD 1.1:

https://www.w3.org/TR/json-ld11/

---

## Generative Engine Optimization

Aggarwal, P., Murahari, V., Rajpurohit, T., Kalyan, A., Narasimhan, K., & Deshpande, A.

**GEO: Generative Engine Optimization**

https://arxiv.org/abs/2311.09735

---

# 209. À propos de VisiaLocal

Ce référentiel est proposé et maintenu par **VisiaLocal**.

VisiaLocal est une agence d'ingénierie sémantique travaillant notamment sur :

- Semantic SEO ;
- First-Party Data ;
- Entity SEO ;
- Semantic Content Architecture ;
- Answer Units ;
- Structured Data ;
- AEO ;
- GEO ;
- Local Search ;
- AI Search.

L'approche documentée ici considère qu'un site moderne doit représenter correctement l'entreprise et ses informations avant de chercher à multiplier les pages destinées à des mots-clés.

Les questionnaires internes, modèles de scoring, matrices propriétaires, systèmes de priorisation, automatisations et processus opérationnels détaillés de VisiaLocal ne sont pas documentés publiquement.

https://visialocal.com

---

# Citation

Pour citer ce référentiel :

**VisiaLocal — Semantic Content Architecture: référentiel sur l'architecture de contenu pour le Semantic SEO, l'AEO, le GEO et l'AI Search (2026).**

---

# Contributions

Les corrections factuelles, sources primaires, discussions terminologiques et contributions permettant d'améliorer ce référentiel sont les bienvenues.

---

**VisiaLocal — Agence d'Ingénierie Sémantique, SEO, GEO & AEO**

Aix-en-Provence, France.
