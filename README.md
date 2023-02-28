# SLACK-BOT-GO
# Tarea: Moficar el formato del mensaje.
Requisito previo, instalar go

Para poder ejecutar el proyecto primero se necesita crear un modulo para poder usar el API de slack

- go mod init <Nombre del modulo>
- go get -u github.com/slack-go/slack

===================================================================================================================

Crear una cuenta de slack y realizar los siguientes pasos:

    1. Creamos un espacio de trabajo
    2. En la esquina superior izquierda esta el nombre del espacio de trabajo creado, le damos click
    3. Buscamos la opción "ajustes y administración", ponemos el cursor en dicha opción
    4. Buscamos la opción que dice "Administrar aplicaciones" y damos click
    5. En la esquina superior dice "compilar", damos click
    6. Creamos una aplicación, seleccionamos la opción from scratch,elegimos el lugar de trabajo y el 
        el nombre de la apliación.
    7. Se despliega una nueva pagina, entre las primeras opciones que ofrece seleccionamos "bot"
    8. Una vez realizado lo anterior, vamos a la esquina superior derecha y damos click en "your apps"
    9. En la sección de "your apps" damos click en la parte de "generate token", seleccionamos el lugar de trabajo
    10. El token generado lo vamos a copiar y pegar el codigo donde dice TOKEN
    11. Con todos pasos completados, vamos al chat que creamos y buscamos en el url del chat la ultima serie de 
            caracteres, en este ejemplo seria : C04S8H5CU7J
        https://app.slack.com/client/T04asdfasdS/C04S8H5CU7J
    12. Estos caracteres los pegamos en codigo donde dice "CHAT"
    13. De esta manera el codigo quedaria listo, solo haria falta correr el programa y pasarle los parametros
    14. go run jenkins-notification.go http://localhost SUCCESS 10 test
    15. Despues de correr este comando con las variables necesarias deberia mandar un msj en su chat de slack
===================================================================================================================

Documentación:

https://pkg.go.dev/github.com/slack-go/slack@v0.12.1#section-readme