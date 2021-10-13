# Lanza el dado
En este readme voy explicando paso a paso lo que fui haciendo en mi rama. En ella se podra ver lo que fui entendiendo del proyecto DiceRoller.
## Así lo hice


1. [Crear Boton].
En este commit se puede observar que en el archivo activity_main.xml del layout creo el boton con:
```
        <Button
        android:id="@+id/bLanzar"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="29dp"
        android:text="BotonTexto"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView"/>
``` 


2. [Huella en el boton].
Lo primero de todo en el build.gradle implemento el material de android. A continuacion en res/values/styles.xml le cambio el estilo. Por ultimo en layout/activity_main.xml le añado al boton la huella

[Commit creación botón y huella](https://github.com/hfaildeestevez/andfun-kotlin-dice-roller/commit/47a50d1570457d6b0268878e750e90d24ed6f3e0)

3.[Idiomas](https://github.com/hfaildeestevez/andfun-kotlin-dice-roller/commit/71f4a6030d8a1669640ed573f21ecd4180fb6500)
Lo que hago aquí es básicamente es que en el activity_main.xml pongo el nombre de la aplicación y el texto del botón en español y en inglés cde tal forma que se pueda cambiar.
Aquí es donde empleo los strings.

4. [Creo random](https://github.com/hfaildeestevez/andfun-kotlin-dice-roller/commit/e86ea8d9605aeab0c62d11085d131a84ee0533d9).
En este commit se crea la funcion random.

5. [Visualizo dado](https://github.com/hfaildeestevez/andfun-kotlin-dice-roller/commit/41e4f5e69d8221efbb2630b8436190379b64c717). En este commit 
visualizo las diferentes caras del dado con la ayuda de la funcion random. Lo que hago es asociar cada imagen de cada lado del dado con un numero aleatorio u despues lo visualizo. Las imágenes empleandas se encuentran en drawable.

6. [Random Propio](https://github.com/hfaildeestevez/andfun-kotlin-dice-roller/commit/d0e8b7ebe2faff270920a49a15d0cd29c5d55f17)
