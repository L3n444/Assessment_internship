
This project uses the game engine Unity and AR Foundation. 

Goal : this program allows the user to visualize 3D models from their device (computer, phone, tablet).

Use : To use this project, you have to download these folders and add them on Unity to create a Unity project. Then you have to build it with Android or iOS. 
My program can work on computer or on phone/tablet.

Hierarchy : 
This project contains files from the AR template. They are not mine. 
My files are in the folder "Assets" and they are separated according to their role (script, model, scene). 

	Files : 
	- Click : this files detects when the user click on the screen with his finger (phone/tablet) or with a mouse (computer). 

	- MainMenu : this files manages the differents menus (main menu, changeModel menu,...) and also the buttons (open and close the menu windows).

	- ToggleSettings : this files manages the ToggleGroup which allows the user to choose a different model. 

The different windows are on the same canvas and on the same scene.  


Ce projet a été programmé pour fonctionner sur ordinateur (détection du clic de la souris) ou sur tablette/téléphone (détection de la pression du doigts). Cependant, je n'ai pu vérifier que la fonctionnalité (téléphone et tablette) car mon ordinateur ne possède pas de capteur AR. De plus, possédant des appareils Apple (iPhone et iPad), les tests ont été effectués avec le module OS d'Unity et non avec celui d'Android. 