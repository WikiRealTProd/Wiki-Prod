# Bridge, en cas de Pb..

Le bridge est une opération qui se déroule en 2 temps : une transaction d'envoi depuis la chaine source, puis après validation une seconde transaction sur la chaine cible.

Si la première transaction échoue, c'est pas trop grave car votre token n'a pas été transmis au Bridge.\
Par contre si vous rencontrez des problèmes lors de la seconde transaction, vous etes dans la situation plus délicate car votre propriété a été envoyé au Bridge mais celui ci ne la restitue pas !...

La seconde étape la plus complexe est celle du Claim (Bridge de Gnosis vers Ethereum). dans ce cas :&#x20;

* Soit vous n'arrivez pas à lancer le claim depuis l'application : la solution est alors de le faire à partir de l'explorateur directement sur le smartcontract.\
  L'adresse du contrat mediator, qui gère la logique du Bridge, est : ....
*   Soit le claim a été lancé, mais n'aboutie pas :

    <figure><img src="../../.gitbook/assets/image (3) (1).png" alt="" width="218"><figcaption></figcaption></figure>

    Une procédure pour annuler totalement le bridge et se faire restituer le realtoken sur la chaine source, est alors a mis à disposition dans l'historique via le statut "Help".\


    <figure><img src="../../.gitbook/assets/image (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

    Une fois réalisée, le statut de l'opération de Bridge sera "Recovered"

    <figure><img src="../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>
