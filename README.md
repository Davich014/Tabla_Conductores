# Tabla_Conductores
Esta aplicación JavaFX permite al usuario seleccionar un año y ver los resultados de los pilotos y constructores de Fórmula 1 en tablas interactivas. Cuando se selecciona un año, las tablas se actualizan automáticamente con los datos correspondientes.
1.- Importaciones: Se importan las clases necesarias de JavaFX, como Application, FXCollections, ObservableList, Scene, ComboBox, TableView, TableColumn, PropertyValueFactory y VBox.
2.-Clase Driver: Esta clase representa a un piloto de Fórmula 1 y contiene información sobre su nombre, equipo, número de victorias, puntos totales y posición en el campeonato.
3.-Clase Constructor: Esta clase representa a un constructor de Fórmula 1 y contiene información sobre su nombre, número de victorias, puntos totales y posición en el campeonato.
4.-Método start(): Este es el método principal de la aplicación JavaFX, que se ejecuta cuando se inicia la aplicación.

Se crea un ComboBox para seleccionar el año deseado.
Se crean dos TableViews, uno para los pilotos y otro para los constructores.
Se definen las columnas de las tablas y se asocian a los campos de las clases Driver y Constructor.
Se crean listas observables (ObservableList) con los datos de los pilotos y constructores para cada año (2016-2020).
Se agrega un evento de acción al ComboBox para actualizar los datos de las tablas cuando se selecciona un año.
Se crea un VBox para contener el ComboBox y las dos tablas, y se establece como la escena principal de la aplicación.
Se configura y se muestra la ventana principal de la aplicación.
5.-Método main(): Este método es el punto de entrada de la aplicación y llama al método launch() de JavaFX para iniciar la aplicación.

CAPTURAS DEL CODIGO EJECUTADO:
![IMG-20240708-WA0006](https://github.com/Davich014/Tabla_Conductores/assets/169005437/f3b16857-6a84-4452-a9ce-fd9cea15bcad)
![IMG-20240708-WA0005](https://github.com/Davich014/Tabla_Conductores/assets/169005437/df10e6a0-de4b-4e6c-8620-d77de1a05efc)
![IMG-20240708-WA0004](https://github.com/Davich014/Tabla_Conductores/assets/169005437/6b43e028-c9fb-446b-aa70-82f968153ad7)
![IMG-20240708-WA0003](https://github.com/Davich014/Tabla_Conductores/assets/169005437/355032e4-f3e5-4321-b969-1b55b08854d1)
![IMG-20240708-WA0002](https://github.com/Davich014/Tabla_Conductores/assets/169005437/d57cf702-b8e5-42ba-b8f6-85827f877609)

