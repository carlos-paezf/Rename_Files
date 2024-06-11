# Rename Files and Folders Script

Este repositorio contiene un script de Python que renombra archivos y carpetas dentro de un directorio raíz especificado. El script permite limpiar los nombres de archivos y carpetas eliminando espacios, acentos y caracteres especiales según las opciones especificadas.

## Funcionalidades

- Renombrar archivos y carpetas reemplazando espacios por guiones bajos.
- Eliminar marcas de acento.
- Eliminar caracteres especiales.

## Requisitos

Este script requiere Python 3.x y las siguientes bibliotecas:

- `unidecode`

Puedes instalar las dependencias necesarias ejecutando:

```txt
$: pip install -r requirements.txt
```

## Uso

Para utilizar el script, sigue estos pasos:

1. Clona el repositorio:

    ```txt
    $: git clone <https://github.com/carlos-paezf/rename-files-and-folders.git>
    
    $: cd rename-files-and-folders
    ```

2. Edita el script `rename_files_and_folders.py` para especificar el directorio raíz (root) que deseas procesar y las opciones para eliminar acentos y caracteres especiales.

    ```python
    root = "/ruta/a/tu/directorio"
    remove_accent_marks = True
    remove_special_characters = True
    ```

3. Ejecuta el script:

```txt
$: python rename_files_and_folders.py
```

El script renombrará recursivamente todos los archivos y carpetas en el directorio raíz según las opciones especificadas.
