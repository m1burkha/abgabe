# abgabe
Den Ordner Project1 in webstorm aufmachen<br>
In Terminal mach ein CD noteserver
npm install in der noteserver ordner
Von Webstorms Terminal dieser command ausführen um den Server zu starten; npm run dev
Der Applikation lauft auf den link http://localhost:3004
In Webstorm die Preferences einstellen unter: Languages & Frameworks, Javascript auf Ecmascript 6 einstellen

Projekt ordner struktur:
  noteserver (haupt order)
    - controllers , der kontoller file die von express server benützt wird<br>
    - data , die daten / Db von der applikation<br>
    - node_modules, erstellt mit npm install
    - public, code an der Client seite services,html images, js, model und css code
    - routes, routing auf der express server seite
    - services, den speichern, holen updaten von daten auf der server seite
    - views, error pages die auf der server seite liegen
    - package.json
    - server.js, die konfiguration file für express js server
