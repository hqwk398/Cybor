# Cybor - Patch Notes

Outil hors ligne d'aide à la prise d'audition Salduz 1 pour les victimes d'escroquerie numérique et de cybercriminalité - ZP Boraine, Service Enquête et Recherche.

---

## V1.2a

### Nouveautés
- **Plusieurs modes de paiement dans un même dossier.** Une nouvelle page permet de cocher virement, paiement en ligne, espèces et/ou crypto. Chaque mode a ensuite sa page de détails, et le recall (virement) et la contestation (paiement en ligne) se traitent séparément.
- **Réquisitoire bancaire prérempli.**
  - Le bouton « Réquisitoire » de la page de rapport se débloque quand un virement de moins de 48 h part vers un compte belge, pour au moins 2 500 €.
  - Une fenêtre propose un réquisitoire par compte belge concerné. On peut y vérifier ou corriger la banque, l'IBAN et le montant avant de télécharger le document en .docx.
  - Seules les opérations de moins de 48 h comptent dans le montant, et la période d'historique est calculée automatiquement.
  - Un rappel précise que si la procédure Mule Stop a fonctionné et que l'argent est revenu sur le compte de la victime, le réquisitoire n'est pas utile.
- **Mule Stop Police.**
 - Un bouton « Mule Stop » apparaît dans le rapport quand un virement part vers un compte d’une banque partenaire (liste Febelfin).
 - Il génère le formulaire bilingue prérempli (.docx) par banque : police, victime, PV, IBAN, montant, type de fraude.
 - L’objet du mail s’adapte : « MULE STOP POLICE » ou « CAMERA REQUEST POLICE » si la victime a déjà signalé la fraude à sa banque.
 - « Télécharger et ouvrir Outlook » télécharge le formulaire et ouvre un mail Outlook prérempli (destinataire, objet, texte). Le formulaire doit être joint manuellement.
 - Vos coordonnées sont mémorisées pour les prochaines fois.
- **Nouveau logo.**

### Améliorations
- Le bouton **Recommencer** demande maintenant une confirmation, partout dans l'application.
- Les textes d'audition sont harmonisés en **Q : [question du policier] / R : [réponse de la victime à la première personne]**.
- La relation des faits, l'audition et le PV tiennent compte des modes de paiement combinés, avec le montant total et un résultat par mode.
- Le menu de destination des transactions propose aussi le marchand, le lieu de remise ou le wallet selon les modes cochés.

---

## V1.2

### Types de faits alignés sur CyberAid
- Ajout des 19 infractions de CyberAid, avec leurs intitulés exacts. Elles s'ajoutent à « Escroquerie via internet » et « Escroquerie par téléphone », qui restent en tête de liste (plus courantes).
- Les infractions sont rangées en 4 blocs repliables, tous fermés au départ :
  - Escroqueries et fraudes
  - Piratage, intrusion et vol de données
  - Identité et faux profils
  - Atteintes aux personnes en ligne
- Un bandeau avec le logo CyberAid ouvre le Flowchart en ligne dans le navigateur, pour l'utilisateur qui hésite sur l'infraction.

### Nouvelles infractions
- Ransomware, Hacking / Sabotage, Prise de contrôle de profil ou de boîte mail, Vol de monnaies virtuelles, Vol de systèmes informatiques.
- Phishing, Fraude au service d'assistance / Helpdesk, Fraude aux moyens de paiements, Fraude à la demande d'aide.
- Usurpation d'identité, Faux profils / faux sites.
- Cyberprédation, Cyberharcèlement, Sextorsion, Voyeurisme / sexting.

Chaque infraction a ses champs de saisie adaptés aux faits et ses mesures immédiates. Le parcours financier ne s'ouvre que si la fiche le prévoit.

### Qualification des faits (nouveau Code pénal)
- Une section « Qualification suggérée » apparaît dans le résumé et dans le PV, avec les articles proposés selon les éléments encodés (indicative et à vérifier).

### Fonctionnement
- « Nouvelle intervention » et « Recommencer » ramènent à la page d'accueil et remettent tout à zéro.
### Design
- Refonte visuelle (gradient, etc).

### Corrections
- Accords et tournures dans les récits générés, par exemple « auteur » au lieu d'« escroc » pour les faits de piratage.
- Doubles points d'interrogation dans certaines questions d'audition.
- Détection des fraudes à l'investissement en néerlandais.
- Le rapport affichait « du le » devant une date.

---

## V1.1

- Génération du texte de la relation des faits.
- Plusieurs IBAN pour la victime : il est possible d'encoder plusieurs comptes.
- Langue : sélecteur FR/NL (le néerlandais est désactivé en attendant la traduction).
- Confirmation avant « Nouvelle intervention » : une fenêtre prévient que les données encodées seront effacées.
- Références légales : les articles du Code pénal sont retirés du rapport, sauf article du CICr.

---

## V1.0

- Questionnaire guidé pour la prise d'audition Salduz 1 d'une victime d'escroquerie numérique.
- Génération du rapport d'intervention et du texte d'audition.
- Identification de la banque à partir de l'IBAN belge, avec les mesures d'urgence : Mule Stop, contestation et chargeback.
