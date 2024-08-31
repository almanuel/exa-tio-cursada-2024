### Tecnología de la Información en las Organizaciones | Facultad de Ciencias Exactas | UNICEN
# Trabajo Práctico 3  | Git Branching

## Ejercicio 1
- Crear un nuevo branch `bibliografia` y mostrar los branches del repositorio. 

## Ejercicio 2 
- Crear el archivo `capitulos/capitulo4.txt` y añadir el texto siguiente: 

```
En este capítulo veremos cómo usar GitHub para alojar repositorios en remoto.
```

- Añadir los cambios a la zona de intercambio temporal. 
- Hacer un commit con el mensaje `“Añadido capítulo 4.”`
- Mostrar la historia del repositorio incluyendo todos los branches. 

## Ejercicio 3 
- Cambiar al branch `bibliografía`. 
- Crear el archivo `bibliografia.txt` y añadir la siguiente referencia:

```
Chac, S. and Straub, B. Pro Git. Apress. 
```

- Añadir los cambios a la zona de intercambio temporal. 
- Hacer un commit con el mensaje `“Añadida primera referencia bibliográfica.”`
- Mostrar la historia del repositorio incluyendo todos los branches. 

## Ejercicio 4 
- Fusionar (mergear) el branch `bibliografía` con `master`. 
- Mostrar la historia del repositorio incluyendo todos los branches. 
- Eliminar el branch `bibliografía`. 
- Mostrar de nuevo la historia del repositorio incluyendo todos los branches. 

## Ejercicio 5 
- Crear el branch `bibliografía`. 
- Cambiar a `bibliografía`. 
- Cambiar el archivo `bibliografía.txt` para que contenga las siguientes referencias:

```
Scott Chac and Ben Straub. Pro Git. Apress. 
Ryan Hodson. Ry’s Git Tutorial. Smashwords (2014) 
```

- Añadir los cambios a la zona de intercambio temporal y hacer un commit con el mensaje `“Añadida nueva referencia bibliográfica.”` 
- Cambiar a `master`. 
- Cambiar el archivo `bibliografía.txt` para que contenga las siguientes referencias:

```
Chac, S. and Straub, B. Pro Git. Apress. 
Loeliger, J. and McCullough, M. Version control with Git. O’Reilly. 
```

- Añadir los cambios a la zona de intercambio temporal y hacer un commit con el mensaje `“Añadida nueva referencia bibliográfica.”` 
- Fusionar el branch `bibliografía` con el branch `master`. 
- Resolver el conflicto dejando el archivo `bibliografia.txt` con las referencias: 

```
Chac, S. and Straub, B. Pro Git. Apress. 
Loeliger, J. and McCullough, M. Version control with Git. O’Reilly. 
Hodson, R. Ry’s Git Tutorial. Smashwords (2014) 
```

- Añadir los cambios a la zona de intercambio temporal y hacer un commit con el mensaje `“Resuelto conflicto de bibliografía.”`
- Mostrar la historia del repositorio incluyendo todos los branches. 

