# Blog Platzi

Blog creado con React y Redux.

Configurado para ejecución en ambientes Linux Debian y derivados.



**Pasos a seguir:**

Instalar Node: 

```bash
sudo apt install nodejs
```

Instalar NPM:

```bash
 sudo apt install npm
```

Crear aplicación en React:

```node
create-react-app <nombreAplicación>
```

Ejecutar la aplicación:

```node
npm run start
```

ó con

```node
yarn start
```

Si presenta problemas al iniciar, eliminar la carpeta de node_modules con permisos de administrador:

```bash
sudo rm -RF node_modules
```

y reinstalar de nuevo NPM:

```node
npm install
```

Luego, instalar axios:

```node
npm install axios
```

Después, instalar react-router-dom:

```node
npm install react-router-dom
```

También se debe instalar los paquetes redux react-redux:

```node
npm install redux react-redux
```

Seguido a esto se deben instalar el paquete redux-thunk:

```node
npm install redux-thunk
```