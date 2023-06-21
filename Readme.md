# Monorepo-test

Este proyecto ahora es el monorepo del servidor y cliente para el sistema de orbil,
con el se podra enviar la información y la pagina web del administrador a los usuarios
que sooliciten dicha información.

# Comandos clave

Listado de comandos para iniciar en desarrollo, compilar o iniciar para producción el servidor

### npm run dev

- Este comando iniciara el proyecto para desarrollo, con el se iniciaran los servicios de ambos proyectos
  para consumirlos o usarlo de manera independientes, con los cambios realizados en este.

### npm run test

- Este comando compila el cliente e inicia el servidor para identificar errores en tal caso, tambien puede
  emplearese para ejecutar el proyecto de manera local.

### npm run build

- Con el inicia la compilación del lado del cliente.

### npm run production

- Con este comando se inicia el servidor del ApiRest con pm2 y se renderiza el lado del cliente previamente
  compilado después del desarrollo (Aqui es necesario tener en cuenta si tiene instalado pm2 en el sistema,
  de no ser así, no podra ejecutarse).
