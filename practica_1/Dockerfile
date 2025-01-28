#de que libreria, de quien trabajas
FROM node:22

#el directorio de trabajo
WORKDIR /app

#este mando copia los archivos de la carpeta actual a la carpeta de trabajo, de donde a donde 
COPY . /app/

EXPOSE 80

#este comando se ejecuta cuando se crea el contenedor, dentro del contenedopr va a correr
RUN npm install

#ESte comando hace que se ejecute el index.js y por fuera del contenedor 
CMD ["node", "server.js"]

# el "docker build . "hace que se cree la imagen y el docker run hace que se ejecute el contenedor 