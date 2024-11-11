# Tarea6_SXE

***1. Primero con el docker compose ya creado, tenemos que lanzarlo***

  ***En el directorio donde se encuentra el docker compose lanzamos este comando***
  
  ```
sudo docker compose up -d
```

  ***Una vez lanzado nos deberia salir esto:***

  ![Screenshot from 2024-11-10 15-26-29](https://github.com/user-attachments/assets/900dd315-5f58-474d-b8db-e4a993a19c2a)


***2. Ahora entramos en prestashop, en el navegador ponemos http://172.18.0.1:8000***

***Nos debería salir esto:***

![Screenshot from 2024-11-10 15-34-42](https://github.com/user-attachments/assets/2854a98f-a13e-4e13-91b1-02cd9835a7be)



***Aceptamos los terminos de privacidad y pasamos a configurar nuestra tienda***

![Captura de pantalla 2024-11-11 010355](https://github.com/user-attachments/assets/64c4c103-d3b6-4af6-b5c5-46a997f66f02)

***Cuando ya tenemos todo rellenado le damos a siguiente y esperamos a que cargue nuestra tienda***

![Captura de pantalla 2024-11-11 085521](https://github.com/user-attachments/assets/c685bb0a-033c-4ee7-849e-038585f7c1b9)


***Una vez ya cargó nos sale esto***

![Captura de pantalla 2024-11-11 085654](https://github.com/user-attachments/assets/535818d7-d0e6-4607-b6cb-b5481871cb40)

***Ahora tenemos que volver a la consola y poner esto***

```
sudo docker compose exec ps bash
```

***Ahora que estamos dentro eliminamos la carpeta de install***

```
rm -r install/
```

***Posteriormente renombramos la carpeta admin***

```
mv admin/ admin449arzmyo29zbrujmi0/
```

***Ahora accedemosa a la carpeta desde el navegador***

![Captura de pantalla 2024-11-11 091028](https://github.com/user-attachments/assets/ad38cade-cfee-48cb-b32b-ba88d5e7e38c)


***Iniciamos sesión y ya estaría todo listo***

![Captura de pantalla 2024-11-11 091117](https://github.com/user-attachments/assets/46e7bd33-a9f3-468d-93d1-013397dafb26)
