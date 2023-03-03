Primero creamos nuestro repositorio local y lo asociamos con el remoto, una vez creado el repositorio creamos la rama gh-pages y nos podemos manos a la obra con nuestra primera web en jekyll


Para poder crear primero el tema remoto tenemos que buscar uno que nos guste de kejyll, en mi caso he usado el repositorio, en este caso usamos el de daviddarnes/garth.

Seguimos las intrucciones del creador del tema para poder cambiarlo en nuestra página Jekyll en este caso hay que agregar en el archivo config.yml las siguientes opciones: remote_theme: daviddarnes/garth y en plugins jekyll-remote-theme.

En el archivo de gemfiles instalamos las gemas necesarias, ene ste caso son las de gh-pages, remote theme y para poder posibles errores nos aconsejan instalar webrick.

Una vez instalado todo lo necesario procedemos a crear nuestra página web. Mi tema acepta 4 tipos de layout pero yo he optado por crear cuatro páginas distintas con el layout: pages.

Una vez finalizada la web la subimos al repositorio remoto mediante un push, como hemos estado trabajando sobre la rama gh-pages podremos visionarla en nuestra navegador.

