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
