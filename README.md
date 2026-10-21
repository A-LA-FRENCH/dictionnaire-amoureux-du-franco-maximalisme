# dictionnaire-amoureux-du-franco-maximalisme
Dépôt de code du "Dictionnaire amoureux du franco maximalisme technologique"

# Dictionnaire amoureux du Franco-Maximalisme

> *Le numérique est une idée française, temporairement exploitée par d'autres.*

Bienvenue dans le dépôt officiel, souverain et parfaitement objectif du **Dictionnaire amoureux du Franco-maximalisme** (ou Frenchmaxxisme).

Le Franco-maximalisme consiste à pousser l'art de vivre à la française jusqu'à son point d'incandescence. On y optimise la cuisson de sa baguette, l'affinage de son camembert, la pétillance de son champagne, la consommation éléctrique de son GPU plutôt que son sommeil, on y défend le déjeuner de deux heures comme un droit fondamental universel inaliènable, et l'on y rappelle à chaque occasion que l'ordinateur, la carte à puce et la descente de gradient sont des affaires françaises.

Ce dictionnaire est **amoureux, donc partial, injuste et de mauvaise foi**. Il ne décrit aucun Français réel, seulement celui qui sommeille en chacun de nous entre un café/pain au chocolat et un chocolat au lait/chocolatine.

---

## Sommaire

- [Un seul glossaire, de A à Z](#un-seul-glossaire-de-a-à-z)
- [Organisation du dépôt](#organisation-du-dépôt)
- [La règle d'or](#la-règle-dor)
- [Règles de contribution](#règles-de-contribution)
- [Format d'une entrée](#format-dune-entrée)
- [Ordre alphabétique](#ordre-alphabétique)
- [Typographie française](#typographie-française)
- [Comment contribuer](#comment-contribuer)
- [Messages de commit](#messages-de-commit)
- [Modèle de demande de fusion](#modèle-de-demande-de-fusion)
- [Relecture et validation](#relecture-et-validation)
- [Licence](#licence)

---

## Un seul glossaire, de A à Z

Le dictionnaire tient en **un seul glossaire alphabétique**. Il n'y a ni annexes, ni parties thématiques, ni numérotation.

L'art de vivre et le numérique y cohabitent librement : **Apéro** voisine avec **Apprentissage profond**, **Fromage** avec **Frimousse**, **Réunion** avec **Révolution**. C'est voulu. Pour le franco-maximaliste, la baguette et l'intelligence artificielle relèvent du même génie national.

Le glossaire est encadré par deux textes :

- une **préface**, qui définit le Franco-maximalisme ;
- une **postface**, qui contient le serment du franco-maximaliste.

---

## Organisation du dépôt

```
.
├── README.md
├── LICENSE.md
├── dictionnaire/
│   ├── preface.md
│   ├── A.md
│   ├── B.md
│   ├── C.md
│   ├── …
│   ├── Z.md
│   └── postface.md
└── .github/
    └── merge_request_templates/
        └── Nouvelle_entree.md
```

Un fichier par lettre. Les lettres sans entrée existent quand même, avec un simple titre : elles attendent leur heure, comme une terrasse en février.

Chaque fichier de lettre commence ainsi :

```markdown
# A
```

---

## La règle d'or

> **Les faits sont exacts. Seules les conclusions sont de mauvaise foi.**

C'est tout l'art du franco-maximaliste. Écrire « Gutenberg a mené ses premiers travaux à Strasbourg » est un fait. En conclure que « l'imprimerie est donc alsacienne » est de la mauvaise foi : c'est exactement ce qu'on attend de vous.

En revanche, inventer une date, ou une citation est interdit. Une mauvaise foi bâtie sur un mensonge n'est pas de la mauvaise foi, c'est de la paresse.

---

## Règles de contribution

### Ce qui est attendu

1. **Un fait vérifiable** dès que l'entrée cite une date, une personne, une invention ou une entreprise. La source figure dans la demande de fusion, pas dans le texte.
2. **Une chute.** Chaque entrée se termine par une pointe d'arrogance, d'ironie ou de mauvaise foi assumée.
3. **De la brièveté.** Une à trois phrases. Le franco-maximaliste parle beaucoup, mais il écrit court.
4. **Un français soigné.** Orthographe, accords et typographie française. Les anglicismes ne sont tolérés que pour être corrigés.
5. **Pas de doublon.** Cherchez dans tout le dépôt avant d'ajouter un terme, y compris sous une autre forme (« courriel » et « e-mail », « jeune pousse » et « start-up »).

### Ce qui est refusé

- **Les faits inventés** ou approximatifs présentés comme vrais.
- **Le mépris réel.** On se moque des Français, de notre arrogance et, tendrement, de nos rivaux. On ne rabaisse aucun peuple, aucune origine, aucune religion, aucun groupe. La cible de l'humour est toujours le franco-maximaliste lui-même.
- **Les attaques contre des personnes.** On peut citer des personnalités publiques pour leurs réalisations, jamais pour les ridiculiser ou leur prêter des propos.
- **La politique partisane.** On peut rire de la grève, des réunions et de l'administration ; on ne prend pas parti pour un parti.
- **Le plagiat.** Aucune définition copiée d'un dictionnaire, d'un article ou d'un autre auteur.
- **La vulgarité gratuite.** Un « zut » bien placé vaut mieux qu'un juron.

---

## Format d'une entrée

```markdown
**Terme** (catégorie grammaticale) — Définition ou fait exact. Chute de mauvaise foi. *Voir aussi* Autre terme.
```

- Le terme est en **gras**, sans numéro.
- La catégorie grammaticale est entre parenthèses.
- Un tiret cadratin `—` sépare la catégorie de la définition.
- Le renvoi *Voir aussi* est facultatif et doit pointer vers un terme qui existe déjà.
- Une ligne vide sépare deux entrées.

### Exemples

```markdown
**Bof** (interj.) — Philosophie complète en trois lettres. Exprime à la fois le doute cartésien, la lassitude existentielle et le refus d'un deuxième dessert, qu'on prendra quand même.

**Descente de gradient** (loc.) — Méthode d'optimisation au cœur de tout l'apprentissage profond, décrite par Augustin-Louis Cauchy en 1847. Toute l'IA moderne descend donc, littéralement, d'un mathématicien français.

**Témoin de connexion** (loc.) — Nom officiel du « cookie ». Le franco-maximaliste refuse les cookies par principe : il exige des madeleines, et le souvenir qui va avec. *Voir aussi* Bandeau de consentement.
```

### Anglicismes

Le titre de l'entrée est toujours le **terme français**. L'anglicisme apparaît dans la définition, entre guillemets français : « Le "prompt". » ou « Le « hashtag », enfin rendu à la musique. »

On n'ajoute pas d'entrée au nom de l'anglicisme : **Hashtag** n'existe pas, **Mot-dièse** si.

### Catégories grammaticales admises

| Abréviation | Signification |
| --- | --- |
| `n. m.` | nom masculin |
| `n. f.` | nom féminin |
| `n. m. pl.` / `n. f. pl.` | nom au pluriel |
| `n. m. inv.` | nom invariable |
| `n.` | nom épicène |
| `n. pr.` | nom propre (personne, entreprise, produit, lieu) |
| `adj.` | adjectif |
| `adv.` | adverbe |
| `v. tr.` / `v. intr.` | verbe transitif / intransitif |
| `interj.` | interjection |
| `loc.` | locution |
| `abr.` | abréviation ou sigle |

---

## Ordre alphabétique

Chaque entrée se place dans le fichier de sa lettre, **à sa place alphabétique exacte**. Le tri suit l'usage des dictionnaires français.

| Cas | Règle | Exemple |
| --- | --- | --- |
| Accents | Ignorés au premier tri ; à égalité, la forme sans accent passe d'abord | **Écharpe** se range comme « echarpe », avant **École 42** |
| Ligatures | `œ` se range comme `oe`, `æ` comme `ae` | **Œuvre** se range comme « oeuvre » |
| Espaces, traits d'union, apostrophes | Ignorés | **Café en terrasse** se range comme « cafeenterrasse » |
| Majuscules | Ignorées | **RGPD** se range comme « rgpd » |
| Personnes | Au nom de famille, prénom entre parenthèses | **LeCun (Yann)** à L, **Bellard (Fabrice)** à B |
| Article initial d'un nom propre | Ignoré | **Le Chat** se range à C |
| Chiffres en tête | On range au premier mot écrit en lettres | **École 42** à E |
| Symboles | On range au nom du symbole | « @ » devient **Arobase** à A |

En cas d'hésitation, ouvrez la demande de fusion et signalez-le : un mainteneur tranchera, avec la plus grande mauvaise foi.

---

## Typographie française

Le franco-maximaliste ne transige pas sur la typographie.

- Guillemets français avec espaces : « comme ceci », jamais "comme cela".
- Espace insécable avant `:` `;` `?` `!` et après `«`, avant `»`.
- Tiret cadratin `—` entre la catégorie grammaticale et la définition.
- Majuscules accentuées : « État », « Éducation », jamais « Etat ».
- Ligatures : « œuvre », « cœur ».
- Siècles en chiffres romains : XVIIIe siècle.
- Titres d'œuvres en italique : *Essais*, *Le Petit Prince*.

---

## Comment contribuer

1. **Bifurquez** (« forkez ») le dépôt sur github.
2. **Créez une branche** depuis `main` :
   ```bash
   git checkout -b ajout/nom-du-terme
   ```
   Préfixes de branche : `ajout/`, `correction/`, `style/`, `doc/`.
3. **Ajoutez ou modifiez** les entrées dans le fichier de la bonne lettre, à leur place alphabétique.
4. **Relisez-vous** avec la liste de vérification ci-dessous.
5. **Validez** (« commitez ») selon la convention de messages.
6. **Ouvrez une demande de fusion** (« merge request ») vers `main` avec le modèle `Nouvelle_entree`.

Une demande de fusion contient au maximum **10 entrées**. Au-delà, la relecture devient une réunion, et nul ne veut d'une réunion de plus.

### Liste de vérification avant envoi

- [ ] Le terme n'existe pas déjà dans le glossaire, même sous une autre forme
- [ ] L'entrée est dans le fichier de la bonne lettre, à sa place alphabétique
- [ ] Le format est respecté (gras, catégorie, tiret cadratin, pas de numéro)
- [ ] Chaque fait cité est exact et sourcé dans la demande de fusion
- [ ] La mauvaise foi porte sur les conclusions, pas sur les faits
- [ ] L'entrée ne vise ni un peuple, ni un groupe, ni une personne de façon blessante
- [ ] La typographie française est respectée

---

## Messages de commit

Format :

```
<type> : <terme> (<lettre>)
```

| Type | Usage |
| --- | --- |
| `ajout` | nouvelle entrée |
| `correction` | erreur factuelle ou orthographique |
| `style` | reformulation, chute améliorée, typographie |
| `tri` | entrée déplacée à sa bonne place alphabétique |
| `doc` | modification du README, de la licence ou des modèles |

Exemples :

```
ajout : Pétanque (P)
ajout : Logiciel de traitement de texte (L)
correction : date du brevet de la carte à puce (C)
style : chute de l'entrée Réunion (R)
tri : Écharpe replacée après Débat (E)
```

Les messages de commit s'écrivent en français. Évidemment.

---

## Modèle de demande de fusion

À placer dans `.github/merge_request_templates/Nouvelle_entree.md` :

```markdown
## Entrées proposées

<!-- Collez ici les entrées, au format exact du glossaire -->

## Lettre(s) concernée(s)

<!-- A, B, C… -->

## Sources des faits cités

<!-- Une ligne par fait : le fait, puis le lien vers la source -->
- Fait : …
  Source : …

## Liste de vérification

- [ ] Pas de doublon
- [ ] Bonne lettre, bonne place alphabétique
- [ ] Format respecté, sans numéro
- [ ] Faits exacts et sourcés
- [ ] Mauvaise foi dans les conclusions seulement
- [ ] Aucune moquerie blessante envers un peuple, un groupe ou une personne
- [ ] Typographie française respectée

/label ~"nouvelle entrée"
```

---

## Relecture et validation

Chaque demande de fusion est relue par au moins **un mainteneur**. La relecture porte sur trois points, dans cet ordre :

1. **L'exactitude.** Un fait faux bloque la fusion, quel que soit le talent de la chute.
2. **Le ton.** L'arrogance doit faire sourire, pas blesser.
3. **Le style.** Brièveté, précision, élégance.

Étiquettes utilisées :

| Étiquette | Signification |
| --- | --- |
| `nouvelle entrée` | proposition d'un ou plusieurs termes |
| `à sourcer` | un fait manque de source |
| `à reformuler` | le fond est bon, la forme peut mieux faire |
| `pas assez de mauvaise foi` | la chute manque de panache |
| `mal rangé` | l'entrée n'est pas à sa place alphabétique |
| `doublon` | le terme existe déjà |
| `refusé` | contraire aux règles de contribution |

Les débats en commentaire sont encouragés, à condition de rester courtois. Le franco-maximaliste a le droit d'avoir tort avec éloquence ; il n'a pas le droit d'être désagréable.

---

## Licence

Le projet est publié sous **licence ALF à la French** (Arrogance, Liberté, Fromage), version 1.789 : voir [`LICENSE.md`](LICENSE.md).

Vous pouvez réutiliser, modifier et redistribuer le contenu et le code, à condition de les republier sous la même licence, avec un **Indice de Franco-maximalisme égal ou supérieur**. Toute dilution est interdite.

L'ALF étant une licence humoristique, le projet est également publié sous **double licence** pour garantir un cadre juridique solide : **CC BY-SA 4.0** pour le contenu et **GNU GPL v3** pour le code. En cas de contradiction, ces licences reconnues s'appliquent, et l'ALF reste une exigence morale de la communauté.

En contribuant, vous acceptez que vos entrées soient publiées sous ces licences.

---

*Et si quelqu'un trouve tout cela excessif, nous hausserons les épaules et nous dirons : « Mouais. »*
