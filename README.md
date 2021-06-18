# Express Books
Express Books 


# Instalacion

```shell
npm install
npm run build
npm start
```

# Variables de entorno
Aunque no deberia, agregue el archivo .env con las variables de entorno
- `PORT`, guardado en el puerto `3000`.
- `APPID` - (opcional), este es un ID único para que la aplicación lo identifique en un balanceador de carga

# Docker

```shell
docker build -t express-books .
```

```shell
docker run -p 80:5000 express-books .
```

vista: `http://localhost`

# Consideraciones

- Asegúrese de que nodemon ignore el archivo `src / books.json`.
