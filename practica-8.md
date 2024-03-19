# a.  	¿Cómo se inicializa un repositorio en Git?
---
por lo general siempre suelo primero crear la carpeta, luego abro gitGUI, le doy a “create new repository”

![alt text](image-1.png)

luego elijo la carpeta que creé antes y ya

![alt text](image-2.png)
---
# b.  	¿Cómo creas un repositorio en GitHub?

primero voy a la sección de "repositories" de GitHub

![alt text](image-3.png)

le pico al boton verde que dice new.

![alt text](image-4.png)

y ya solo le pongo nombre y pico el boton de create repository.

---
# c.  	¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?

usando el comando de: 

$ git clone https://github.com/sssrcv/repositoriodeprueba

en la terminal de comandos.
---
# d.  	¿Cuál es el flujo básico de trabajo en Git y GitHub?

GitHub se basa en trabajo "corto" para que varias personas de un mismo equipo puedan trabajar en el mismo proyecto.

Mientras que Git se basa en trabajo continuo .

---
# e.  	¿Para qué sirve el archivo .gitignore?

sirve para revisar los nombres en los repositorios y determinar si debe de ignorarse o no basándose en si los nombres coinciden o no.

---
# f.   	¿Cuál es el propósito de una rama?

poner una nueva parte en el código por separado, para poder agregarlo al main después.

---
# g.  	¿Qué es una fusión?

una fusión es cuando juntamos una rama secundaria con otra (por lo general la principal) para combinar su contenido, usando el comando de:
- *$ git merge (nombre de la rama con la que la quieras combinar)*.

---

# h.  	Explica los diferentes tipos de fusión que existen.

- fast forward (la verdad no se como funciona)
- manual merge, esta se lleva a cabo con los comandos:

- *$ git checkout y  git merge*.

---
# i.   	¿Cómo puedes ver el historial de tu repositorio?

para ver el historial de tu repositorio se usa el comando *git log*.

---
# j.   	¿Cuál es el propósito de una etiqueta?

Las etiquetas se usan con el propósito de versionar nuestro código "etiquetándolo" por version del trabajo en la que estemos.