#GitHub Pages

## Introducción

GitHub Pages es una forma de alojar nuestros proyectos en una página web, 
sin necesidad de tener conocimientos en servidores. De hecho, es algo muy sencillo 
y que no te tomará más de 5 minutos configurar. En este artículo te mostraré cómo hacerlo.

## Como se Hace

-1) Primero vamos a Crear un Nuevo repositori en GitHub para Nuestra pagina.
![RepositoriGit](/../images/gitpag1.png)

-2) A partir de aqui es igual que un repositorio normal solo tenemos que enlazarlo y hacer nuestros commit
como normalmente lo hariamos. 
__ $ git clone https://github.com/nombreDeUsuario/nombreDeUsuario.github.io __

-3) O con una vinculacion remota
__ $ git remote add origin https://github.com/nombreDeUsuario/nombreDeUsuario.github.io __


-4) Y listo nuestra git page podremos verla en este link que sirve para cualquier usuario
__ http://nombreDeUsuario.github.io. __

5) Pero esto no es todo tambien podemos hacer git pages para nuestros proyectos , Basta con tan solo
crear una nueva rama para la gh pages por ejemplo.

__ $ git branch gh-pages __

6) Ahora hacemos un push de este repositorio ..
__$ git push origin gh-pages__

7) y listo nuestra git page se vera en el enlace por ejemplo:
__ http://nombreDeUsuario.github.io/repositorio__