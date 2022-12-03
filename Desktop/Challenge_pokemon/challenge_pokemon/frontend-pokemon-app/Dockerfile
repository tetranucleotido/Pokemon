FROM node:16-alpine
WORKDIR /app
#Copio archivo de gestion de depedencia node
COPY ./ /app/
# Descargo dependencia
RUN npm install 
#Expone el puerto 3000 en el contenedor
EXPOSE 3000
#Establece el comando sobre como correra la aplicacion
CMD ["sh","-c","npm start"]