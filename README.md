# Comandos-SO-IIIQ

ip addr (sacar IP)
sudo (convertir comando a admin)
sudo apt install -name of the app- (instalar app)
sudo apt install openssh (conectar virtual)
whoami (saber user)
root (conectarse para ser admin)
cleaar (borra todo)
user add / sudo user add -name- -m
neofetch > para ver carac de la virtual
comando pwd > me dice en que ruta estoy en la terminal
comando cd > devuelve a home en la terminal
sudo apt update >va a todos los paquetes del repusitorio a actualizar
sudo apt upgrade >para instalarlos
cat /etc/passwd #archivo para ver users del SO
/etc/shadown #ver contra encriptada
nmap IPADDRESS #puertos abiertos
mkdir #crear carpeta
rm ruta #borrar carpeta
rm carpeta -r #que lo elimine donde sea que este
rm carpeta -rf #lo fuerza para que no pregunte
scp texto.txt fherreram084@192.168.1.184:/home/fherreram084/Semana09/texto3.txt
wget url #extrae archivos de alguna pag web 
git clone (url del que quiero clonar) #para correr scripts de github
wc #hacer conteo de palabras
wc /var/log/syslog -l #solo lineas
wc /var/log/syslog -w #palabras
wc /var/log/syslog -m #caracteres
head /var/log/syslog -n 3 #ver lineas primeras
tail /var/log/syslog -n 3 #ver ultimas lineas
more /var/log/syslog #podemos ver lineas cuando damos enter. Q para parar
less /var/log/syslog #
ls -l / -R #recorre todas las carpetas y las imprime en pantalla
ls -l / -R | more #las pasa poco a poco
grep #buscar cadenas de texto
grep -r "linux" /var/log #busca una palabra en el directorio que ponemos
find /home/fherreram084 -name index.html #buscar en una carpeta en especifico
history #historial de la terminal 
history | grep palabraqueocupobuscarenlaterminal #para buscar algo en especifico en la terminal
reboot #reinicia la pc sin importar nada
shutdown #apaga sin importar nada
pdfunite p1.pdf p2.pdf salida.pdf #une los pdf, el ultimo es el que tiene todos juntos
pdfseparate -f 1 -l 5 salida.pdf resultado_%d.pdf #saca solo paginas que yo indico una por una
convert -verbose -density 300 -trim -quality 100 -flatten -sharpen 0x1.0 archivo.pdf salida.jpg #de pdf a jpg
sudo apt-get install ocrfeeder tesseract-ocr tesseract-ocr-spa
ocrfeeder #abre una app para sacar texto de una imagen
sudo snap install app #instalacion desde snap
apt-get install lightdm xfce4 xfce4-goodies :Para instalar XFCE y demás paquetes
sudo nano /etc/lightdm/lightdm.conf :Para crear un folder llamado lightdm.conf en /etc/lightdm
systemctl reboot #reinicia el sistema
systemctl isolate graphical.target #cambia de interfaz a consola (server del proyecto)
VNCserver -localhost #reinicia el server
sudo ufw default deny incoming / sudo ufw default allow outgoing #configura politicas de firewall
docker pull nextcloud #crear instancia en NC


