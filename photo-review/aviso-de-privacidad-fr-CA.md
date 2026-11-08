---
layout: page
title: Avis de confidentialité complet de Photo Review
permalink: /photo-review/aviso-de-privacidad-fr-CA.html
lang: fr-CA
---

**Date d’entrée en vigueur :** 8 octobre 2026

## 1. Portée de l’avis

Le présent avis explique quels renseignements Photo Review traite, à quelles fins, où ils sont conservés, quand des fournisseurs comme Apple ou Google interviennent et quels choix s’offrent à l’utilisateur. Il couvre l’utilisation de l’application sous iOS, notamment les autorisations de Photos, la révision des éléments, la liste d’éléments en attente, la publicité intégrée et les achats d’abonnements.

L’avis ne remplace pas les avis de confidentialité d’Apple, de Google, des annonceurs ni des sites externes ouverts à partir d’une publicité. Chaque fournisseur est responsable de ses propres pratiques de confidentialité.

## 2. Renseignements liés à la photothèque

Photo Review utilise PhotoKit, le cadre logiciel d’iOS permettant de consulter et de modifier la photothèque, uniquement après que l’utilisateur a accordé l’autorisation demandée par iOS. Selon l’autorisation accordée, l’application peut consulter les photos et les vidéos disponibles, les catégories intelligentes — par exemple les favoris, les éléments récents, les vidéos, les captures d’écran, les égoportraits et les autres groupes offerts par Photos — et, avec un accès complet, les albums créés par l’utilisateur.

Pour afficher et trier les éléments, l’application peut utiliser sur l’appareil :

- L’identifiant local qu’iOS attribue à chaque élément de Photos.
- Le type de média — image ou vidéo — et la date de création fournie par Photos.
- L’identifiant et le nom d’une catégorie ou d’un album.
- Une vignette fournie par PhotoKit pour représenter la photo ou la vidéo à l’écran.

L’application traite ces renseignements pour constituer les catégories, afficher les cartes, mémoriser la progression et exécuter les décisions de conservation ou de suppression. La version décrite dans le présent avis ne comprend ni reconnaissance faciale, ni identification de personnes, ni reconnaissance optique de caractères (OCR), ni recherche selon le contenu des images.

**Les photos, les vidéos et leurs vignettes ne sont pas téléversées vers des serveurs de Photo Review ni jointes aux demandes publicitaires effectuées par l’application.** Le code examiné n’utilise aucun serveur propre, compte d’utilisateur ou service dorsal pour stocker le contenu de la photothèque.

Si une photo ou une vidéo est optimisée dans iCloud et que le système doit la récupérer pour l’afficher, PhotoKit peut la demander aux services Apple/iCloud selon les réglages de Photos et d’iCloud de l’utilisateur. Ce transfert est géré par le système d’exploitation et Apple; il ne constitue pas un téléversement du contenu vers des serveurs du Responsable.

Les photos peuvent contenir des renseignements que l’utilisateur considère comme privés ou sensibles. Photo Review n’extrait ni ne classe intentionnellement les visages, la localisation ou d’autres attributs sensibles à des fins publicitaires ou de profilage. L’utilisateur contrôle les éléments auxquels l’application peut accéder au moyen de l’autorisation de Photos d’iOS.

## 3. Autorisations de Photos et contrôle de l’utilisateur

L’application demande l’autorisation de lire et de modifier la photothèque lorsque cela est nécessaire pour afficher les éléments et permettre une suppression confirmée. iOS peut accorder un accès complet, un accès limité aux éléments sélectionnés ou refuser l’accès. Avec un accès limité, Photo Review peut seulement utiliser les éléments qu’iOS lui permet de voir; certaines catégories ou certains albums peuvent être indisponibles.

L’utilisateur peut modifier ou révoquer l’autorisation dans **Réglages d’iOS > Confidentialité et sécurité > Photos > Photo Review**. Lorsque l’accès est révoqué, les catégories et les cartes qui dépendent de la photothèque peuvent ne plus être disponibles.

Marquer un élément au moyen du geste ou du bouton de suppression **ne le supprime pas immédiatement**. L’application conserve son identifiant dans la liste locale d’éléments en attente, où la marque peut être annulée. La modification de la photothèque est demandée uniquement lorsque l’utilisateur choisit **Supprimer la sélection**. iOS peut afficher sa propre confirmation ou autorisation. Les éléments supprimés sont assujettis aux fonctionnalités et aux délais de récupération de l’application Photos, notamment l’album **Suppressions récentes**, si iOS les y place.

## 4. Renseignements conservés sur l’appareil

Photo Review conserve dans l’espace de stockage privé de l’application les données minimales nécessaires pour maintenir la liste d’éléments en attente et reprendre la révision. En particulier, SwiftData peut conserver :

- L’identifiant local de chaque photo ou vidéo marquée pour suppression.
- L’identifiant et le nom de la catégorie ou de l’album d’origine.
- La date à laquelle l’élément a été marqué, l’état d’une demande de suppression et, en cas d’erreur, le texte d’erreur nécessaire pour afficher ou réessayer l’opération.
- Le point de reprise de la révision par catégorie : type et identifiant de la collection, nom affiché, identifiant du dernier élément dont la décision a été enregistrée et date de mise à jour.

L’application ne conserve pas de fichiers multimédias, de copies de photos, de vidéos, de vignettes ni d’objets PhotoKit dans SwiftData. La base de données locale est configurée sans synchronisation CloudKit ni service dorsal de Photo Review.

La langue choisie et un compteur d’utilisation servant à espacer les publicités peuvent aussi être conservés dans les préférences locales d’iOS. Le compteur est remis à zéro lorsqu’un intervalle publicitaire est écoulé. Il n’est pas utilisé comme identifiant de compte.

Ces données sont utilisées sur l’appareil même. Le système d’exploitation peut inclure les données des applications dans les sauvegardes de l’appareil, selon les réglages de sauvegarde choisis par l’utilisateur. Le Responsable ne reçoit pas ces sauvegardes.

## 5. Publicité et Google Mobile Ads

La version examinée intègre le SDK Google Mobile Ads pour charger des publicités natives dans le parcours de révision. Le code prévoit un intervalle de huit photos révisées : le moment venu, s’il reste une autre photo à réviser, une carte publicitaire est insérée. L’application ne demande pas ces publicités lorsqu’elle détecte un abonnement actif. La fréquence ou la disponibilité finale peut aussi dépendre de la configuration publicitaire et de la réponse du fournisseur.

Les demandes publicitaires limitent le contenu à la classification grand public de Google. Cette classification limite le type de contenu publicitaire; elle ne signifie pas qu’un âge vérifié est transmis à Google ni que ce réglage suffit à lui seul à satisfaire aux règles de confidentialité applicables aux enfants.

Le SDK peut traiter automatiquement les renseignements nécessaires pour diffuser, mesurer, protéger et diagnostiquer les publicités. Selon la documentation de Google Mobile Ads pour iOS, ces renseignements peuvent comprendre l’adresse IP, les identifiants d’appareil ou publicitaires disponibles, les données publicitaires et les interactions avec les publicités, les journaux de plantage ainsi que les mesures de performance ou de diagnostic. Google peut utiliser ces données selon ses propres avis, outils, réglages de l’appareil et exigences légales. Le SDK peut communiquer avec Google et les fournisseurs publicitaires participants.

L’application ne transmet pas à Google de photos, de vidéos, de vignettes ni d’identifiants locaux de la photothèque comme paramètres de demandes publicitaires. Si l’utilisateur touche des éléments interactifs d’une publicité, utilise le geste d’interaction configuré par le SDK ou ouvre la destination de la publicité, Google, l’annonceur et le site ou l’application de destination peuvent recevoir des renseignements sur cette interaction et les traiter selon leurs propres avis.

Les publicités sont identifiées dans l’interface. L’utilisateur peut passer la carte au moyen du bouton ou du geste disponible. Une interaction vers la droite est configurée comme geste de clic personnalisé pour le SDK et peut être enregistrée comme interaction publicitaire; le comportement final et la destination dépendent de la publicité diffusée.

Vous pouvez consulter la [Politique de confidentialité de Google](https://policies.google.com/privacy) et la description des données du SDK dans la [divulgation des données de Google Mobile Ads pour iOS](https://developers.google.com/admob/ios/privacy/data-disclosure). Les renseignements publicitaires et les contrôles disponibles peuvent varier selon le pays, le système d’exploitation, les réglages de l’appareil et les technologies de consentement mises en place.

## 6. Achats et abonnements

L’application propose des abonnements hebdomadaires et annuels à renouvellement automatique au moyen de StoreKit, le système d’achat d’Apple. Avant un achat, Apple affiche le prix, la devise, la période, les taxes et les conditions applicables dans la boutique concernée.

Apple traite le paiement et gère la transaction, le renouvellement, l’annulation et la restauration des achats. Photo Review vérifie auprès de StoreKit s’il existe un abonnement actif afin de cesser d’afficher des publicités. Le Responsable ne reçoit ni ne conserve le numéro complet de carte ou les identifiants de paiement. Apple peut traiter les renseignements de compte, de paiement et de transaction conformément à ses avis et à ses conditions.

L’utilisateur peut gérer ou annuler un abonnement dans les réglages de son compte Apple/App Store et restaurer les achats admissibles à partir de l’application. Les liens disponibles sont **[Gérer les abonnements Apple](https://apps.apple.com/account/subscriptions)** et le **[contrat de licence d’utilisation standard d’Apple](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/)**. La disponibilité, le prix, le renouvellement et les remboursements sont assujettis aux conditions d’Apple et de la boutique.

## 7. Finalités et décisions de l’utilisateur

Les renseignements sont utilisés aux fins suivantes :

1. **Fournir la fonctionnalité principale :** consulter les catégories et les albums autorisés, présenter les photos et les vidéos, mémoriser où l’utilisateur s’est arrêté et conserver ses décisions en attente.
2. **Exécuter les actions demandées :** retirer des éléments de la liste d’éléments en attente ou demander à iOS de supprimer par lot uniquement ceux confirmés par l’utilisateur.
3. **Gérer l’abonnement :** vérifier auprès de StoreKit l’achat et sa validité pour activer l’expérience sans publicité.
4. **Afficher et mesurer la publicité :** charger les publicités, limiter leur fréquence, enregistrer les interactions publicitaires au moyen du SDK et financer l’accès gratuit.
5. **Conserver les préférences :** conserver localement la langue choisie et l’état minimal nécessaire à la fréquence publicitaire.
6. **Traiter les incidents :** afficher dans l’application les erreurs de Photos, de StoreKit ou du SDK et permettre de réessayer les opérations, s’il y a lieu.

L’accès à Photos a lieu uniquement après que l’utilisateur a accordé l’autorisation correspondante dans iOS. Lorsque Google UMP détermine qu’une décision de confidentialité publicitaire est requise, l’application demande cette décision avant de démarrer Google Mobile Ads. Les achats sont traités lorsque l’utilisateur confirme l’opération par l’intermédiaire d’Apple. L’application ne demande pas de date de naissance et ne crée pas de compte d’utilisateur.

## 8. Transferts et fournisseurs

Photo Review ne possède pas de service dorsal propre et ne transmet pas au Responsable de copie de la photothèque. Certaines fonctionnalités peuvent nécessiter une communication directe avec :

- **Apple**, pour les autorisations et les services du système Photos/iCloud, la distribution de l’application, StoreKit, la validation des achats et la gestion des abonnements.
- **Google et les participants à son service publicitaire**, pour le chargement, la mesure, la protection et le diagnostic des publicités et des interactions avec celles-ci.
- **Les annonceurs et les destinations externes**, lorsque l’utilisateur interagit avec une publicité et qu’un lien ou une application de tiers s’ouvre.

Ces fournisseurs peuvent traiter les renseignements dans d’autres pays que celui de l’utilisateur selon leurs propres avis, contrats et mécanismes de transfert. Pour la publication, le Responsable doit confirmer les entités fournisseurs correspondant aux comptes et aux accords réels d’Apple et de Google, ainsi que les transferts internationaux applicables.

Les identifiants locaux de Photos ne sont pas vendus et Photo Review ne remet pas de photos ou de vidéos aux annonceurs. Le code examiné ne comprend aucune intégration à une plateforme propre d’analytique, de gestion de la relation client (CRM), d’inscription de comptes ou de publicité de tiers autre que Google Mobile Ads.

## 9. Conservation et suppression des données

Les identifiants des éléments en attente demeurent dans le stockage local jusqu’à ce que l’utilisateur retire la marque ou que Photos confirme la suppression et que l’application retire l’entrée. Si l’opération échoue, l’application peut conserver l’élément en attente et l’erreur pour permettre un nouvel essai.

Le point de reprise de la révision est conservé localement pour permettre de poursuivre une catégorie et est supprimé ou mis à jour lorsque sa session se termine ou redémarre. Les préférences demeurent sur l’appareil tant qu’elles ne sont pas modifiées ou que les données de l’application ne sont pas supprimées. Le Responsable ne conserve pas ces enregistrements sur un serveur central.

La désinstallation de Photo Review supprime normalement les données locales de l’application, sans préjudice des sauvegardes de l’appareil ni des données qu’Apple, Google ou d’autres fournisseurs doivent conserver selon leurs propres politiques. Désinstaller l’application n’annule pas un abonnement Apple; l’utilisateur doit l’annuler dans son compte.

## 10. Sécurité

L’application utilise le stockage privé d’iOS et limite les renseignements locaux aux identifiants et à l’état de révision nécessaires à ses fonctionnalités. L’accès à la photothèque est contrôlé par les autorisations du système d’exploitation. Le Responsable n’exploite ni base centrale de photos ni compte d’utilisateur pour cette version.

Aucune mesure ne peut garantir une sécurité absolue. L’utilisateur doit protéger l’accès à son appareil, tenir iOS à jour, vérifier les autorisations de Photos et éviter de partager son appareil avec des personnes non autorisées. Apple et Google appliquent leurs propres mesures aux services qu’ils gèrent.

## 11. Droits et choix de l’utilisateur

L’utilisateur peut :

- Accorder, limiter ou révoquer l’autorisation de Photos dans les réglages d’iOS.
- Vérifier, annuler ou retirer de la liste locale les marques de suppression avant de confirmer le lot.
- Confirmer la suppression, puis la gérer dans Photos, y compris dans **Suppressions récentes**, s’il y a lieu.
- Changer la langue dans l’application.
- Gérer, annuler ou restaurer des achats par l’intermédiaire d’Apple.
- Demander des renseignements sur le traitement des renseignements personnels dont le Responsable est responsable et exercer les droits d’accès, de rectification, d’annulation ou d’opposition (ARCO), retirer son consentement, s’il y a lieu, ou limiter l’utilisation ou la communication, conformément à la législation applicable.

Pour exercer vos droits ou présenter une demande, écrivez à l’adresse de contact indiquée dans la dernière section du présent avis en indiquant votre nom, un moyen de recevoir une réponse, le droit que vous souhaitez exercer et les renseignements permettant de retrouver les données concernées. Si vous représentez une autre personne, indiquez cette relation. Le Responsable peut demander les renseignements strictement nécessaires pour vérifier l’identité ou la représentation conformément à la législation applicable. N’envoyez pas par courriel de photos, de mots de passe, de numéros de carte ni d’autres renseignements sensibles inutiles.

Certains enregistrements existent uniquement sur l’appareil et le Responsable ne peut pas les consulter à distance. Pour les supprimer, l’utilisateur peut retirer les marques dans l’application, gérer l’élément dans Photos, modifier les autorisations ou désinstaller l’application. Les demandes concernant les achats, les identifiants publicitaires ou les renseignements gérés par Apple ou Google doivent aussi être adressées à ces fournisseurs par leurs voies officielles.

## 12. Personnes mineures

Photo Review s’adresse au grand public et n’est pas conçue ni commercialisée spécifiquement pour les enfants. L’application ne crée pas de comptes et ne demande pas l’âge des utilisateurs. La photothèque peut contenir des images de personnes mineures; celles-ci sont affichées localement uniquement dans les limites de l’autorisation accordée et ne sont pas transmises à des serveurs de Photo Review ni aux demandes publicitaires créées par l’application. Les demandes publicitaires limitent le contenu à la classification grand public de Google et UMP présente les choix de confidentialité appropriés à la région. L’application ne transmet pas l’âge de l’utilisateur et ne configure pas les demandes comme étant spécifiquement destinées aux enfants. L’utilisation par des personnes mineures et le traitement des renseignements qui y est associé sont assujettis aux lois applicables, ainsi qu’aux réglages d’âge et aux contrôles parentaux de l’appareil et du compte Apple.

Si le Responsable constate qu’il a reçu des renseignements personnels d’une personne mineure d’une manière incompatible avec la loi applicable, il prendra les mesures appropriées, qui peuvent comprendre leur suppression lorsque cela est possible.

## 13. Modifications du présent avis

Le Responsable peut mettre à jour le présent avis lorsque l’application, les fournisseurs, les finalités ou les obligations légales changent. La version en vigueur indiquera sa date de mise à jour et sera accessible à l’adresse [https://morrisgrill33.github.io/photo-review/aviso-de-privacidad-fr-CA.html](https://morrisgrill33.github.io/photo-review/aviso-de-privacidad-fr-CA.html). Si une modification exige un nouveau consentement, celui-ci sera demandé dans l’application ou par un autre moyen permis par la législation applicable avant le traitement concerné.

## 14. Autorité de protection des renseignements personnels

Si l’utilisateur estime que sa demande n’a pas été traitée adéquatement, il peut s’adresser à l’autorité compétente en matière de protection des renseignements personnels de son territoire. Au Mexique, il peut consulter la **Secretaría Anticorrupción y Buen Gobierno** (ministère de la Lutte contre la corruption et de la Bonne Gouvernance) et la procédure de protection des droits prévue par la [Ley Federal de Protección de Datos Personales en Posesión de los Particulares](https://www.diputados.gob.mx/LeyesBiblio/pdf/LFPDPPP.pdf) (Loi fédérale sur la protection des données personnelles détenues par des particuliers). Les renseignements officiels du ministère sont accessibles à [gob.mx/BuenGobierno](https://www.gob.mx/buengobierno).

## 15. Responsable du traitement et contact

Le responsable du traitement des renseignements personnels liés à Photo Review est **Mauricio Zárate Barrera**, domicilié au **Grand Masters 48, Fracc. Junto al Río, Temixco, Morelos, Mexique**, dont l’adresse courriel pour les questions de confidentialité est **morrisgrill@gmail.com** (ci-après le « Responsable »).

Photo Review est une application pour iPhone destinée au grand public; elle n’est pas conçue ni commercialisée spécifiquement pour les enfants. Elle permet de parcourir les catégories et les albums de la photothèque, de passer en revue les photos et les vidéos, de les conserver ou de les marquer pour suppression, de gérer les éléments en attente et de consulter les offres d’abonnement. Sa distribution est prévue au **Mexique, aux États-Unis et au Canada**, avec un avis offert en espagnol, en anglais des États-Unis et en français canadien. L’application est offerte par **Mauricio Zárate Barrera**.

Pour toute question, demande ou plainte concernant le présent avis ou le traitement des renseignements, vous pouvez écrire à **morrisgrill@gmail.com**, le moyen de communication du Responsable.
