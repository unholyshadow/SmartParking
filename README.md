Clonar este proyecto

1. Installar Git
	https://git-scm.com/download/win
	
2. Clonar el proyecto

	git clone https://github.com/unholyshadow/SmartParking.git
	
	cd SmartParking

Desarrollar con Phonegap

1. Installation guide
	https://phonegap.com/getstarted/
	
	En el paso 3, en lugar de crear un nuevo proyect, abrir el SmartParking.


ISSUE and Solution

1. Loading screen issue

Downloaded the Node.js version 6 x86 zip (https://nodejs.org/dist/latest-v6.x/node-v6.17.1-win-x86.zip)

In the zip file, go to node_modules folder, extract the NPM folder, and zip the NPM folder into NPM.zip

Navigate to the 'C:\Program Files (x86)\Adobe\PhoneGap\PhoneGap Desktop\resources\app.asar.unpacked\bin' folder, and replaced NPM.zip with the one I created.

Opened cmd, navigated to the same folder, and ran postInstall.bat
