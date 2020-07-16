# JS Snippets

## jQuery

$("a[rel~='external']").click(function(){
	this.target = "_blank";
});

//OPEN IN NEW WINDOW, THANKS: http://css-tricks.com/snippets/jquery/open-external-links-in-new-window/
$("a[href^='http']").attr("target","_blank");




//ANIMATED SCROLL TO TOP, thanks: http://snipplr.com/view/8782/jquery-animated-scroll-to-top/
$('#pageEnd').click(function(){
	$('html, body').animate({scrollTop:0}, 'slow');
	return false;
});

//LAZY LOADING OF IMAGES, thanks: http://www.appelsiini.net/projects/lazyload
$("img").lazyload();
