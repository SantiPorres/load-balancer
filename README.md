IMPLEMENTACIÓN DE BALANCEADOR DE CARGA CON NGNIX

- Verificamos que las máquinas se ven entre ellas

![image](https://github.com/user-attachments/assets/d60f8edd-e008-4ab4-af12-cbfa167dad44)

![image](https://github.com/user-attachments/assets/2843ee65-aeac-4f53-9c92-cb799ed9d5fb)

![image](https://github.com/user-attachments/assets/85d353b8-acf9-4eea-9a9b-cf3b9f76dc58)


- Actualizamos la lista de paquetes disponibles e instalamos nginx en cada máquina

![image](https://github.com/user-attachments/assets/fa65c2e4-fca7-455b-b78f-853085ce239b)


- Ponemos a correr nginx

![image](https://github.com/user-attachments/assets/1dab4871-f888-4951-ac4e-8de0b0cd8f6d)


- Configuración de la máquina que actúa como balanceador de carga (10.10.0.11)

![image](https://github.com/user-attachments/assets/3472e218-2a35-4746-8d0f-1e5066358a65)


- Verificamos que el default quedó bien

![image](https://github.com/user-attachments/assets/ea7bf54a-8dd7-4698-ba02-78f41536b777)


- Y en las otras dos máquinas (10.10.0.12 y 10.10.0.13) ejecutamos este comando que va a establecer la respuesta que vamos a recibir de ambas máquinas

![image](https://github.com/user-attachments/assets/37ac27fc-a5ff-45dd-82b8-fcd9e0bed579)


- Hacemos pruebas manuales con curl

![image](https://github.com/user-attachments/assets/0e7731ed-39de-47de-b029-392e011706c8)


- Después hacemos pruebas con apache benchmark

![image](https://github.com/user-attachments/assets/3c206ce6-c4cb-4a48-8934-d563f4acbc89)


- Revisamos los logs de la máquina 10.10.0.12

![image](https://github.com/user-attachments/assets/b483f6a0-0f48-42fa-85d0-4a6611f3fc6f)


- Y los de la máquina 10.10.0.13

![image](https://github.com/user-attachments/assets/baf3176a-2120-4d65-9cd3-3c3d84690525)

