<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Aish@'Store</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Bienvenue chez Aish@'Store</h1>
   <nav>
  <ul>
    <li><a href="accueil.html">Accueil</a></li>
    <li><a href="Produits.html">Produits</a></li>
    <li><a href="contact.html">Contact</a></li>


</nav> 
  </section>
<!--image placée apres le menu-->
<img src="image1.png"alt="image1"width="100%">
<script>
  window.onload = function() {
    const urlParams = new URLSearchParams(window.location.search);
    if (urlParams.get('admin') === 'oui') {
      document.getElementById("bouton-ajout").style.display = "inline-block";
    }
  };
</script>
</body>
</html>



<footer>
  <p>&copy;2025Aish@'Store.Tous droits réservés.</p>
</footer>
