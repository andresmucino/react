{
    // nombre de aplicacion para web
    "name": "Contador App React",
    // nombe corto para la aplicacion en dispositivo mobil
    "short_name": "Contador React",
    // description application
    "description": "Contador app hecha con React para e curso de react desde cero",
    // color de la aplicacion completa
    "background_color": "#333333",
    // tema para colorear espacios donde no llega la aplicacion
    "theme_color": "#333333",
    // url inicial de la aplicacion
    "start_url": "./",
    // alcance de la aplicacion
    "scope": "./",
    // lenguaje de la aplicacion
    "lang": "es-MX",
    // todo lo que va a utilizar la aplicacion del tamaño del dispositivo
    "display": "fullscreen",
    /// orientacion de la aplicacion, portrait nunca cambiara orientacion
    "orientation": "portrait",
    
    "icons": []
}

crear images de icons para el manifiesto de la aplicacion PWA

npx pwa-asset-generator favicon.png ./assets -m manifest.json -i index.html
