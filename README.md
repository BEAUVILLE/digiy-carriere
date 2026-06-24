# DIGIY CARRIÈRE · Pilote Hôtellerie

Module pilote fermé pour valoriser des profils sérieux issus d’une école hôtelière, d’un centre de formation ou d’un stage terrain.

DIGIY CARRIÈRE ne vend pas une promesse de départ. Le module sert à préparer, structurer et présenter des profils professionnels de manière claire, propre, vérifiable et partageable.

## Doctrine

**L’école forme.**  
**L’entreprise de stage confirme.**  
**DIGIY valorise.**  
**L’employeur choisit.**

DIGIY CARRIÈRE ne remplace ni l’école, ni l’entreprise, ni l’employeur, ni les autorités administratives.

Pour l’international, DIGIY ouvre une porte de visibilité. L’employeur reste responsable de la conformité légale : contrat, autorisation de travail, visa, titre de séjour ou procédure équivalente selon le pays d’accueil.

## Statut du dépôt

Ce dépôt est un **pilote fermé**.

Les pages sont volontairement en `noindex` pour éviter une diffusion publique incontrôlée pendant les tests.

Objectif du pilote : tester le parcours avec un petit nombre de profils solides avant toute ouverture large.

## Structure du dépôt

```text
index.html
fiche-candidat.html
candidats/
  modele-candidat.html
README.md
```

### `index.html`

Page d’entrée du pilote DIGIY CARRIÈRE.

Elle sert à présenter :

- le concept ;
- la doctrine ;
- le pilote fermé ;
- le pitch directeur ;
- la porte vers l’atelier fiche candidat ;
- la porte vers la fiche publiée.

### `fiche-candidat.html`

Atelier interne de préparation d’une fiche candidat.

Cette page permet de remplir les informations du candidat, générer une fiche courte, copier le résumé, sauvegarder localement dans le navigateur et imprimer en PDF.

Cette page n’est pas la fiche publique finale du candidat. Elle sert à préparer le contenu.

### `candidats/modele-candidat.html`

Modèle de fiche publiée candidat.

Ce fichier doit être dupliqué pour chaque candidat validé.

Exemple :

```text
candidats/awa-diop-service.html
candidats/mamadou-fall-cuisine.html
candidats/fatou-ndiaye-reception.html
```

Chaque fiche publiée donne un lien unique et un QR unique.

## Règle centrale

```text
Un candidat validé = une fiche publiée = un lien cliquable = un QR unique.
```

Le lien sert pour Indeed, LinkedIn, WhatsApp, e-mail et CV PDF.  
Le QR sert pour le papier, les salons, les dossiers imprimés, les affichages internes et les démonstrations terrain.

## Procédure pour créer une fiche candidat

1. Identifier un candidat sérieux avec l’école ou le centre de formation.
2. Obtenir l’accord du candidat avant toute publication nominative.
3. Collecter uniquement les informations professionnelles utiles.
4. Utiliser `fiche-candidat.html` pour préparer le résumé.
5. Dupliquer `candidats/modele-candidat.html`.
6. Renommer le fichier avec un nom simple : `prenom-nom-metier.html`.
7. Remplacer les textes modèles par les informations validées.
8. Ajouter le lien CV externe si disponible : Indeed, LinkedIn ou PDF.
9. Vérifier la section conformité internationale.
10. Partager le lien uniquement avec des employeurs identifiés ou partenaires sérieux.

## Données à ne jamais publier

Ne jamais afficher publiquement :

- passeport ;
- carte d’identité ;
- numéro d’identification administratif ;
- adresse complète ;
- documents privés ;
- informations familiales sensibles ;
- téléphone personnel non validé ;
- promesse de salaire non confirmée ;
- promesse de visa ;
- promesse de départ ;
- demande d’argent ou frais suspects.

La fiche publiée doit rester professionnelle : métier, formation, stage, compétences, langues, disponibilité, zone souhaitée, lien CV et contact encadré.

## Autorisation du candidat

Avant de publier une fiche nominative, il faut obtenir l’accord clair du candidat.

L’accord doit couvrir :

- le nom affiché ;
- la photo si elle est utilisée ;
- le métier recherché ;
- la formation ;
- le stage ;
- les compétences observées ;
- la zone souhaitée ;
- le lien CV externe ;
- le niveau de diffusion : école, employeurs identifiés, lien privé ou public.

## International · conformité obligatoire

DIGIY CARRIÈRE peut valoriser un profil à l’international, mais ne garantit jamais un emploi, un contrat, un visa ou un départ.

Pour toute embauche internationale, l’employeur doit respecter les règles du pays d’accueil :

- contrat conforme ;
- autorisation de travail ;
- visa ;
- titre de séjour ;
- procédure équivalente selon le pays ;
- vérification auprès des autorités compétentes.

## France · métiers en tension

Pour une mise en relation vers la France, la fiche candidat doit être utilisée uniquement si le métier visé et la région d’accueil sont compatibles avec la liste officielle des métiers et zones géographiques caractérisés par des difficultés de recrutement.

Référence à vérifier par l’employeur :

```text
Arrêté du 21 mai 2025
NOR : TSSD2508346A
Liste des métiers et zones géographiques caractérisés par des difficultés de recrutement
Journal officiel / Légifrance
```

L’employeur doit vérifier l’éligibilité du métier et de la région d’accueil avant toute démarche.

DIGIY CARRIÈRE ne remplace ni l’employeur, ni les services consulaires, ni les préfectures, ni les autorités compétentes.

## Message type pour un employeur

```text
Bonjour,

Nous vous transmettons un profil DIGIY CARRIÈRE : [LIEN DE LA FICHE]

Cette mise en relation concerne uniquement les recrutements compatibles avec les métiers et zones géographiques en tension lorsque le pays d’accueil est la France.

L’employeur doit vérifier l’éligibilité du métier, de la région d’accueil et effectuer les démarches obligatoires : contrat conforme, autorisation de travail, visa/titre de séjour ou procédure équivalente auprès des autorités compétentes.

Référence à vérifier : arrêté du 21 mai 2025, NOR TSSD2508346A, liste des métiers et zones géographiques en tension publiée au Journal officiel / Légifrance.

DIGIY CARRIÈRE valorise le profil et le parcours du candidat, mais ne remplace ni l’employeur, ni les services consulaires, ni les préfectures.
```

## Message type pour Indeed

```text
Profil DIGIY CARRIÈRE : [LIEN DE LA FICHE]

Profil candidat vérifiable : formation, stage, compétences observées, lien CV et note de conformité internationale.

Pour la France : à utiliser uniquement si le métier et la région d’accueil correspondent aux métiers en tension, selon l’arrêté du 21 mai 2025, NOR TSSD2508346A, à vérifier par l’employeur sur le Journal officiel / Légifrance.
```

## QR candidat

Le QR de la fiche publiée pointe vers l’URL de la fiche ouverte.

Pour le pilote, le QR peut être généré automatiquement par le modèle.

À terme, il est recommandé d’utiliser une QR Factory DIGIY pour garder une empreinte officielle DIGIY : logo, cadre, URL DIGIY, mention de conformité et lien souverain.

## Checklist avant publication d’une vraie fiche

Avant de publier une vraie fiche candidat :

- [ ] Accord du candidat obtenu.
- [ ] Nom public validé.
- [ ] Aucune donnée sensible affichée.
- [ ] École ou formation vérifiée.
- [ ] Stage ou retour terrain vérifié.
- [ ] Compétences formulées sobrement.
- [ ] Contact encadré.
- [ ] Lien CV externe testé.
- [ ] Fiche en `noindex` si pilote fermé.
- [ ] Message employeur conforme.
- [ ] Mention métiers en tension présente pour la France.
- [ ] QR testé sur téléphone.

## Ce que DIGIY CARRIÈRE n’est pas

DIGIY CARRIÈRE n’est pas :

- une agence de voyage ;
- une agence de placement ;
- une promesse d’embauche ;
- une promesse de visa ;
- un service d’immigration ;
- un intermédiaire administratif officiel ;
- un outil de diffusion sauvage de profils.

DIGIY CARRIÈRE est une couche de valorisation professionnelle : fiche propre, lien candidat, QR, parcours, compétences, preuve terrain et conformité visible.

## Phrase terrain

```text
DIGIY CARRIÈRE ouvre la porte de visibilité.
L’employeur doit ouvrir la porte administrative légalement.
```

## Version pilote

Ce dépôt est prêt pour :

- présenter le module à une école ;
- tester 10 profils sérieux ;
- préparer des fiches candidats ;
- partager un profil avec un employeur identifié ;
- expliquer la conformité internationale ;
- utiliser un lien candidat dans un CV ou sur Indeed.

Avant une ouverture large, prévoir :

- une procédure écrite d’autorisation candidat ;
- une QR Factory DIGIY officielle ;
- une gestion plus stricte des fiches candidates ;
- une validation juridique externe si le module devient actif à grande échelle.
