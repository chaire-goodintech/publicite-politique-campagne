# Baromètre de la publicité politique

> Au cours de la **campagne électorale 2022**, ce baromètre de la chaire Good in Tech, réalisé par Jules Rostand et Marion Seigneurin, avec la collaboration de Sprint JE et sous la coordination de Christine Balagué, propose une eprésentation graphique des thèmes de campagne les plus cités dans la publicité.

## Présentation

La période de campagne officielle s'est ouverte le 11 mars, avec la publication de la liste officielle des candidats à l'élection présidentielle par le Conseil Constitutionnel. Au cours de cette période, toute communication à caractère de propagande électorale, y compris la publicité en ligne et sur les réseaux sociaux, est formellement interdite (articles L48-1, L52-1, L52-4, L52-8 du Code électoral).  Le débat public continue toutefois d'opposer les acteurs politiques cherchant à imposer leurs discours. Dans ce contexte, ce baromètre donne à voir chaque semaine les thèmes de la campagne sur lesquelles la publicité se concentre.

## Méthodologie

### Introduction

L’étude des thèmes de la campagne repose sur une attention au lexique des candidats et des partis, à leur discours. Cette étude, à laquelle l’histoire et la science politique sont particulièrement attentives, s’ouvre à de nouveaux terrains. Ainsi, de l’entre-deux-guerre aux présidents contemporains, le discours de gauche et de droite a été finement analysé par Damond Mayaffre[@mayaffre_poids_2000; @mayaffre_du_2016]. Avec les outils de la logométrie appuyés de l’intelligence artificielle, celui-ci est même parvenu à produire une prédiction du discours de campagne d’Emmanuel Macron, dans un livre sorti le 6 mai 2021[@mayaffre_macron_2021].

Cette attention au verbe a été porté sur les réseaux sociaux, où la capacité de chacun des acteurs politiques à faire fleurir son discours est devenue essentielle. L’équipe de recherche de l’[Institut des Systèmes Complexes](https://iscpif.fr/), menée par David Chavalarias, porte en particulier cette étude sur Twitter, à travers la publication d’un [baromètre en ligne permettant de suivre l’évolution des termes de la campagne](https://presidentielle2022.politoscope.org/dashboard). Au-delà des seules approches quantitatives, c’est un exercice auquel se livrent également une fois par mois Béatrice Bouniol et Emmanuel Laurentin, respectivement pour le journal [La Croix](https://www.la-croix.com/France/Universite-presidentielle-2022-mots-campagne-2022-01-28-1201197337) et l’émission « [Le temps du débat](https://www.franceculture.fr/emissions/temps-du-debat) » sur France Culture. 

Dans le cadre de cette attention au discours politique, la publicité, source de rétribution et un moyen de diffusion majeur pour les créateurs de contenus publiant sur les plateformes en ligne, joue un rôle central. En se saisissant des capacités d’atteinte et de profilage des utilisateurs des plateformes en ligne, les acteurs politiques et sociaux font usage de techniques de communication extrêmement puissantes, particulièrement critiquées lors des dernières campagnes électorales aux États-Unis[@tucker_online_2020].

En France, la publicité politique est extrêmement encadrée, le Code électoral interdisant l’utilisation de ces plateformes pour la promotion de programmes et de candidats (art. L52-1). La désinformation en ligne a en outre été investie par des associations et des journalistes, et même portée au niveau institutionnel par l’[Observatoire des initiatives de lutte contre la désinformation (ODIL)](https://odil.org/a-propos/). Dans le contexte de la campagne présidentielle de 2022, le collectif [CheckFirst](https://checkfirst.network/), né au début de la pandémie pour lutter contre la désinformation sur la Covid-19, propose une plateforme d’étude des publicutés politiques liées aux candidats : [https://22vlalapub.fr/](https://22vlalapub.fr/). 

Dans ce riche contexte, cette analyse propose de décentrer le regard sur les candidats pour s’intéresser plutôt aux mots de la publicité en ligne, tels qu’ils s’expriment sur les annonces achetées auprès des principales plateformes américaines. En s’inscrivant à la suite des explorations menées en la matière par [https://22vlalapub.fr/](https://22vlalapub.fr/), il s’agit ici d’établir un suivi, au cours de la campagne elle-même, de l’évolution et de la répartition des thématiques sur lesquelles les annonceurs communiquent. L’objectif de cette recherche *in itinere* est de faire connaître les acteurs de la publicité à caractère politique, ainsi que de mieux faire voir les dynamiques de la campagne.

### Sources et méthodes

Cette recherche s’appuie sur les bibliothèques publicitaires de Meta, dont l’[API Ad Library](https://www.facebook.com/ads/library/api) permet une étude approfondie et contrôlée. Google et Snapchat proposent également une API pour accéder à leurs données, mais ne permettent pas d’accéder facilement au contemu même de ces publiictés. Les données publicitaires de TikTok et LinkedIn sont quant à elles accessibles uniquement via une interface graphique. Les publicités politiques étant enfin interdites sur Twitter, suite à la campagne présidentielle américaine, ceux-ci ne sont pas soumis par la loi à la divulgation de leurs publicités.

#### Établissement du corpus

La réalisation de cette recherche passe par la construction d’un corpus de publicités. Pour ce faire, il a été choisi de ne pas se limiter aux catégories proposées par Meta, qui propose elle—même un champ de publicité à caractère politique. Au contraire, le choix a été fait de définir un lexique des mots de la campagne présidentielle, à même de permettre une comparaison entre plateformes et de contrôler la construction de ce corpus. Deux approches distinctes ont été retenues, en traitant d’abord les thèmes de la campagne puis le discours des candidats.

Les thèmes de la campagne constituent le premier corpus d‘analyse. Il s’agit ici d’obtenir une vue générale des publicités à caractère politique, indépendamment des positions de leur auteur. Le lexique choisi pour ce faire repose sur les catégories élaborées par Le Monde, dans le [comparateur des programmes des candidats à la présidentielle de 2022](https://www.lemonde.fr/les-decodeurs/article/2022/02/16/election-presidentielle-2022-comparez-les-programmes-des-principaux-candidats_6113964_4355770.html) réalisé par le service politique et les décodeurs. Ce travail de grande ampleur, [dont les ressorts de la méthodologie sont présentés en ligne](https://www.lemonde.fr/le-monde-et-vous/article/2022/02/18/comparateur-de-programmes-de-la-presidentielle-comment-le-monde-a-t-il-travaille_6114311_6065879.html), a permis d’identifier 120 thèmes sur lesquels le débat se joue entre les candidats. À partir de ces données, gracieusement mises à disposition par Le Monde à la Chaire Good in Tech, une liste de 157 mots-clefs a été établie, permettant d’identifier les points principaux de chacun des thèmes identifiés par Le Monde.

Le second corpus d’étude est celui du lexique de chacun des candidats. Il s’agit ici d’obtenir une vue détaillée des publicités à caractère politique reprenant les formulations, les expressions, les manières de dire des principaux candidats à l’élection présidentielle. Le lexique choisi repose sur l’important travail de l’[observatoire de la présidentielle 2022](https://presidentielle2022.politoscope.org/dashboard) de l’Institut des Systèmes Complexes, proposant, pour chaque thème, quinze termes significatifs du vocabulaire de chacun des candidats. À partir de ces données, une liste de mots-clefs a été établie, permettant de suivre la reprise dans la publicité du discours de chacun des candidats.

#### Collecte et traitement de données

Les données sont collectées par Quentin Michaud, élève-ingénieur à Télécom Sud Paris, dans le cadre d’un partenariat avec [Sprint JE](https://sprint-je.com/). 

La bibliothèque publicitaire de Meta pour les publicités à enjeu social, électoral ou politique en France est accessible à l'adresse : <https://www.facebook.com/ads/library/?active_status=all&ad_type=political_and_issue_ads&country=FR&media_type=all>. Si la recherche manuelle est accessible sans s'inscrire, la requête par [l'API](https://www.facebook.com/ads/library/api/) nécessite de créer un compte de développeur validé par Meta. Il est ensuite nécessaire de créer un projet développeur et de  générer un token pour pouvoir se connecter.

Les requêtes sur l'API permettent d’obtenir, pour chaque liste de mots-clefs soumis, un tableau JSON décrivant l’ensemble des publicités répondant à au moins un de ces termes. Les requêtes pouvant éventuellement renvoyer un accès vers un autre lien de l'API permettant de récupérer la suite des résultats, il peut être nécessaire d'accéder au lien suivant en boucle jusqu'à avoir récupéré l'intégralité des données.

Ces données sont ensuite transformées, afin d’obtenir un format adapté pour le traitement automatisé.

### Analyse de graphe

À partir de ces données, les thèmes et les mots de la campagne sont étudiés à travers une analyse de graphe. Pour chaque plateforme, les nœuds correspondent à un annonceur. Un lien n'est pas une publicité mais, pour deux annonceurs, le fait d’avoir acheté au moins une fois une publicités sur le même thème, c’est-à-dire identifiée dans les données collectées par le même mot-clef.
