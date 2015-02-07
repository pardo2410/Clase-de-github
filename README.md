# Clase-de-github
Ejemplo de uso github
clase-de-github - en la rama mejorandola
Este Es Un EJEMPLO de Github Para La comunidad de #mejorandola

Una Vez instalas GIT, Debes configurarlo:

git config user.name --global "cristiano" git config --global user.email " xxxxxx@xxxx.com "

Generando tu clave pública:

ssh-keygen

Leyendo tu llave párr copiarla un Github:

cat ~ / .ssh / id_rsa.pub

Arrancando tu Proyecto:

git init

toque README

git add README

git commit -m "tu primer cometer"

git push origin master

/ ********************************* GIT from 0 - Porklinsmannf ********* **************************** /

configuration

Descarga git párr OSX

Descarga de Windows git párr

Descarga git para Linux

Crea repositorio Un Nuevo

Nuevo Crear otro Directorio, ábrelo y ejecuta git init párr Crear repositorio git ONU de nuevo.

Hacer checkout un repositorio de la ONU

Crea Una copia locales del repositorio git clone Ejecutando / ruta / al / repositorio al utilizar remoto Servidor de la ONU, el Será comando git clone nombre de usuario @ host: / ruta / al / repositorio

Flujo de Trabajo

Tu repositorio locales Compuesto this Tres por "árboles" git ADMINISTRADOS POR. El Primero es tu Contiene Directorio de Trabajo el cual sea los Archivos. El Segundo es el el Índice sea cual actua Como un área intermedia y finalmente un EL JEFE el cual sea un Apunta El último cometió Realizado.

agregar y comprometerse

Puedes en proponer Cambios (agregarlos un índice de el) git Usando agregar git add * Este es el Primer Paso en el Flujo de Trabajo básico. Pará En Realidad Hacer cometer un Estós Cambios EE.UU. git commit -m "Commit mensaje" Ahora el archivo esta incluido en el HEAD, but AÚN no en tu repositorio remoto.

Envío de Cambios

Tus Cambios ESTAN Ahora es el JEFE de tu copia local. Para enviar OEN Cambios un repositorio git remoto ejecuta push origin master Reemplaza tu maestro Por La rama a la cual sea desees enviar tus casas de cambio.

Si no se han clonado ONU repositorio existente y Quieres Conectar tu repositorio remoto de un repositorio de la ONU, need agregarlo con git remoto agregar origen Ahora Florerias subir tus casas de cambio al repositorio remoto selecionado ramas hijo Las ramas utilizadas párr desarrollar Funcionalidades Aisladas Unas de Otras. La principal rama es la rama por "Defecto" CUANDO CREAS repositorio ONU. EE.UU. ramas Otras para el Desarrollo y fusionalas De regreso a la rama principal de Al Terminar.

Una Crea Rama Nueva Llamada "feature_x" y cambiate un Usando ella:

git checkout -b feature_x regresa a la rama principal de git checkout master y borra la rama git branch -d feature_x Una rama no disponible this Para los demás un Menos Que subas (push) la rama de un remoto repositorio git push origin tu

actualiza y Fusiona

actualizar párr tu repositorio local, al cometer mas nuevo, git pull ejecuta en tu Directorio de Trabajo zona de alcance y se funden Cambios Remotos. párr fusionar otra rama de un (maestro EJEMPLO POR) tu rama activa, git utilizació fusionar baño de yunque Casos git intenta fusionar casas de cambio automático. : Desafortunadamente, Esto No es Posible TODO EL TIEMPO y Resultados de la Búsqueda en Conflictos. Tú eres responsable de fusionar organismos europeos de normalización Conflictos manualmente al editar los Archivos mostrados Por git. LUEGO de modificarlos, need marcarlos Como fusionados con git añadir los antes de fusionar casas de cambio, También Puedes dar ONU Vistazo Previo Usando git diff

Etiquetas

Recomendable es crear de Etiquetas párr Cada versión Publicada de software un. Esto Es Conocido Concepto de la ONU, el cual sea Existe tambien en SVN. Puedes en Crear Una Nueva Etiqueta Llamada 1.0.0 Ejecutando git tag 1.0.0 1b2e1d63ff el 1b2e1d63ff se refiere a los 10 Caracteres de El comprometen Id al cual sea Quieres referirte con tu Etiqueta. Puedes en el Obtener el Commit Identificación con git log También Puedes USAR Menos Caracteres Que El cometen id, but Ser Dębe valor ONU Único.

reemplaza locales Cambios

En Caso De Que Hagas algo malo (Que de Seguro Nunca pasa;) PUEDES reemplazar Cambios locales Usando el comando git checkout - reemplaza ESTO los Cambios en tu árbol de Trabajo con El último contenido de HEAD. Los Cambios Que ya han Sido agregados al índice, Asi Como Also Nuevos Archivos, se mantendrán Cambio pecado.

Si Por Otro Lado Quieres deshacerte de Todos los lugares Cambios y se compromete, PUEDES Traer la última versión del Servidor y Apuntar a tu copia local principal of this forma git fetch origen git reset --hard origin / master

Útiles DATOS

Interfaz gráfica Por Defecto gitk colores especiales Para La consola git config color.ui verdadera Sólo Mostrar Línea Una Por Cada cometen en la traza git config format.pretty oneline buscas? Busca otros Archivos de forma interactiva git add -i

enlaces y Recursos

Clientes GRAFICOS GitX (L) (OSX, de código abierto) Torre (OSX) árbol de código fuente (OSX, gratis) GitHub para Mac (OSX, gratis) GUIAS Git Comunidad Book Pro Git Piense como un git GitHub Ayuda Guía Visual Git
