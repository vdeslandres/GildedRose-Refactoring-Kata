Spécification de la Rose dorée (Gilded Rose)

Bonjour et bienvenue dans l'équipe de la Rose dorée !

Comme vous le savez, notre petite taverne située à proximité d'une cité importante est dirigée par l'amicale aubergiste Allison.
Nous achetons et vendons uniquement les meilleurs produits. Malheureusement, la qualité de nos marchandises se dégrade à l'approche de leur date de péremption.
Un système a donc été mis en place pour suivre et mettre à jour notre inventaire. Il a été développé par Leeroy, une personne pleine de bon sens, partie pour de nouvelles aventures.

Votre mission est d'ajouter une nouvelle fonctionnalité à notre système pour que nous puissions vendre un nouveau type de produit.

Mais d'abord, quelques informations sur notre système :
• Tous les éléments ont une valeur sellIn qui désigne le nombre de jours restant pour nous pour vendre l'article.
• Tous les articles ont une valeur quality qui dénote combien l'article est précieux.
• A la fin de la journée pour chaque produit, ces deux valeurs diminuent.

Plutôt simple, non ? Attendez, ça devient intéressant :
• Une fois que la date de péremption est passée, la qualité se dégrade deux fois plus rapidement.
• La qualité (quality) d'un produit ne peut jamais être négative.
• Le produit "Aged Brie" accroit sa qualité avec le temps ;
• La qualité d'un produit n'a jamais une valeur supérieure à 50.
• "Sulfuras", un objet légendaire, n’a pas besoin d’être vendu et ne perd jamais en qualité ;
• "Backstage passes", comme "Aged Brie", augmente sa qualité au fur et à mesure que sa date de péremption approche (sellIn) ; la qualité augmente de 2 quand il reste 10 jours ou moins, et de 3 quand il reste 5 jours ou moins, mais la qualité tombe à 0 après le concert.

Nous avons d'autre part récemment signé un partenariat avec un fournisseur de produits ("Conjured"). Cela nécessite de mettre à jour notre système :
• Les éléments "Conjured" voient leur qualité se dégrader deux fois plus vite que les objets normaux.

Vous pouvez faire les changements que vous voulez à la méthode updateQuality() et ajouter autant de code que vous voulez, tant que tout fonctionne correctement.
Cependant, nous devons vous prévenir, vous ne devez modifier en aucun cas la classe Item ou ses propriétés car cette classe appartient au gobelin de l'étage. Il rentrera dans une rage instantanée et vous tuera sans délai si jamais vous modifiez cette classe, car il ne croit pas dans le partage du code. Par contre vous pouvez ajouter une méthode updateQuality() et des propriétés statiques dans la classe Item si vous voulez, nous vous couvrirons.
Juste une précision, si un produit ne peut jamais avoir une qualité supérieure à 50, "Sulfuras" est un objet légendaire et comme tel, sa qualité est de 80 et ne change jamais.
