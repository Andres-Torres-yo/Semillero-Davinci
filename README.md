Este codigo es un prototipo de software para monitoreo de variables: Temperatura y Humedad.
Estas variables son tomadas un sensor DHT11.
Se utiliza comunicación con dos Arduinos Nanos con RF integrado (un emisor y un receptor).
Los datos son visualizados en un HTML que solicita la conexión a un puerto serial, en donde se imprimen los datos y el HTML los recoge y muestra.
Al mismo tiempo, los datos son mostrados en una pantalla OLED o.96" que esta conectada al arduino receptor.
