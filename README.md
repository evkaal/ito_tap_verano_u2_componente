# Componente visual generador de password en java


## Descripción del componente
Este componente permite la generación de contraseñas, de manera aleatoria incluyendo numeros letras mayusculas, minusculas y algunos caracteres especiales, ademas permite ver la contraseña y ocultarla de una manera sencilla, todo en java.


## Aplicaciones
* Aplicaciones de Prueba y Desarrollo: Ideal para entornos de desarrollo que requieren generación rápida de contraseñas para pruebas de software.
* Aplicaciones de Aprendizaje: Útil para proyectos educativos que enseñan conceptos básicos de seguridad informática y manejo de contraseñas.
* Herramienta de Uso Personal: Para usuarios individuales que necesitan generar contraseñas seguras para cuentas personales y acceso seguro a dispositivos.

## Caracteristicas
* Generación de Contraseñas Aleatorias: Crea contraseñas aleatorias que incluyen letras minúsculas, mayúsculas, números y caracteres especiales.
* Interfaz Minimalista y Funcional: Incluye un JPasswordField para visualizar y copiar la contraseña generada de manera segura.
* Opción de Mostrar/Ocultar Contraseña: Un checkbox permite alternar entre ocultar y mostrar la contraseña generada. El icono del checkbox cambia visualmente para indicar el estado actual de la contraseña.
* Botón de Generar: Al presionar un botón, se genera una nueva contraseña aleatoria con los parámetros configurados.

## Requisitos
* JAVA JDK 13 o superior
* IDE parececido a netbeans
  
## componenteVisual
Aqui se genera las contraseñas incluye los metodos de validad contraseña y genrar contraseña

## Metodos
### generarContraseña
* Es el metodo que declara una varaible de tipo String donde contiene todos los caracteres que puede ioncluir dentro de la contraseña.
* El SecureRandom crea un objeto random para eleigir aleatoriamente los datos
*  StrinBuilder aqui se crea un objeto de tipo StringBuilder donde se va a a guardar la contraseña

### validarContraseña
* Es el metodo que valida si la contraseña cumple con ciertos caracteres especificos.
* Dentro se retorna password una vez validado la contraseña

### Otras acciones
* Se le agrega iconos al checkBox creando obketos de tipo ImageIcon 
* En los eventos de los botones, contienen condiciones donde validan que el password tenga una longitud de 8.


## Instalación


## Autores
Eduardo Jiménez Mendoza

## Funcionamiento 
Consulta el link para conocer mejor el componente 
