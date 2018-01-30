# Rendu-THP-Ruby-on-rails-w4d01

<h1>Initiation à Rails</h1>

<ul>
	<li><a href="https://github.com/sebbai/Rendu-THP-Ruby-on-rails-w4d01/new/master?readme=1#site-statique-et-site-dynamic"> Différence entre un site statique et un site dynamic</a></li>
	<li><a href="https://github.com/sebbai/Rendu-THP-Ruby-on-rails-w4d01/new/master?readme=1">Le MVC</a></li>
	<li><a href="https://github.com/sebbai/Rendu-THP-Ruby-on-rails-w4d01/new/master?readme=1">Les routes</a></li>
	<li><a href="https://github.com/sebbai/Rendu-THP-Ruby-on-rails-w4d01/new/master?readme=1">Les Bases De Données(BDD)</a></li>
	<li><a href="https://github.com/sebbai/Rendu-THP-Ruby-on-rails-w4d01/new/master?readme=1">GET/POST</a></li>
	<li><a href="https://github.com/sebbai/Rendu-THP-Ruby-on-rails-w4d01/new/master?readme=1">Le concept de migration</a></li>
	<li><a href="https://github.com/sebbai/Rendu-THP-Ruby-on-rails-w4d01/new/master?readme=1">Les relations entre les models des BDD</a></li>
	<li><a href="https://github.com/sebbai/Rendu-THP-Ruby-on-rails-w4d01/new/master?readme=1">Les fonctions du CRUD</a></li>
</ul>
<h3><a href="#site-statique-et-site-dynamic">Difference entre un site statique et un site dynamic</a></h3>
<p>Un <strong>site statique</strong> est un site qui ne change pas et n'intéragie pas selon l'utilisateur(la géolocalisation, les recherches précédentes...), il sera toujours le même (même si on rafraichi éternellement la page HTML sera toujours la même), le site peut contenir des vidéos, des GIFs et des musiques mais sera quand même static car les animations ne le  rendent pas dynamic pour autan.</p>
<p>Un <strong>site dynamique</strong> est un site qui renvoi une réponse par rapport au paramètre reçu de l'utilisateur(identifiants, géolocalisation, fils d'actualités...), de ce fait une même adresse URL n'affichera pas le même résultat pour tous les utilisateurs.<br></p>

<h3>MVC</h3>
<p>Le <strong>MVC</strong> pour Model View Controller sert à structuré le code avec plusieurs types de fichiers(.rb, .html.erb). Une partie pour l'affichage(View)(HTML.erb qui renvoi une page HTML).<br>Une partie pour accéder à la base de données et la manipulée(Model)(.rb).<br>
Une autre partie qui traitera le code brut(Controller)(.rb) on y mettra les classes, les méthodes...<br></p>

<h3>Les routes</h3>
<p><strong>Les routes</strong> sont les chemins d'accès aux index et aux pages HTML du site, elles se trouvent dans la barre de recherche avec des "/". Ex http://guides.rubyonrails.org<mark><em>/active_record_callbacks.html</em></mark>  la partie en italique est la route. Le nom peut être plus ou moins explicite.</p>

<h3>Les Bases De Données(BDD)</h3>
<p>La <em>Base De Données</em> ou <em>BDD</em> permet de stocké et organisé les données(id utilisateur, mot de passe, photos, informations de paiements...).<br></p>

<h3>GET/POST</h3>
<p>GET renvoi quelque chose à l'utilisateur.<br>
POST va créer un élément(formulaire).</p>

<h3>Le concept de migration</h3>
<p>La <em>migration</em> sert un créé une table de BDD, à la modifier ou la supprimer.<br></p>

<h3>Les relations entre les models des BDD</h3>
<p>Les models communique avec la BDD pour y récupérer des éléments référencer par ID.</p>

<h3>Les fonctions CRUD</h3>
<p>CRUD est un acronyme anglais pour Create Read Update Delete qui correspond à 4 fonctions nécessaires pour gérer une BDD.</p>
