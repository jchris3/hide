PROJET: HIDE
c'est un systeme simple d'utilisation qui va permettre de cacher de texte sur une page.
Comment ca marche?
 Dans une balise html, ajouter une classe hide.
 HTML
 
 <a class="declencheur">Cacher</a>
 <p class="hide">Bonjour je suis le bout de message sur la page qui va se cacher quand on va cliquer sur <b>cacher</b></p>
 
 Javascript/JQuery 
 
 $(".declencheur").click(
	function(){
		$('.hide').hide();
		
	}
);
