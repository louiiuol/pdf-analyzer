# PDF analyzer

<h2>Recherche automatique de zone de signature</h2>
<p>Le script réalise ces étapes dans l'ordre; il essaie d'abord la première étape, puis si elle échoue, passe à la suivante</p>
<ol>
    <li>Recherche des mots clés "signature", "bon pour accord", ou "lu et approuvé"</li>
    <li>Recherche d'espace vide où l'on pourrait ajouter une signature</li>
    <li>Ajout d'une page prédéfinie (avec un emplacement pour signer)</li>
</ol>
