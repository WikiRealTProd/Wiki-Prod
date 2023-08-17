# Bridge, en cas de Pb..

Le bridge est une opération qui se déroule en 2 temps : une transaction d'envoi depuis la chaine source, puis après validation une seconde transaction sur la chaine cible.

Si vous rencontrez des problèmes lors de la seconde transaction, vous etes dans la situation délicate où votre propriété a été envoyé au Bridge mais celui ci ne la restitue pas !

La seconde étape la plus complexe est celle dans le cas du Claim (Bridge Gnosis vers Ethereum). dans ce cas :&#x20;



* Soit vous n'arrivez pas à lancer le claim depuis l'application, la solution est alors de le faire à partir de l'explorateur directement sur le smartcontract.\
  L'adresse du contrat mediator, qui gère la logique du Bridge, est :&#x20;
*   Autre cas, le claim a été lancé, mais n'aboutie pas&#x20;

    <figure><img src="../../.gitbook/assets/image (3).png" alt="" width="218"><figcaption></figcaption></figure>

    Une procédure pour annuler totalement le bridge et se faire restituer le realtoken sur la chaine source, est alors a mis a disposition dans l'historique via le statut "Help"\
    Une fois réalisée, le statut de l'opération de Bridge sera "Recovered"

    <figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>
