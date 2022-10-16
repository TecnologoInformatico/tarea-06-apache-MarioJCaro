1- mkdir repositorios, git clone https://github.com/TecnologoInformatico/AdmInf-web.git

2- apt update

3- sudo apt install apache2

4- sudo mkdir mcaro

5- sudo chown ubuntu mcaro

6- cd /etc/apache2/sites-available, sudo cp 000-default.conf pp.conf, sudo nano pp.conf (se edita el servername por “www.mcaro.tecnologoinformatico.com”)

7- cd /etc, sudo nano hosts (se agrega 127.0.0.1 y www.mcaro.tecnologoinformatico.com)

8- sudo service apache2 restart

9- cp -r AdmInf-web /var/www/mcaro

10- Para probarlo entro a la ip 129.159.56.110 desde el navegador

11- {
    "serverName": "mcaro.tecnologoinformatico",
    "ip": "129.159.56.110"
