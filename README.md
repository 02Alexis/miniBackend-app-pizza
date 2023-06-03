# Creacion de Json-server
* creamos 📁 miniBackend-app-pizza
* Entramos y abrimos consola git bash
* Ejecutamos comandos: 
#### `npm init -y` crea package.json
#### `npm i json-server` crea package-lock.json y node_modules

# Creamos estructura de carpetas
![imagen](https://github.com/02Alexis/space-tourism/assets/99287560/22ea25cd-a90c-4629-a049-d2ad60d9b324)

### Agregamos su respectiva logoca al index.js
![imagen](https://github.com/02Alexis/space-tourism/assets/99287560/37a24fcb-6ea0-4b35-8b85-8fff0799efff)

### En el package.json dentro de `scripts` agregamos esta linea de comando `"start": "node src/index.js"`
![imagen](https://github.com/02Alexis/space-tourism/assets/99287560/cdaabc44-7d79-4c69-9414-bd98ca7882d8)

### Dentro de la 📁 miniBackend-app-pizza
* Ejecutamos `npm run start` para comprobar que todo este orden

![imagen](https://github.com/02Alexis/space-tourism/assets/99287560/b2f21657-2f58-4863-ad0b-d69ebe5bbf15)

# Creamos repositorio 
* Abrimos nuestra consola de preferencia y ejecutamos los siguientes comandos
#### `git init`
#### `git add .`
#### `git commit -m "first commit"`

## Luego en tu repositorio Git Hub creas un nuevo Repositorio y sigues los siguientes pasos
#### `git remote add origin "link"`
#### `git branch -M main` este lo ejecutas en el caso que no este creada la rama `main`
#### `git push -u origin main`

# Ejecucion
* En el directorio del proyecto donde se encuentra tu archivo `db.json`, puede ejecutar:
#### `json-server --watch db.json` por defecto ejecuta en el puerto 3000 
#### `json-server --watch db.json --port 4000` cambias de puerto al 4000
![imagen](https://github.com/02Alexis/space-tourism/assets/99287560/f30e2af9-a01a-49f5-89e4-1f69a19e3c4f)

![imagen](https://github.com/02Alexis/space-tourism/assets/99287560/07f71449-d5e5-476c-9f84-18d4fb5ef64f)