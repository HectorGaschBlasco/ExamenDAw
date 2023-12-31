# Hector Gasch Blasco
## Examen DAW 1r Trimestre

### Comandos utilizados
- sudo nano HectorGaschBlasco.txt 
- whoami > sudo nano HectorGaschBlasco.txt 
- who -u | grep "pts/" >> $(echo "HectorGaschBlasco" | tr -d ' ').txt

#### Primer paso

Conectarse mediante ssh al ordenador en remoto

```sh
ssh usuario@192.168.0.148
```

Posteriormente la contraseña
```sh
DAMWDAWM
```

#### Segundo paso

Una vez ya conectado, debemos crear un archivo _txt_ con nuestro nombre.
![Mi Imagen](https://github.com/HectorGaschBlasco/ExamenDAw/blob/main/sshnano.png)

#### Tercer paso

Posteriormente empleamos el comando whoami y la concatenación de comando para introducir en el archivo la salida del comando.

#### Cuarto paso

Finalmente utilizamos el comando who para saber quien esta conectado y lo incrustamos una vez más en el archivo creado.
![Mi Imagen](https://github.com/HectorGaschBlasco/ExamenDAw/blob/main/sshcomandowho.png)
![Mi Imagen](https://github.com/HectorGaschBlasco/ExamenDAw/blob/main/sshnanocorrecto.png)  


| Comando | Función |
| ------ | ------ |
| sudo | Permite estar o mantenerse en super usuario |
| whoami | Muestra por pantalla el usuario actual |
| > | Concatena el comando anterior con el siguiente |
| who -u | Muestra información sobre los usuarios que están actualmente conectados al sistema |
| nano | Crea y edita un archivo |

### Bibliografía

> ChatGpt

