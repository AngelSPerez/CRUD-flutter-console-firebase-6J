Investigar cómo instalar Firebase CLI para una aplicación flutter en consola (CMD o bash)

Instalar dependencias: 
En Linux (Fedora):
sudo dnf install nodejs npm
En Windows:
curl -L --retry 5 https://npmmirror.com/mirrors/node/latest-v20.x/node-v20.12.2-win-x64.zip -o %USERPROFILE%\node.zip && powershell -Command "Expand-Archive -Force $env:USERPROFILE\node.zip -DestinationPath $env:USERPROFILE\nodejs" && setx PATH "%PATH%;%USERPROFILE%\nodejs\node-v20.12.2-win-x64"

Verificar instalación: npm -v

Nota: en windows, después de instalar node tienes que cerrar y volver a abrir la  consola


Después hay que instalar el CLI.

Comando universal:
npm install -g firebase-tools

Verificar instalación: flutterfire --version
Inicia sesión con tu cuenta de Firebase con el siguiente comando: firebase login
Entra a la web de Console Firebase y selecciona el botón “Agregar app” y selecciona flutter, sigue las instrucciones que se muestran en pantalla y listo.

Resultado con IA:

