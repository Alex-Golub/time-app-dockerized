# Time Application

Time application consists of the frontend and backend parts  
Frontend is written with help of the `Vue.js` framework  
Backend is written using `Node.js` and `Express`  
Database is `MySQL`  
DB management too is `Adminer`  

Run from anywhere use from root dir:

```sh
docker-compose -f docker-compose.pub.yml up
```

For development use:

```sh
docker-compose up
```

Frontend server available at: `http://localhost:3000`
Api server available at: `http://localhost:5555`
Database management (`Adminer`) tool available at: `http://localhost:8888`
`Adminer` credentials can be found in `docker-compose.yml`
