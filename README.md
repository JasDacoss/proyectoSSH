<h1 align="center"> Proyecto SSH </h1>

## Antes de empezar
Lo primero es ir a git y crear un nuevo repositorio. Después de esto, creamos nuestro nuevo proyecto en el Code. Una vez listo esto, creamos también un nuevo proyecto en Git y lo asociamos al repositorio creado anteriormente. 

## Conexión a otra máquina con claves pública y privada
1. Genera un par de claves SSH en tu máquina local:

```bash
ssh-keygen -t rsa -b 4096 -C "jdacostaregueiro@danielcastelao.org"
```

2. Copia la clave pública a la máquina remota:

```bash
ssh-copy-id jasmine@narnia
```

3. Inicia sesión en la máquina remota con tu clave privada:

```bash
ssh jasmine@narnia
```
