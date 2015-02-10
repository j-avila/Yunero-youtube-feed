# Yunero-youtube-feed
Feed de canales de youtube con jquery

Para su  uso es muy sencillo,  solo debes reemplazar el cnal  en la prueba por el canal  que se desea mostrar



var youTubeURL = "http://www.youtube.com/user/el canal que desea mostrar";
	

	/jquery call---------------------------------------
	var yuneroWidgetHeight = 400; 
	var yuneroWidgetWidth = 280; 
	
	function goClicked() {
		$('#yunero').empty().append(' loading ...');
		youTubeURL=$('#youTubeUrl').val();
		
		loadYunero();
	}


 luego simplemente se llama al div #yunero" o el especificado  en el llamado  de jquery



