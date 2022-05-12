# linkedin-node-databases

Para descargar con todas las branches. Cada una de ellas tiene el ejercicio de cada tarea con una b para begining y e para ending
de cada video

`mkdir node-databases`

`cd node-databases` 

`git clone --bare git@github.com:LeanoA/linkedin-node-databases.git .git`

Este comando no devuelve nada
`git config --bool core.bare false`

`git reset --hard`

para revisar que todas las branche se hallan bajado
`git branch`

# Configurando el docker


`docker run --name mongodb -p 37017:27017 mongo`

para ver que docker corren 

`docker ps`

