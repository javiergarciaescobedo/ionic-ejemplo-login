## Ejemplo para Ionic de Login de usuario usando un correo y contraseña, utilizando el servicio de autenticación Firebase

Se ha omitido el archivo src/environments/environment.ts que almacena las credenciales de conexión a Firebase. Se debe crear a partir de los datos proporcionados en la web de Firebase, con el siguiente formato:

```export const environment = {
  production: false,
  firebase: {
    apiKey: "############",
    authDomain: "############",
    databaseURL: "############",
    projectId: "############",
    storageBucket: "############",
    messagingSenderId: "############",
    appId: "############"
  }
};
```

