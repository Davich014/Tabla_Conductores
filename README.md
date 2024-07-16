# Tabla_Conductores
Esta aplicación JavaFX permite al usuario seleccionar un año y ver los resultados de los pilotos y constructores de Fórmula 1 en tablas interactivas. Cuando se selecciona un año, las tablas se actualizan automáticamente con los datos correspondientes.

1.- Importaciones: Se importan las clases necesarias para crear la interfaz gráfica y trabajar con la base de datos.

2.-Clase Resultdrivers: Esta clase extiende la clase Application de JavaFX y es el punto de entrada de la aplicación.

3.-Atributos de la clase: Se declaran los siguientes atributos:

tableView: un TableView que se utilizará para mostrar los datos de los pilotos.
driverList: una ObservableList que almacenará los datos de los pilotos.
yearComboBox: un ComboBox que se utilizará para filtrar los datos por año.

4.-Método start(): Este es el método principal de la aplicación. Aquí se realiza lo siguiente:

Se establece la conexión a la base de datos MySQL.
Se crea el TableView y se configuran las columnas.
Se cargan los datos de los pilotos desde la base de datos utilizando el método loadDrivers().
Se carga la lista de años disponibles en el yearComboBox utilizando el método loadYears().
Se crean los botones de filtrado y reseteo.
Se crea el layout de la aplicación utilizando un BorderPane y se agrega el TableView y los controles de filtrado.
Se crea la escena y se muestra la ventana principal.

5.-Método loadDrivers(): Este método ejecuta una consulta SQL para cargar todos los datos de los pilotos desde la base de datos y los agrega a la driverList.

6.- Método loadYears(): Este método ejecuta una consulta SQL para obtener los años disponibles en la base de datos y los agrega al yearComboBox.

7.- Método filterByYear(): Este método se ejecuta cuando se selecciona un año en el yearComboBox. Filtra la driverList para mostrar solo los pilotos del año seleccionado.

8.- Método main(): Este es el punto de entrada de la aplicación, que llama al método launch() para iniciar la ejecución de la aplicación JavaFX.


CAPTURAS DEL CODIGO EJECUTADO:

![image](https://github.com/user-attachments/assets/93b3b747-3c03-4e20-9e5e-e58d86fcbde6)
![image](https://github.com/user-attachments/assets/9e4aa0ae-2c4c-4de1-872a-17f22aeec1a7)
![image](https://github.com/user-attachments/assets/8936151a-415e-4a60-8349-4937bbf26beb)
![image](https://github.com/user-attachments/assets/b58f670a-4367-45fd-8e35-3d530e2684dd)



