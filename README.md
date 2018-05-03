# test

Instrucciones
- Descomprimir  webapi.rar
- Descomprimir testfront.rar

Levantar el serviocio web api  y levantar el servidor de angular con ng server




Para el backend
- es un web API realizado usando tecnologia .net core v2 .net core v2
se implemento REST con autentificacion JWT

- se obtiene la data desde dos fuentes distintas, una es una lista de pilizas y la otra de clientes
- las clases modelos se encargan de parsear la data a objetos los cuales contienen metodos que realizan las cuatro 
operaciones de consulta requeridas

- En el controlador se llaman a los metodos para generar las busquedas

- el web api tiene la siguiente nomenclatura:

login
http://localhost:35547/api/Token post parametro= email

clientes
http://localhost:35547/api/client/id/{id}
retorna un cliente por su id

http://localhost:35547/api/client/name/{name}
retorna un cliente por su nombre


http://localhost:35547/api/client
retorna todos los clientes


polizas

http://localhost:35547/api/user/{user}
retorna una lista de polizas q pertenecen a un usuario



http://localhost:35547/api/nu,ber/{number}
retorna una poliza dada su id



Para el front end
- Se desarrollo en la ultima version de angular
- Consta de dos componentes login y busqueda y servicios para autentificacion y manejo de tokens jwt


Consideraciones

- el puerto de localhost esta fijo tanto en la configuracion de la web API como en las llamadas 
al servicio en testfront

