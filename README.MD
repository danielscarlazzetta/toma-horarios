Install Electron

npm install electron --save-dev

        Solo para desarrollo, preload(Cargara los cambios en el momento en que se esten ejecutando)

npm install electron-reload electron-forge --save-dev

        main.js
        require('electron-reload')(__dirname, {
            electron: require(`${__dirname}/node_modules/electron`)
            });


ejecutar app

        npm run dev