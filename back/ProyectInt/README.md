# Inicio en desarrollo del backend
Para desarrollo en ambiente local se puede crear en una imagen docker la base de datos para reducir el consumo de herramientas computacionales: 

### `docker run --name digital-booking-database -v \kuasar\volume-docker\mysql:/var/lib/mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=g10Booking -e MYSQL_DATABASE=proyecto_integrador -d mysql`

El script para generar la base de datos se encuenta en la carpeta assets, sin embargo basta con conectar la base de datos en el application.properties y correr el proyecto para que esta se genere. 

Consulte para ser agregado al ambiente de prueba de los endpoints en postman, ya que a medida que crezca el proyecto y se crean o modifican los endpoints, estos deben ser probados para poder ser aceptado el merge request correspondiente.

Be coder, be happy.
