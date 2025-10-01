ls
cd /
cd etc/
cat passwd
cd
cls
vim texto.txt
ls
cat texto.txt
cat << FIN >> texto.txt 
ahora voy a crear un archivo ejecutable
mkdir -p familia/{{mama,papa}/hijos{1..4},papa/perro}
sudo snap install tree
tree familia
FIN

vim texto.txt 
vim ejecutable.sh
sudo chmod +x ejecutable.sh 
ls
chmod +x ejecutable.sh 
./ejecutable.sh 
ls -l
mkdir Archivo ejecutagle
ls
ls -l
mv ejecutagle ejecutable
ls
cp ejecutable.sh ejecutable
ls
cd ejecutable/
ls
cd ..
rm ejecutable.sh
ls
cd ejecutable/ | ls -l
cd ejecutable/
ls
cat << FIN > texto.txt | mv texto.txt nuevo.txt
hola
too
bien
are you okay
?
???
FIN

ls
cd ..
ls
cat texto.txt 
rm texto.txt 
cd ejecutable/
ls
cat nuevo.txt 
cp nuevo.txt home/vagranty
cp nuevo.txt home/vagrant
cd ..
pwd
cd ejecutable/
cp nuevo.txt /home/vagrant
ls
cd ..
ls
rm nuevo.txt 
cd ejecutable/
ls
ls -l
cd /
sudo chmod 777 nuevo.txt
cd
cd eje
cd ejecutable/
ls
sudo chmod a+x nuevo.txt
ls -l
cat nuevo.txt 
mv nuevo.txt /home/vagrant/
ls
cd ..
ls
exit
gls -l
ls -l
rm -r familia
ls
rm -r ejecutable
rm -r nuevo.txt 
cd Archivo/
ls
cd ..
rmdir Archivo/
ls
ssh -keygen
ssh-keygen
cd ..
pwd
ls
cd vagrant/
pwd
ls -la
cd .ssh/
pwd
ls -la
cat id_rsa.pub 
cd
ls
sudo apt install git
git --version 
git clone git@github.com:manucourtade/TP_AySO.git
ls
cp README TP_AySO/
LS
ls
cd TP_AySO/
ls
ls -la
ls -l
ls -la
git status
git add README 
git status
git commit -m "comentario"
git commit -m "Primer archivo"
git push
git push origin main
ls
git add README
git commit -m "Primer archivo"
git config --global user.email "courtademanuel@outlook.es"
git add README
git commit -m "Primer archivo"
git push
git add README
git commit -m "Primer archivo"
git push origin main
git push -u origin main
git add README
git commit -m "Primer archivo"
ls -la
cd
ls
cd repogit/
pwd
ls -la
ls -l
cd repogit/
ls
cd
cd TP_AySO/
ls
cd
cd /
ls
cd etc/
ls -l
cat mtab 
man grep
grep -i SYSFS /etc/mtab 
man grep
grep -i home_url /etc/os-release 
grep SYSFS /etc/mtab 
grep home_url /etc/os-release 
man grep
grep -no home_url /etc/os-release 
grep -i Sysfs /etc/mtab 
grep -i Sysfs /etc/mtab > datos_sys.txt
ls -l
sudo grep -i Sysfs /etc/mtab > datos_sys.txt
man grep
sudo grep -i Sysfs /etc/mtab > ~/datos_sys.txt
cd ..
ls -l
sudo chmod o+w vagrant/
sudo chmod o+w vagrant
pwd
whoami
cd
vim datos_usuario.txt
ls -l
cat datos_usuario.txt 
echo “Usuario=$(whoami)” > datos_usuario.txt 
cat datos_usuario.txt 
mv TP_AySO/ repogit/
ls -l
cd repogit/
ls -l
cd TP_AySO/
ls
cd
ls
mv datos_usuario.txt repogit/TP_AySO/
cd repogit/TP_AySO/
ls
cd
mv datos_sys.txt repogit/TP_AySO/
cd repogit/TP_AySO/
git add .
mv datos_sys.txt ~ 
ls
cd
pwd
cd repogit/TP_AySO/
ls
cd
ls
cd repogit/TP_AySO/
git add .
git commit -m "ADD: agregadp 1er ejercicio sobre datos_usuarios.txt"
git push origin main
git add .
git commit -m "ADD: agregado 1er ejercicio sobre datos_usuarios.txt"
git push
git status
cd
cd /
cd etc/
cat passwd
grep -i vagrant passwd | awk -f ":" '{print$1}'
grep -i vagrant passwd | awk -F ":" '{print$1}'
grep -i vagrant passwd | awk -F ":" '{print$1}' >> /home/vagrant/repogit/TP_AySO/datos_usuario.txt 
cd
cd repogit/TP_AySO/
cat datos_usuario.txt 
git add .
git commit -m “feat: Añadiendo información del Usuario”
git push origin main
git push
cat datos_usuario.txt 
git add datos_usuario.txt 
git commit -m "feat: Añadiendo informacion del Usuario"
git push origin main
ls
cat << EOF >> README.md 
Alumno: Manuel Courtade
Division: 116
Turno: Mañana
EOF

cat README.md 
git add README.md datos_usuario.txt 
git commit -m "ADD: Añadiendo Readme y datos de usuario"
git push
sudo snap install tree
cd
mkdir -p TP1/{{arquitectura/so}/Clase{1..5},so/Clase5}
tree TP1/
mkdir -r TP1/
man mkdir
rmdir -r TP1/
man rmdir
rmdir -p TP1/
man rmdir
rmdir  --ignore-fail-on-non-empty TP1/
ls
cd TP1/
ls
cd 
rm -r TP1/
ls
mkdir -p TP1/{arquitectura,so}/Clase{1..5},so/Clase6
tree TP1/
rm -r TP1/
mkdir -p TP1/{{arquitectura,so}/Clase{1..5},so/Clase6}
tree TP1/
vim script_dir.sh
ls -l
sudo chmod u+x script_dir.sh 
ls -l
mv script_dir.sh repogit/TP_AySO/
cd repogit/TP_AySO/
ls -l
git add .
git commit "ADD: Añadiendo script"
git commit -m "ADD: Añadiendo script"
git push origin main
./script_dir.sh 
ls
tree TP1/
rm -r TP1/
ls
man history
cd
pwd
history -a $HOME/.bash_history
ls
history -a
pwd
history -a /home/vagrant/.bash_history
ls
ls -la
