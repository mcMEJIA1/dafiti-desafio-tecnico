1. Escribe un comando para ver las últimas dos líneas del archivo `lorem-ipsum.txt`, ubicado en el directorio `bash/`:
```shell 
```tail -n 2 lorem-ipsum.txt
```

2. Escribe un comando para mostrar la cantidad de palabras que contiene cada línea del archivo `lorem-ipsum.txt`, ubicado en el directorio `bash/`:
```shell
```while read -r line; do echo "$line"  | wc -w ; done < lorem-ipsum.txt
```

1. Escribe un comando para ver el contenido del archivo `lorem-ipsum.txt`, ubicado en el directorio `bash`, sin los caracteres ***punto*** `.` y ***coma*** `,`:
```shell
```sed 's/.//' lorem-ipsum.txt | sed 's/,//' lorem-ipsum.txt 
```

4. Escribe un comando para listar todos los directorios dentro de este repositorio (no recursivo):
```shell
```respuesta
```

5. Esribe un comando para ordenar los directorios listados, por tamaño:
```shell
```respuesta
```
