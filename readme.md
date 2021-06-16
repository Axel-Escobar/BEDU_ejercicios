
# Iniciar proyecto de git
git init
# preparar archivos que se convertiran en commit
git add .           
# El punto es agregar todos los archivos modificados
# crear commit con su mensaje
git commit -m "Aqui va el mensaje"

#  remoto "solo la primera vez"
git remote add origin http://github.com/adres2093/santander-front.git

# enviar commits al servidor de github 
git push -u origin master