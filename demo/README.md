# Demostracion de la solucion <!-- omit in toc -->

A continuación, se presenta una demostración de la solución siguiendo la secuencia de pasos correspondiente al intercambio de credenciales educativas entre tres partes: primero, una institución educativa que acredita a los egresados de un programa de High School. Segundo, un egresado que, habiendo completado el programa, recibe una credencial por parte del primero. Y tercero, una empresa que, para otorgar un puesto de trabajo requiere al segundo presentar una prueba que demuestre que ha culminado los estudios de High School. Adicionalmente, la demostración incluye un paso adicional en el que la empresa otorga una credencial de empleo. 

### Corriendo esta demo en un navegador

En un navegador, es posible dirigirse al servicio docker playground [Play with Docker](https://labs.play-with-docker.com/) y ejecutar la demo sin necesidad de descargar Docker localmente o de ejecutarla en una maquina virtual o barebone. Se deberan abrir tres instancias docker, una para cada uno de los agentes que participan en la demo. 

### Agente Emisor
```bash
git clone https://github.com/jdelvalle10/TFM_Final
cd TFM_Final/demo
LEDGER_URL=http://dev.greenlight.bcovrin.vonx.io ./run_demo faber
```

### Agente Titular

```bash
git clone https://github.com/jdelvalle10/TFM_Final
cd TFM_Final/demo
LEDGER_URL=http://dev.greenlight.bcovrin.vonx.io ./run_demo alice
```

### Agente Verificador
```bash
git clone https://github.com/jdelvalle10/TFM_Final
cd TFM_Final/demo
LEDGER_URL=http://dev.greenlight.bcovrin.vonx.io ./run_demo acme
```

1. Una vez iniciadas las tres instancias, desde el agente Emisor, genere una invitacion a conectar
2. Copie la invitacion en el agente Titular y presione [ENTER]
3. Pruebe la conexion entre el Emisor y el Titular mediante el envio de mensajes (Opcion 3)
4. Emita la credencial educativa de "Jose del Valle" y verifique como el agente Titular la recibe correctamente.
5. Ahora cierre la conexion con entre el Emisor y el Titular, usando la opcion "X" en el agente Emisor.
6. En el agente Titular, seleccione la opcion para aceptar una nueva invitacion
7. En el agente Verificador, cree una nueva invitacion. Copie esta invitacion en el agente titular para crear una nueva conexion.
8. En el agente verificador, seleccione la opcion de solicitar una prueba de educacion. El Titular aceptara la solicitud de verificacipon se aceptara automaticamente.
9. El agente Verificador validara la credencial y aceptara como valida la credencial educativa del Titular.

