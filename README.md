# ministra 5.6.9 en Ubuntu 20.04 Vanilla
wget https://files.scripting.online/ministra_569/install.sh
sudo chmod +X install.sh
sudo bash install.sh
Durante la instalación, el script solicitará dos contraseñas, una para el usuario root de MySQL y la otra para una contraseña que Ministra utilizará para conectarse a MySQL. Se le preguntará si desea descargar archivos directamente desde los servidores de Ministra. escriba sí o no; si selecciona no, el script se descargará desde un espejo. Durante la última parte del script, cuando se ejecuta sudo phing, verá un mensaje que le pedirá que confirme la autenticidad de una fuente para git, simplemente escriba sí y presione Entrar.
