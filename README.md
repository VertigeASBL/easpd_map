EASPD MAP
=========

Le module Drupal pour la carte de easpd et investt. À l'installation,
il crée automatiquement un content type Country Page, mais ne crée pas
tous les champs nécessaires (TODO). Il faut ajouter à la main un field de
type List(text) avec comme nom machine "easpd_country". Les valeurs
permises pour cette liste sont les suivantes (à copier-coller dans la
définition du champ) :

    albanie|Albania
    allemagne|Germany
    andorre|Andorra
    autriche|Austria
    armenie|Armenia
    azerbaijan|Azerbaijan
    belgique|Belgium
    bielorussie|Belarus
    bosnie|Bosnia
    bulgarie|Bulgaria
    chypre|Cyprus
    croatie|Croatia
    dannemark|Denmark
    espagne|Spain
    estonie|Estonia
    finlande|Finland
    france|France
    grece|Greece
    georgie|Georgia
    hongrie|Hungary
    iceland|Iceland
    ireland|Ireland
    italie|Italy
    lettonie|Latvia
    lituanie|Lithuania
    liechtenstein|Lichtenstein
    luxembourg|Luxembourg
    macedoine|Macedonia
    malte|Malta
    moldavie|Moldova
    monaco|Monaco
    montenegro|Montenegro
    norvege|Norway
    paysBas|Holland
    pologne|Poland
    portugal|Portugal
    republiqueTcheque|Czech Republic
    roumanie|Romania
    russie|Russia
    sanMarino|San Marino
    serbie|Serbia
    slovaquie|Slovakia
    slovenie|Slovenia
    suede|Sweden
    suisse|Switzerland
    turquie|Turkey
    uk|UK
    ukraine|Ukraine

Ensuite, tout est prêt ! Il faut ajouter le contenu des pages de pays
en créant des "Country Page". On utilise le champ "easpd_country" pour
définir à quel pays est liée chacune de ces pages.

La carte est générée automatiquement, et se trouve à l'url "/map".
