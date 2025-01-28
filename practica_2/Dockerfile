# Usa una imagen base de Python
FROM python

# Establece el directorio de trabajo dentro del contenedor
WORKDIR /python3

# Copia el archivo de requerimientos (opcional si tienes dependencias)
COPY . /python3



# Comando para ejecutar tu script de Python
CMD ["python", "rng.py"]


##docker start -it  hace que el contenedor se ejecute en modo interactivo
## docker start -ai hace que el contenedor se ejecute en modo interactivo y se conecte a la terminal