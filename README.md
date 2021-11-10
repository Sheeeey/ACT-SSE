# ACT-SSE
1. Utilizar [Google Fonts](https://fonts.google.com/) para cambiar el tipo de fuente del documento la siguiente fuente: https://fonts.google.com/specimen/Cinzel+Decorative#standard-styles
2. Poner un favicon en la siguiente página: https://www.pngitem.com/middle/hhmwow_bloodborne-hunters-mark-tattoo-png-download-hunters-mark/
3. Bajo el apartado del titulo bloodborne poner la siguiente imagen [Vicaria Amelia](https://media.vandal.net/i/1280x720/3-2018/201832201439_1.jpg.webp)
4. Añadimos las siguiente imagenes bajo el apartado de jugabilidad: [BossFight](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.businessinsider.com%2Fbloodborne-review-photos-bosses-weapons-2016-8&psig=AOvVaw0W98WXzDy6qFVU5a6HdQSX&ust=1636547028048000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCOCGwfaii_QCFQAAAAAdAAAAABAD) y esta al lado [dollFace](https://external-preview.redd.it/PBeCrULhl3u5rqqPo5T9F7Q_iAh9gd6zwcw5BvmHenE.jpg?width=640&crop=smart&auto=webp&s=bba9c7b801bd83829ee09235dedaa61b59e6f22f)
5. Mediante una hoja de **estilos externos** se ha de aplicar formato a la página web de manera que:
 * Regla 1. Utilizar el selector universal `*` para cambiar el tipo de fuente del documento
 * Regla 2. Añadir el elemento body en el cual añadiremos el background con la siguiente [Imagen](https://www.wallpaperflare.com/anime-anime-grasoso-bloodborne-video-game-art-fantasy-city-wallpaper-cwerh/download/2160x1440)
 * Regla 3. En el elemento body vamos a tener que poner el background fijo para que la imagen no se mueva al desplazar el texto.
 * Regla 4. Los elementos de `h1` con color rgb(104, 9, 9)
 * Regla 5. Los elementos con clase `title` tendrán que estar en color `rgb(104, 9, 9)`.
 * Regla 6. Los parrafos tienen que estar en color white en tamaño medium.
 * Regla 7. Los elementos del párrafo tienen que llevar esta fuente [Google Fonts](https://fonts.google.com/specimen/MedievalSharp?query=medieval)
 * Regla 8. Los elementos div tendrán una clase llamada all.
 * Regla 9. Dentro de la clase all vamos a poner un el borde `inset` con el color `rgb(104, 9, 9)` de `10px` con un margen de `5% 10%` y un fondo de color `black`.
 * Regla 10. En la etiqueta `h1` sin clase vamos a añadirle el color `rgb(104, 9, 9)`.
 * Regla 11. En las imagenes que hemos añadido vamos a ponerlo en tamaño `40%` con un borde tipo `inset` color `white`
 * Regla 12. En la clase de los párrafos añadimos la lista que hemos hecho para que se aplique el color `white`.
 * Regla 13. En la etiqueta ul abrimos un estilo en css para que estén del mismo color que los párrafos en la etiqueta p ponelos ,li.
 * Regla 14. En las eitquetas ul añadimos el siguiente estilo:
 ```css
  ul {
    list-style: none;
  }
  
  ul li::before {
    content: "\2022";  
    color: white; 
    font-weight: bold; 
    display: inline-block; 
    width: 1em; 
    margin-left: -1em; 
  }
  ```
  Para que se nos quede la bolita de la lista de color blanco.
 * Regla 15. 
Añadir un borde de color rgb(104, 9, 9) y estilo border:instet. y dentro de este borde poner un bakcground color negro.
Hacer una documento de styles.css
Poner el siguiente background: https://www.wallpaperflare.com/anime-anime-grasoso-bloodborne-video-game-art-fantasy-city-wallpaper-cwerh/download/2160x1440
Poner una clase titulo con tamaño 70px y color rgb(104, 9, 9)
Poner el mismo color del titulo en los subtitulos.
Añadir esta imagen https://media.vandal.net/i/1280x720/3-2018/201832201439_1.jpg.webp con un borde instet color: white tamaño 40%
En el estilo body poner un margen de 5% y 10%
Añadimos estas imagenes debajo del párrafo de jugabilidad , https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.reddit.com%2Fr%2Fbloodborne%2Fcomments%2Fewe0i6%2Fhas_anyone_created_doll_in_the_character_creation%2F&psig=AOvVaw2iMKVKdsdP1-T5m0Nmqktp&ust=1636547213188000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCKiy7c-ji_QCFQAAAAAdAAAAABAD




