<h1 align="center"> Proyecto SSH </h1>

## Antes de empezar
Lo primero es ir a git y crear un nuevo repositorio. Después de esto, creamos nuestro nuevo proyecto en el Code. Una vez listo esto, creamos también un nuevo proyecto en Git y lo asociamos al repositorio creado anteriormente. 

## Conexión a otra máquina con claves pública y privada
1. Generar un par de claves SSH en la máquina local:

```bash
ssh-keygen 
```

2. Copiar la clave pública a la máquina remota:

```bash
ssh-copy-id asir2@A09Equipo01
```

3. Iniciar sesión en la máquina remota con la clave privada:

```bash
ssh asir2@A09Equipo01
```

## Configuración de acceso SSH en GitHub
1. Generar un par de claves SSH en la máquina local si no se ha hecho previamente:

```bash
ssh-keygen 
```

2. Agregar la clave pública a la cuenta de GitHub:

   - Ve a "Settings" en el perfil de GitHub.
   - Seleccionar "SSH and GPG keys".
   - Agregar la clave pública.
