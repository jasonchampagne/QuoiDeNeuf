# Nouveautés Python

> **SOMMAIRE**
> + [3.11](#311)
> + [3.10](#310-4-octobre-2021)
> + [3.9](#39-5-octobre-2020)
> + [3.9](#38-14-octobre-2019)
> + [3.7](#37-27-juin-2018)
> + [3.6](#36-23-décembre-2016)
> + [3.5](#35-13-septembre-2015)
> + [3.4](#34-17-mars-2014)
> + [3.3](#33-29-septembre-2012)
> + [3.2](#32-20-février-2011)
> + [3.1](#31-26-juin-2009)
> + [3.0](#30-3-décembre-2008)

---

## 3.11 (6 août 2022)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 654**](https://peps.python.org/pep-0654)|Groupes d'exceptions et instruction `except*`|
|[**PEP 655**](https://peps.python.org/pep-0655)|Marquage des éléments individuels d'un `TypedDict` comme nécessaires ou potentiellement manquants|
|[**PEP 673**](https://peps.python.org/pep-0673)|Nouveau type `Self`|
|[**PEP 675**](https://peps.python.org/pep-0675)|Type de chaîne littérale arbitraire|

## 3.10 (4 octobre 2021)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 597**](https://www.python.org/dev/peps/pep-0597)|Nouvelle option `EncodingWarning` lors de l'ouverture d'un fichier dont l'encodage n'est pas spécifié|
|[**PEP 604**](https://www.python.org/dev/peps/pep-0604)|Simplification de l'écriture d'unions|
|[**PEP 612**](https://www.python.org/dev/peps/pep-0612)|Amélioration du typage pour les décorateurs|
|[**PEP 613**](https://www.python.org/dev/peps/pep-0613)|Alias explicite pour un type de donnée|
|[**PEP 618**](https://www.python.org/dev/peps/pep-0618)|Nouvelle vérification optionnelle de la longueur pour `zip`|
|[**PEP 623**](https://www.python.org/dev/peps/pep-0623)|Suppression de `wstr` dans l'implémentation d'Unicode (`PyUnicodeObject`)|
|[**PEP 624**](https://www.python.org/dev/peps/pep-0624)|Suppression des API d'encodage `Py_UNICODE`|
|[**PEP 626**](https://www.python.org/dev/peps/pep-0626)|Amélioration de la précision sur les numéros de ligne pour le débogage et d'autres outils|
|[**PEP 632**](https://www.python.org/dev/peps/pep-0632)|Dépréciation du module `distutils`|
|[**PEP 634**](https://www.python.org/dev/peps/pep-0634)<br>[**PEP 635**](https://www.python.org/dev/peps/pep-0635/)<br>[**PEP 636**](https://www.python.org/dev/peps/pep-0636/)|Filtrage par motif avec le nouveau mot-clé `match`|
|[**PEP 644**](https://www.python.org/dev/peps/pep-0644)|Nécessité d'OpenSSL 1.1.1 ou une version plus récente|

## 3.9 (5 octobre 2020)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 573**](https://www.python.org/dev/peps/pep-0573)|Accès à l'état du module à partir des méthodes d'extension C|
|[**PEP 584**](https://www.python.org/dev/peps/pep-0584)|Nouvel opérateur d'union (`\|`) pour les dictionnaires|
|[**PEP 585**](https://www.python.org/dev/peps/pep-0585)|Typage générique sur les types natifs|
|[**PEP 593**](https://www.python.org/dev/peps/pep-0593)|Annotation flexible des fonctions et des variables|
|[**PEP 602**](https://www.python.org/dev/peps/pep-0602)|Cycle de publication annuel pour Python|
|[**PEP 614**](https://www.python.org/dev/peps/pep-0614)|Assouplissement des restrictions sur les décorateurs|
|[**PEP 615**](https://www.python.org/dev/peps/pep-0615)|Prise en charge de la base de données des fuseaux horaires de l'IANA dans la bibliothèque standard|
|[**PEP 616**](https://www.python.org/dev/peps/pep-0616)|Nouvelles méthodes (`removeprefix` et `removesuffix`) pour supprimer un préfixe ou un suffixe dans une chaîne|
|[**PEP 617**](https://www.python.org/dev/peps/pep-0617)|Nouvel analyseur PEG pour CPython|

## 3.8 (14 octobre 2019)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 570**](https://www.python.org/dev/peps/pep-0570)|Paramètres spécifiés uniquement par leur position|
|[**PEP 572**](https://www.python.org/dev/peps/pep-0572)|Expressions d'affectation, notamment avec l'ajout du nouveau opérateur `:=`|
|[**PEP 574**](https://www.python.org/dev/peps/pep-0574)|Nouvelle version (5) du protocole `pickle` avec prise en charge des tampons hors-bande|
|[**PEP 578**](https://www.python.org/dev/peps/pep-0578)|Crochet (_hook_) d'audit de l'exécution de Python|
|[**PEP 586**](https://www.python.org/dev/peps/pep-0586)|Nouvelle annotation de type `Literal`|
|[**PEP 587**](https://www.python.org/dev/peps/pep-0587)|Nouvelle API C pour configurer l'initialisation de Python|
|[**PEP 589**](https://www.python.org/dev/peps/pep-0589)|Nouvelle annotation de type `TypedDict`|
|[**PEP 590**](https://www.python.org/dev/peps/pep-0590)|Protocole d'appel rapide pour CPython (`VectorCall`)|
|[**PEP 591**](https://www.python.org/dev/peps/pep-0591)|Nouvelle annotation de type `Final`|

## 3.7 (27 juin 2018)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 539**](https://www.python.org/dev/peps/pep-0539)|Nouvelle API C pour le stockage local des threads en CPython|
|[**PEP 545**](https://www.python.org/dev/peps/pep-0545)|Officialisation des traduction de la documentation en français, japonais et coréen|
|[**PEP 552**](https://www.python.org/dev/peps/pep-0552)|Génération des fichiers `.pyc` basée sur un hash|
|[**PEP 553**](https://www.python.org/dev/peps/pep-0553)|Nnouvelle fonction native `breakpoint()`|
|[**PEP 557**](https://www.python.org/dev/peps/pep-0557)|Nouveau module `dataclasses` pour la création d'une classe de données plus concise|
|[**PEP 560**](https://www.python.org/dev/peps/pep-0560)|Support de base pour le typage des modules et des types génériques|
|[**PEP 562**](https://www.python.org/dev/peps/pep-0562)|Extension de l'accès aux attributs d'un module|
|[**PEP 563**](https://www.python.org/dev/peps/pep-0563)|Évaluation différée des annotations|
|[**PEP 564**](https://www.python.org/dev/peps/pep-0564)|Gestion des nanosecondes pour le module `time`|
|[**PEP 565**](https://www.python.org/dev/peps/pep-0565)|Amélioration de la gestion des APIs obsolètes (`DeprecationWarning`)|
|[**PEP 567**](https://www.python.org/dev/peps/pep-0567)|Variables contextualisées|

## 3.6 (23 décembre 2016)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 468**](https://www.python.org/dev/peps/pep-0468)|Préservation de l'ordre des `**kwargs` dans une fonction|
|[**PEP 487**](https://www.python.org/dev/peps/pep-0487)|Personnalisation simplifiée pour la création des classes|
|[**PEP 495**](https://www.python.org/dev/peps/pep-0495)|Moins d'ambiguïtés pour l'heure locale|
|[**PEP 498**](https://www.python.org/dev/peps/pep-0498)|Nouveau formatage de chaîne (_f-string_)|
|[**PEP 506**](https://www.python.org/dev/peps/pep-0506)|Nouveau module `secrets` à la bibliothèque standard (génération plus sûre de nombres aléatoires)|
|[**PEP 509**](https://www.python.org/dev/peps/pep-0509)|Dictionnaires versionnés|
|[**PEP 515**](https://www.python.org/dev/peps/pep-0515)|Utilisation du tiret du bas (`_`) comme sépérateur des nombres littéraux|
|[**PEP 519**](https://www.python.org/dev/peps/pep-0519)|Nouveau protocole de chemin d'accès aux fichiers|
|[**PEP 520**](https://www.python.org/dev/peps/pep-0520)|Préservation de l'ordre de définition des attributs d'une classe|
|[**PEP 523**](https://www.python.org/dev/peps/pep-0523)|Nouvelle API d'évaluation de trame à CPython|
|[**PEP 524**](https://www.python.org/dev/peps/pep-0524)|La fonction `os.urandom()` devient bloquante sous GNU/Linux|
|[**PEP 525**](https://www.python.org/dev/peps/pep-0525)|Générateurs asynchrones|
|[**PEP 526**](https://www.python.org/dev/peps/pep-0526)|Annotation des variables|
|[**PEP 528**](https://www.python.org/dev/peps/pep-0528)|Utilisation de l'encodage UTF-8 pour la console Windows|
|[**PEP 529**](https://www.python.org/dev/peps/pep-0529)|Utilisation de l'encodage UTF-8 pour les chemins de fichiers sur Windows|
|[**PEP 530**](https://www.python.org/dev/peps/pep-0530)|Liste en compréhension asynchrone|

## 3.5 (13 septembre 2015)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 441**](https://www.python.org/dev/peps/pep-0441)|Amélioration du support des archives ZIP contenant du code Python|
|[**PEP 448**](https://www.python.org/dev/peps/pep-0448)|Généralisation des opérations de séparation (_unpacking_)|
|[**PEP 461**](https://www.python.org/dev/peps/pep-0461)|Nouveau formatage `%` pour les octets et les tableau d'octets (_bytearray_)|
|[**PEP 465**](https://www.python.org/dev/peps/pep-0465)|Nouvel opérateur (`@`) pour la multiplication de matrices|
|[**PEP 471**](https://www.python.org/dev/peps/pep-0471)|Nouvelle fonction rapide de parcours des répertoires : `os.scandir()`|
|[**PEP 475**](https://www.python.org/dev/peps/pep-0475)|Prise en charge de la répétition automatique des appels système interrompus|
|[**PEP 479**](https://www.python.org/dev/peps/pep-0479)|Modification de la gestion de `StopIteration` dans les générateurs|
|[**PEP 484**](https://www.python.org/dev/peps/pep-0484)|Nouvelle norme pour les annotations de type (module `typing`)|
|[**PEP 485**](https://www.python.org/dev/peps/pep-0485)|Nouvelle fonction `math.isclose()` pour tester l'égalité approximative|
|[**PEP 486**](https://www.python.org/dev/peps/pep-0486)|Détection des environnements virtuels pour le lanceur Python de Windows|
|[**PEP 488**](https://www.python.org/dev/peps/pep-0488)|Suppression des fichiers `.pyo`|
|[**PEP 489**](https://www.python.org/dev/peps/pep-0489)|Nouveau mécanisme amélioré pour le chargement des modules d'extension|
|[**PEP 492**](https://www.python.org/dev/peps/pep-0492)|Coroutines utilisant la syntaxe `async` et `await` (module `asyncio`)|

## 3.4 (17 mars 2014)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 428**](https://www.python.org/dev/peps/pep-0428)|Nouvelle API orientée objet (`pathlib`) de manipulation de chemins du système de fichiers|
|[**PEP 435**](https://www.python.org/dev/peps/pep-0435)|Nouvelle implémentation standard de types énumérés (module `enum`)|
|[**PEP 436**](https://www.python.org/dev/peps/pep-0436)|Introspection complète des fonctions et méthodes implémentées en C (_The Argument Clinic DSL_)|
|[**PEP 442**](https://www.python.org/dev/peps/pep-0442)|Amélioration de la sémantique pour la destruction des objets (_safe object finalization_)|
|[**PEP 443**](https://www.python.org/dev/peps/pep-0443)|Nouvel envoi unique (_single-dispatch_) générique pour les fonctions dans `functools`|
|[**PEP 445**](https://www.python.org/dev/peps/pep-0445)|Nouvelle API C pour la configuration d'allocateurs mémoires|
|[**PEP 446**](https://www.python.org/dev/peps/pep-0446)|Les fichiers et sockets nouvellement créés sont marqués comme non héritables par défaut dans les sous-processus|
|[**PEP 450**](https://www.python.org/dev/peps/pep-0450)|Nouveau module `statistics` pour calculer des statistiques provenant de données numériques|
|[**PEP 451**](https://www.python.org/dev/peps/pep-0451)|Nouveau type `ModuleSpec` pour le système d’importation|
|[**PEP 453**](https://www.python.org/dev/peps/pep-0453)|Nouveau module `ensurepip` pour l'installation groupée du gestionnaire de paquets PIP|
|[**PEP 454**](https://www.python.org/dev/peps/pep-0454)|Nouveau module `tracemalloc` pour le traçage des allocations de mémoire|
|[**PEP 456**](https://www.python.org/dev/peps/pep-0456)|Nouvel algorithme de hachage (SipHash) pour les chaînes de caractères et les données binaires|
|[**PEP 3154**](https://www.python.org/dev/peps/pep-3154)|Nouveau protocole de sérialisation pour le module `pickle`|
|[**PEP 3156**](https://www.python.org/dev/peps/pep-3156)|Nouveau module `asyncio` pour les traitements asynchrones|

## 3.3 (29 septembre 2012)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 362**](https://www.python.org/dev/peps/pep-0362)|Nouvelle fonction `inspect.getsignature()` pour lire la signature d'une fonction|
|[**PEP 380**](https://www.python.org/dev/peps/pep-0380)|Nouvelle syntaxe pour déléguer à un sous-générateur (`yield from <expr>`)|
|[**PEP 393**](https://www.python.org/dev/peps/pep-0393)|Optimisation de la représentation des chaînes de caractères|
|[**PEP 397**](https://www.python.org/dev/peps/pep-0397)|Nouveau lanceur Python pour Windows (exécution avec ou sans console)|
|[**PEP 405**](https://www.python.org/dev/peps/pep-0405)|Nouveau module `venv` pour la prise en charge des environnements virtuels|
|[**PEP 409**](https://www.python.org/dev/peps/pep-0409)|Suppression du contexte d'exception|
|[**PEP 412**](https://www.python.org/dev/peps/pep-0412)|Allègement de la consommation mémoire grâce à l'utilisation de dictionnaires d'attributs|
|[**PEP 414**](https://www.python.org/dev/peps/pep-0414)|Écriture explicite d'un littéral Unicode pour faciliter la migration de la version 2.7 vers 3.3|
|[**PEP 418**](https://www.python.org/dev/peps/pep-0418)|Ajout des fonctions `monotonic()`, `perf_counter()` et `process_time()` dans le module `time`|
|[**PEP 420**](https://www.python.org/dev/peps/pep-0420)|La création d'un module Python ne nécessite plus de fichier `__init__.py`|
|[**PEP 3151**](https://www.python.org/dev/peps/pep-3151)|Simplification de la hiérarchie des exceptions liées à l'OS et aux entrées/sorties|
|[**PEP 3155**](https://www.python.org/dev/peps/pep-3155)|Nouvel attribut `__qualname__` (classes et fonctions) qui représente le chemin depuis le module de plus haut niveau jusqu'à leur définition|

## 3.2 (20 février 2011)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 384**](https://www.python.org/dev/peps/pep-0384)|Nouvelle API stable pour obtenir des extensions compatibles sur chaque version de Python à partir de la 3.2|
|[**PEP 389**](https://www.python.org/dev/peps/pep-0389)|Nouveau module `argparse` pour la gestion des arguments et sous-commandes|
|[**PEP 391**](https://www.python.org/dev/peps/pep-0391)|Configuration de la journalisation basée sur des dictionnaires|
|[**PEP 3147**](https://www.python.org/dev/peps/pep-3147)|Mise en cache du _bytecode_ dans des fichiers `.pyc`, eux-mêmes localisés dans un répertoire `__pycache__`|
|[**PEP 3148**](https://www.python.org/dev/peps/pep-3148)|Nouveau module `concurrent.futures` pour la gestion des processus légers (threads) ou des processus|
|[**PEP 3149**](https://www.python.org/dev/peps/pep-3149)|Marquage des fichiers d'extensions `.so`|

## 3.1 (26 juin 2009)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 372**](https://www.python.org/dev/peps/pep-0372/)|Nouveau type `odict` pour la création de dictionnaires ordonnés qui conservent l'ordre d'insertion|
|[**PEP 378**](https://www.python.org/dev/peps/pep-0378/)|Utilisation de `,` comme séparateur de milliers pour un nombre|

## 3.0 (3 décembre 2008)

|RÉFÉRENCE|DESCRIPTION|
|:--:|:--|
|[**PEP 237**](https://www.python.org/dev/peps/pep-0237/)|Renommage du type `long` en `int` pour représenter des entiers|
|[**PEP 238**](https://www.python.org/dev/peps/pep-0238/)|Changement sur l'opérateur de division (`/` : résultat en flottant, `//` : résultat sous forme d'entier)|
|[**PEP 3102**](https://www.python.org/dev/peps/pep-3102/)|Arguments à mot-clé uniquement|
|[**PEP 3104**](https://www.python.org/dev/peps/pep-3104/)|Nouveau mot-clé `nonlocal` pour assigner directement à une variable une portée externe,mais non globale|
|[**PEP 3105**](https://www.python.org/dev/peps/pep-3105/)|L'instruction `print` a été remplacée par une fonction `print()`|
|[**PEP 3107**](https://www.python.org/dev/peps/pep-3107/)|Annotation des fonctions (arguments et valeur de retour)|
|[**PEP 3109**](https://www.python.org/dev/peps/pep-3109/)|Nouveau mot-clé `raise` pour déclencher des exceptions|
|[**PEP 3110**](https://www.python.org/dev/peps/pep-3110/)|Nouveau mot-clé `except` pour capturer une exception déclenchée|
|[**PEP 3113**](https://www.python.org/dev/peps/pep-3113/)|Suppression de la séparation des paramètres d'un tuple|
|[**PEP 3115**](https://www.python.org/dev/peps/pep-3115/)|Nouvelle syntaxe pour les métaclasses (`class C(metaclass=M):`)|
|[**PEP 3138**](https://www.python.org/dev/peps/pep-3138/)|Nouvelle représentation des chaînes de caractères (`repr()` sur celles-ci n'échappe plus les caractères non-ASCII)|
|[**PEP 3120**](https://www.python.org/dev/peps/pep-3120/)|L'encodage par défaut des sources est désormais UTF-8|
|[**PEP 3131**](https://www.python.org/dev/peps/pep-3131/)|Support des lettres non-ASCII comme identifiants|
|[**PEP 3132**](https://www.python.org/dev/peps/pep-3132/)|Séparation étendue d'un itérable|
|[**PEP 3134**](https://www.python.org/dev/peps/pep-3134/)|Enchaînement d'exceptions et traçabilité intégrée|
