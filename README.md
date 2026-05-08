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

Para comprobar lo que hemos hehco, nos vamos al escritorio remoto de conexión y escribimos localhost:3389. Al aceptar, nos va a saltar un error de que el equipo no se ha podido conectar poruq eya hay otra sesión en el equipo remoto. 
<img width="626" height="490" alt="image" src="https://github.com/user-attachments/assets/157a215d-4ef8-49fb-8f77-538b0b61efc2" />



