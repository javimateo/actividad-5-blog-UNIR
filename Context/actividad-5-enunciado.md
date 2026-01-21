---
title: "Actividad 5: Sistema Blogging en Angular"
student: "javimateo"
course: "Máster Full Stack"
date: "2026-01-21"
tags:
  - angular
  - práctica
  - blog
---

Actividad 5: Sistema Blogging en Angular

Objetivos
Con esta actividad vas a conseguir desarrollar en Angular un sistema para dar de alta
un listado de noticias de un blog en Angular. Crearemos un sistema que nos permite
publicar a través de un pequeño formulario publicaciones en un listado.
El sistema generado será una SPA, donde el formulario y la lista de elementos del
propio formulario se encuentran en el mismo componente.
Haciendo uso de un sistema de eventos y templating de angular debemos capturar
los datos de cada noticia y pintarlos dentro de un listado de noticias que estarán
dentro del propio componente.
De esta forma vamos a repasar conceptos de eventos, captura y pintado de datos en
angular, comunicación entre plantillas y lógica de componente, uso de lógica de
arrays dentro de angular.

Pautas de elaboración
- Debéis crear en angular un componente `blog`, en dicho componente crearéis dos
  áreas, una para el formulario y otra para la lista de noticias.
- Dentro de la lógica del componente crearemos un array multidimensional de JSON
  donde cada elemento del array sea una publicación del blog y lo inicializaremos
  dentro de nuestro componente con dos noticias.
- Los campos que tendrá cada noticia son:
  - Título.
  - Imagen (url de la foto).
  - Texto o cuerpo de la noticia.
  - Fecha de la publicación.
- Las dos noticias que se han inicializado tenemos que pintarlas dentro de la zona
  del listado de noticias en nuestro componente a través de las diferentes técnicas
  de templating que hemos aprendido.
- El formulario recogerá los datos que debe tener cada noticia, a través de un evento
  y comunicando el HTML con el TypeScript de la forma correspondiente.
- La función del evento deberá comprobar que todos los campos están rellenos. Todos
  los datos son obligatorios. Si falta algún dato no se inserta la noticia y se debe avisar al usuario.

Entrega
- Subir el proyecto al repositorio público de GitHub (control de versiones con commits).
- Entregar además un ZIP con todos los archivos del proyecto excluyendo `node_modules` en la plataforma del campus.
- Añadir README con instrucciones para ejecutar la aplicación (instalar dependencias, comando para levantar el servidor).

Criterios básicos de evaluación (sugeridos)
- Código legible y organizado.
- Uso de TypeScript con tipado (interfaces para la entidad noticia).
- Formularios validados (mensajes de error cuando falten campos).
- Las dos noticias iniciales se muestran correctamente.
- Buenas prácticas de Angular (componentes con responsabilidad única, estructura por features, manejo de estado adecuado).

Notas
- Si usas versiones modernas de Angular, se recomienda usar standalone components y Signals cuando aplique.
- Mantén el proyecto con un branch de trabajo para cada funcionalidad (ej. `feature/blog-component`) y usa commits descriptivos.