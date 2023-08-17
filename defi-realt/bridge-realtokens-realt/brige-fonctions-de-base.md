# Brige, fonctions de base

Transférer des RealTokens d'une chaine à une autre, avec ce Bridge,  est assez simple :&#x20;

1. Se connecter avec son wallet en étant sur la chaine source (Ethereum, par ex)
2.  Sélectionner la propriété de votre wallet que vous souhaitez transférer :

    <figure><img src="../../.gitbook/assets/image.png" alt="" width="227"><figcaption></figcaption></figure>
3.  Indiquer la quantité à transférer :

    <figure><img src="../../.gitbook/assets/image (2).png" alt="" width="346"><figcaption></figcaption></figure>
4. Si vous souhaitez bridger vers un autre wallet (qui doit etre whitelisté) : indiquer son adresse ("reception personnalisée"),
5.  Transférer, en validant la transaction avec les frais correspondants.\
    Un message confirme l'envoi sur la chaine source (avec les coordonnées de la transaction correspondante) :

    <figure><img src="../../.gitbook/assets/image (3).png" alt="" width="216"><figcaption></figcaption></figure>
6.  Actualiser votre navigateur et aller dans "History",\
    Vous constatez que vous êtes en attente de validation :

    <figure><img src="../../.gitbook/assets/image (4).png" alt="" width="563"><figcaption></figcaption></figure>
7. L'action qui suit la validation, dépend de la chaine cible :&#x20;

*   Dans le sens Ethereum vers GnosisChain : une transaction transferera automatiquement le RealToken sur votre wallet (Elle apparaitra au bout d'un moment dans History : Statut "complété")

    <figure><img src="../../.gitbook/assets/image (5).png" alt="" width="563"><figcaption></figcaption></figure>
*   Dans le sens GnosisChain vers Ethereum : à cause des frais de réseau, la livraison sur Ethereum ne sera pas automatique et necessitera une opération de claim (après avoir actualisé votre navigateur, dans "history")

    <figure><img src="../../.gitbook/assets/image (6).png" alt="" width="563"><figcaption></figcaption></figure>
* Pour transférer le Realtoken vers votre wallet sur Ethereum (Claim),&#x20;
  * vous devez au préalable vous mettre sur Ethereum (sinon il y aura demande de changement de chaine, suivi d'un message d'erreur...),
  * vous devez valider la transaction avec les frais correspondants,
  *   la transaction apparaitra dans l'historique et le statut passant à "Réclamé"

      <figure><img src="../../.gitbook/assets/image (7).png" alt="" width="563"><figcaption></figcaption></figure>

