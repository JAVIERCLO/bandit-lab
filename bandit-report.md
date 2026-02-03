## Bandit level 0
**Objetivo**
Encontrar la contraseña del siguiente nivel.
**Comandos utilizados:**
ls -l
cat readme

# Explicación:
Se listaron los archivos para localizar el archivo que contenía la contraseña y se visualizó el contenido del archivo readme con la clave.

# Contraseña obtenida:
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

## Bandit level 1
**Objetivo**
Encontrar la contraseña del siguiente nivel.
**Comandos utilizados:**
ls
cat ./-
file ./-

# Explicación
Se listaron los archivos para localizar el archivo que contenía la contraseña y se averiguó el tipo de archivo y el contenido del archivo - con la clave.

# Contraseña obtenida:
263JGJPfgU6LtdEvgfWU1XP5yac29mFx

##Bandit level 2
**Objetivo**
Encontrar la contraseña del siguiente nivel.
**Comandos utilizados:**
ls
cat ./"--spaces in this filename--"

# Explicación
Se listaron los archivos para localizar el archivo que contenía la contraseña y se visualizó el contenido del archivo --spaces in this filename-- con la clave.

# Contraseña obtenida:
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

## Bandit level 3
**Objetivo**
Encontrar la contraseña del siguiente nivel.
**Comandos utilizados**
ls
cd inhere
ls -la
file ./...Hiding-From-You
cat ./...Hiding-From-You

# Explicación
Se listaron los archivos, se ingresó al directorio con un archivo oculto que contenía la contraseña y se visualizó el contenido del archivo ...Hiding-From-You con la clave.

# Contraseña obtenida:
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

## Bandit level 4
**Objetivo**
Encontrar la contraseña del siguiente nivel.
**Comandos utilizados:**
ls
file inhere
cd inhere
ls -la
cat ./-file00
cat ./-file01
cat ./-file02
cat ./-file03
cat ./-file04
cat ./-file05
cat ./-file06
cat ./-file07

# Explicación
Se listaron los archivos, se comprobó el tipo de archivo de inhere, se ingresó a la carpeta inhere, se visualizó el contenido de los archivos -file0N hasta ver la clave.

# Contraseña obtenida:
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw


## Bandit level 5
**Objetivo:**
Encontrar la contraseña del siguiente nivel.
**Comandos utilizados**
ls
cd inhere
find ./ -size 1033c
cat .file2

# Explicación
Se listaron los archivos, se ingresó al directorio inhere, se hizo una búsqueda de los archivos que ocupan 1033 bytes, se visualizó el archivo .file2 con la clave.

# Contraseña obtenida
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG


## Bandit level 6
**Objetivo:**
Encontrar la contraseña del siguiente nivel.
**Comandos utilizados**
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null

# Explicación
Se buscó en donde el usuario dueño sea bandit7, el grupo dueño sea bandit6, el archivo pesa 33 bytes y se utilizó 2>/dev/null para que no aparezcan errores por falta de permisos.

# Contraseña obtenida
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj


## Bandit level 7
**Objetivo**
Encontrar la contraseña del siguiente nivel.
**Comandos utilizados**
ls
grep "millionth" data.txt

# Explicación
Se listaron los archivos en el directorio, se utilizó grep para filtar en donde estaba el texto millionth y se encontró la clave.

# Contraseña obtenida
dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

## Bandit level 8
**Objetivo**
Encontrar la contraseña del siguiente nivel.
**Comandos utilizados**
ls
sort data.txt | uniq -u

# Explicación
Se listaron los archivos, se ordenó el contenido de data.txt y se buscó la línea con ocurrencia única para hallar la clave.

# Contraseña obtenida
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
