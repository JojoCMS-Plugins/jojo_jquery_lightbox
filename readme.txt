Implements the jQuery lightbox plugin from http://leandrovieira.com/projects/jquery/lightbox/

- You still need to add the lightbox to your DOM elements, eg...

$(function() {
	$('#gallery a').lightBox({fixedNavigation:true});
});