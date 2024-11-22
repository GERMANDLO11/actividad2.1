# Instalación de Jekyll  
  
Para instalar Jekyll usaremos el comando gem install bundler jekyll.  
Con el comando jekyll new myblog --force se crea un nuevo sitio en Jekyll con el tema minima.  
En el archivo config.yalm se modifica la configuracion.   
Para personalizar el sitio hay que editar los ficheros markdown.  
Luego con el comando  bundle exec jekyll serve ejecutamos el sitio en local.  
Despues deslegamos el sitio en github, para ello usaremos los siguientes comandos
-  git init
-git add .  
-  git commit -m "mensaje"
-  git branch -m gh-pages
-  git remote add origin https://github.com/nombreusuario/nombreusuario.github.io.git
-  git push -u origin main  
  
 Una vez en git hub vamos a setings pages y desplegamos el sitio web





