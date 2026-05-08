# Bitacora-IV
## Tarea 1
Incorporado el docker-compose.yml, lo ejecutamos para que se active en el mismo docker.
<img width="917" height="377" alt="image" src="https://github.com/user-attachments/assets/76316baf-039d-44c8-99a5-eb1e704e7508" />

## Fase de ejecución
Cuando voy a conectarme al contenedor con las instrucciones indicadas, me salta un aviso de que ha sido cambiado el host de de identificación. Pero la verificación falla por lo que no me deja avanzar.
<img width="794" height="312" alt="image" src="https://github.com/user-attachments/assets/ca5e8d55-2270-40a6-adc2-074812b98498" />
Para poder solucionar este problema, como el docker es muy nuevo, aún no reconoce el localhost, por lo que hay que poner su IP, que es este caso es 127.0.0.1
Completado lo anterior y añadiendo los comandos correspondientes ssh-keygen -t ed25519 -C "mariadoloresbarba.25@campuscamara.es", ya se ha completado la transferencia necesaria.
"<img width="658" height="298" alt="image" src="https://github.com/user-attachments/assets/12b983fb-a89a-4800-b424-e9e257e515bc" />


Accedemos al sshd_config para la modificacion de las líneas, pero me salta un mensaje de error de que alumno no está dentro del administrador.
<img width="492" height="255" alt="image" src="https://github.com/user-attachments/assets/ec78fb21-4a92-4337-8293-3d0696d673e9" />


Para comprobar lo que hemos hehco, nos vamos al escritorio remoto de conexión y escribimos localhost:3389. Al aceptar, nos va a saltar un error de que el equipo no se ha podido conectar porque ya hay otra sesión en el equipo remoto. 
<img width="626" height="490" alt="image" src="https://github.com/user-attachments/assets/157a215d-4ef8-49fb-8f77-538b0b61efc2" />

Como nos ha dado fallo, nos dirigimos a la web de localhost:3000 y vemos como Ubuntu está activado aquí gracias al apache guacamole.
<img width="789" height="348" alt="image" src="https://github.com/user-attachments/assets/5912f256-b115-4b85-9f2c-b979582348a6" />

Para completar la actividad, lo último que falta por hacer es crear un archivo .txt y averiguar si es posible su realización. Al comporbar que si puedo hacerlo, se ha completado la actividad.
<img width="818" height="327" alt="image" src="https://github.com/user-attachments/assets/89f533f6-489b-466f-bcc1-69556965bb96" />

## Reflexión
Me ha resultado más sencillo ya que te permite tener varias pantallas a la vez con función de copiar y pegar y tener el alfitrion en el mismo terminal y desde ahí poder modificar y acceder lugares que desde otros lados no se nos permite.




