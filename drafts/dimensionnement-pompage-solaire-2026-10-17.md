---
meta_title: "Dimensionnement pompage solaire : débit, HMT, panneaux"
meta_description: "Dimensionnement pompage solaire au Maroc : partez du besoin en eau, de la HMT et de l'ensoleillement pour estimer les panneaux avant de demander un devis."
primary_keyword: "dimensionnement pompage solaire"
secondary_keywords: "calcul pompage solaire, hmt pompe solaire, débit pompe solaire, combien de panneaux pour une pompe"
---

# Dimensionner un pompage solaire : débit, hauteur manométrique et nombre de panneaux

Un pompage solaire se dimensionne en trois temps. D'abord le volume d'eau dont vous avez besoin par jour, en mètres cubes. Ensuite la hauteur sur laquelle il faut la monter, qu'on appelle la hauteur manométrique totale, ou HMT. Enfin la puissance de panneaux nécessaire pour fournir cette énergie pendant les heures de soleil.

Le calcul de base tient en une ligne de physique, et vous pouvez le refaire vous-même pour vérifier un devis. Mais le choix exact de la pompe, du variateur et du champ de panneaux revient à un installateur indépendant, qui doit voir le puits ou le forage. Cet article vous donne la logique, pas un plan de montage.

Les chiffres de calcul ci-dessous sont des exemples pour expliquer la méthode. Ils ne sont ni un devis ni une promesse de résultat. Seules les valeurs d'ensoleillement viennent d'une source publiée (PVGIS, outil de la Commission européenne).

## Étape 1 : le besoin en eau par jour

Tout part de l'eau, pas de la pompe. Une erreur courante consiste à demander « une pompe de tant de chevaux » sans avoir chiffré ce qu'on veut arroser ou abreuver.

Posez trois questions :

- Quelle surface ou quel troupeau, et quelle culture ? Les besoins en eau d'une culture varient fortement d'une saison à l'autre.
- Quel jour est le plus exigeant de l'année ? C'est lui qui fixe la taille du système, pas la moyenne.
- Pouvez-vous stocker l'eau dans un bassin ou un réservoir ? Si oui, la pompe n'a pas besoin de couvrir le pic d'un seul coup.

Convertissez le résultat en mètres cubes par jour. Un mètre cube, c'est 1 000 litres. Si votre agronome, votre coopérative ou l'installateur vous donne un besoin en litres, divisez par 1 000.

Le débit disponible dans le puits ou le forage est une limite, pas un objectif. Un puits qui se vide trop vite met la pompe en danger. L'installateur demandera le débit d'essai du forage, s'il existe. Pour les autorisations de prélèvement, adressez-vous à l'agence de bassin hydraulique de votre région : l'installateur vous conseillera aussi sur ce point.

## Étape 2 : la hauteur manométrique totale (HMT)

La HMT est la hauteur équivalente contre laquelle la pompe travaille. Ce n'est pas seulement la profondeur du puits. Elle additionne plusieurs éléments :

- Le niveau de l'eau dans le puits quand la pompe tourne (le niveau dynamique, plus bas que le niveau au repos, dit statique).
- La hauteur entre le sol et le point d'arrivée de l'eau : le haut du bassin, du réservoir ou la bouche d'irrigation.
- Les pertes de charge dans les tuyaux, qui augmentent avec la longueur, le petit diamètre et le débit.
- Si l'eau part sous pression vers un goutte-à-goutte, la pression demandée en bout de ligne s'ajoute aussi.

Deux fermes avec le même forage peuvent avoir des HMT très différentes. L'une remplit un bassin posé au sol à côté du puits, l'autre envoie l'eau cent mètres plus loin sur une pente. La seconde demande plus d'énergie pour le même volume.

Demandez à l'installateur de vous donner par écrit la HMT qu'il a retenue et le détail de ses hypothèses : niveau dynamique, hauteur de refoulement, longueur et diamètre de conduite. Un devis qui annonce seulement « pompe 3 CV » sans HMT ni débit ne permet pas de comparer.

Pour le choix du type de pompe selon la profondeur, voyez notre guide sur [la pompe solaire immergée pour puits ou forage](/blog/pompe-solaire-puits/).

## Étape 3 : de l'eau à l'énergie

Monter de l'eau demande une énergie qui se calcule. Environ 2,7 Wh pour monter 1 m³ d'eau sur 1 m de hauteur. C'est de la physique de base (masse de l'eau, pesanteur, hauteur), pas une donnée commerciale.

L'énergie « hydraulique » utile par jour vaut donc :

**volume (m³) × HMT (m) × 2,7 = énergie en Wh**

Mais la pompe n'est pas parfaite. Le moteur, la pompe et le variateur perdent chacun une part de l'énergie. Le rendement d'ensemble dépend du matériel et c'est l'installateur qui le connaît, d'après les fiches techniques. Dans les exemples ci-dessous, nous prenons 40 % pour l'ensemble, à titre d'exemple, uniquement pour montrer la méthode.

| Donnée | Ce qu'elle veut dire | Qui la fournit |
|---|---|---|
| Besoin en eau (m³/jour) | Volume du jour le plus exigeant | Vous, avec votre agronome ou votre coopérative |
| Débit (m³/h) | Besoin divisé par les heures de pompage | L'installateur, selon l'ensoleillement |
| HMT (m) | Niveau dynamique + hauteur de refoulement + pertes dans les tuyaux | L'installateur, après visite du puits |
| Énergie électrique (kWh/jour) | Énergie hydraulique divisée par le rendement de l'ensemble | Fiches techniques de la pompe et du variateur |
| Champ de panneaux (kWc) | Énergie électrique divisée par la production d'un kWc par jour | Calcul de l'installateur, avec une marge |
| Réservoir (m³) | Stock d'eau qui remplace la batterie | Vous et l'installateur, selon l'usage |

## Étape 4 : combien de panneaux

Pour passer des kWh par jour à des panneaux, il faut savoir ce que produit un kWc de panneaux par jour à l'endroit où vous vous trouvez. PVGIS (v5.3, modèle PVGIS-SARAH3, 2005-2023, avec 14 % de pertes, panneaux inclinés vers le sud) donne ces valeurs par kWc et par jour en moyenne annuelle : Agadir 5,03 kWh, Marrakech 4,81 kWh, Casablanca 4,72 kWh, Rabat 4,67 kWh, Fès 4,66 kWh, Tanger 4,55 kWh. Ce sont des valeurs modélisées, avant l'effet de la poussière. Notre page sur [l'ensoleillement par ville](/blog/ensoleillement-maroc-par-ville/) détaille les mois les plus et les moins productifs. Vous pouvez aussi interroger [l'outil PVGIS](https://re.jrc.ec.europa.eu/pvg_tools/fr/) pour votre commune.

La formule est simple :

**kWc de panneaux = énergie électrique par jour ÷ production d'un kWc par jour**

C'est un minimum. Une pompe reliée directement aux panneaux, sans batterie, ne tourne que quand le soleil est assez fort. Le matin tôt et le soir, la production est faible. L'installateur ajoute donc une marge de puissance de panneaux par rapport à la pompe, pour que celle-ci démarre plus tôt et tienne plus longtemps dans la journée. Demandez-lui quelle marge il applique et pourquoi.

### Exemple 1 : une ferme près de Taroudant

Prenons l'exemple d'une ferme près de Taroudant qui pompe aujourd'hui au butane. Imaginons un besoin de 20 m³ par jour et une HMT de 40 m.

- Énergie hydraulique : 20 × 40 × 2,7 = 2 160 Wh, soit environ 2,2 kWh.
- Avec un rendement d'ensemble de 40 % (exemple) : 2,2 ÷ 0,4 = environ 5,4 kWh d'électricité par jour.
- Avec la valeur PVGIS d'Agadir, la ville la plus proche dans nos données (5,03 kWh par kWc et par jour) : 5,4 ÷ 5,03 = environ 1,1 kWc au minimum.

Un installateur indépendant partira de ce minimum, puis ajoutera de la marge selon son matériel. Ces chiffres illustrent la méthode. Votre ferme aura d'autres valeurs.

### Exemple 2 : une exploitation près de Marrakech

Imaginons une exploitation près de Marrakech avec 60 m³ par jour au plus fort de l'été et une HMT de 25 m.

- Énergie hydraulique : 60 × 25 × 2,7 = 4 050 Wh, soit environ 4,1 kWh.
- Avec 40 % de rendement (exemple) : environ 10,1 kWh d'électricité.
- Avec la moyenne PVGIS de Marrakech (4,81) : 10,1 ÷ 4,81 = environ 2,1 kWc.
- Avec novembre, le mois le plus faible (4,41) : 10,1 ÷ 4,41 = environ 2,3 kWc.

Le piège est de partir de la moyenne de l'année. Regardez le mois où le besoin est le plus fort, et vérifiez la production de ce mois-là, surtout si vous arrosez aussi en hiver.

## Réservoir ou batterie : où stocker

Une pompe solaire classique ne stocke pas d'électricité. Elle stocke de l'eau. Un bassin ou un réservoir rempli pendant les heures de soleil vous donne de l'eau la nuit et par temps couvert, sans batterie à remplacer.

Cela évite d'acheter et de remplacer des batteries. Le volume utile à prévoir dépend de votre usage : un jour d'eau pour un troupeau, plus pour une culture qui supporte mal un arrêt. L'installateur vous proposera un volume, vous pouvez en discuter selon votre rythme d'arrosage.

La batterie garde un sens dans un cas précis : quand la pompe doit tourner à la demande, la nuit, sans réservoir possible. Vous aurez alors une installation plus chère et plus compliquée, qu'il faut justifier ligne par ligne sur le devis. Pour comprendre ce que fait chaque élément, lisez aussi notre article sur [le variateur solaire pour pompe](/blog/variateur-pompe-solaire/).

## Remplacer le butane, le diesel ou un groupe électrogène

Si vous payez aujourd'hui du carburant pour pomper, comparer demande de poser les deux options côte à côte, sur la même base : même volume d'eau, même HMT. Notre article sur [le groupe électrogène ou l'installation solaire](/blog/groupe-electrogene-ou-solaire/) détaille cette comparaison.

Nous ne chiffrons pas d'économie ici : aucun prix de carburant ni de pompe n'est vérifié sur ce site. Demandez à l'installateur de vous présenter son devis en détail, avec le matériel exact, ce qu'il compte pour la pose, et de vous laisser le comparer à ce que vous dépensez aujourd'hui.

Sur les aides, aucun programme de subvention au pompage solaire n'est confirmé dans nos sources. Notre guide sur [la subvention pompage solaire](/blog/subvention-pompage-solaire/) explique comment vérifier auprès des organismes concernés avant de vous engager sur un montage financier.

## Ce que le devis doit préciser

Quand vous recevez un devis de pompage solaire, vérifiez que ces lignes y figurent :

- Le besoin en eau retenu, en m³ par jour, et le mois pour lequel il est calculé.
- La HMT, avec le niveau dynamique, la hauteur de refoulement et les pertes de charge.
- Le débit de la pompe à la HMT retenue, pas seulement sa puissance en CV ou en kW.
- La puissance des panneaux en kWc, le nombre de panneaux et leur modèle exact.
- La marque et le modèle du variateur ou du contrôleur.
- Ce que la pose comprend : support des panneaux, protections, mise en service, et qui s'occupe des démarches.
- La garantie de chaque élément, séparément : pompe, variateur, panneaux.
- Si le montant est HT ou TTC, et l'échéancier de paiement.

La méthode pour [comparer deux ou trois devis ligne par ligne](/blog/devis-panneaux-solaires/) s'applique aussi au pompage. L'AMEE, l'agence nationale de l'efficacité énergétique, présente sur son site un volet TaqaPro consacré au pompage solaire. Le label est volontaire : demandez à l'entreprise si elle en dispose et vérifiez l'[annuaire TaqaPro](https://taqapro.amee.ma/entreprises-labellisees/). Pour les autres questions à poser avant de signer, voyez [comment choisir un installateur](/blog/choisir-installateur-panneaux-solaires/).

Quand votre besoin en eau, votre HMT et votre surface sont notés, [le formulaire](/#contact) vous permet de demander un devis écrit à un installateur indépendant. Vous pouvez aussi appeler [le +212 5 22 00 00 00](tel:+212522000000) pour être mis en contact avec un installateur indépendant qui visitera votre puits et établira son devis avec vous directement.

Si vous voulez d'abord une vue d'ensemble du sujet, la page [pompage solaire](/pompage-solaire/) présente les cas d'usage. Notez que ce site ne pose pas de pompe lui-même : c'est l'installateur indépendant qui chiffre et qui pose.

## Questions fréquentes

### Combien de panneaux faut-il pour une pompe solaire ?

Cela dépend du volume d'eau, de la HMT, du rendement du matériel et de votre ville. La méthode est : énergie hydraulique par jour (m³ × HMT × 2,7 Wh), divisée par le rendement de l'ensemble, puis divisée par la production d'un kWc par jour dans votre région. L'installateur ajoute ensuite une marge. Demandez-lui le calcul écrit, pas seulement un nombre de panneaux.

### Quelle différence entre le débit et la HMT d'une pompe solaire ?

Le débit est le volume d'eau que la pompe fournit par heure, en m³/h. La HMT est la hauteur totale contre laquelle elle pousse cette eau, pertes dans les tuyaux comprises. Une pompe donne un débit différent selon la HMT : plus la hauteur augmente, plus le débit baisse. Un devis sérieux indique donc le débit à la HMT de votre installation.

### Faut-il une batterie pour un pompage solaire ?

Non, dans la plupart des cas. On stocke l'eau dans un bassin ou un réservoir pendant la journée plutôt que l'électricité dans des batteries. La batterie ne se justifie que si la pompe doit fonctionner la nuit et qu'aucun réservoir n'est possible. Dans ce cas, demandez au devis de détailler le modèle et la capacité retenus.

### Puis-je calculer et monter l'installation moi-même ?

Vous pouvez refaire le calcul pour vérifier un devis, c'est l'objet de cet article. Le raccordement des panneaux, du variateur et de la pompe relève d'un installateur ou d'un électricien qualifié. Ce site ne donne pas d'instructions de câblage. Demandez à l'installateur de visiter le puits avant d'établir son devis.
