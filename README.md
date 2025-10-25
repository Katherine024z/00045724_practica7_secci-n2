# 00045724_practica7_secci-n2
1. ¿Cuál es la diferencia entre autenticación y autorización?
Autenticación: se encarga de verificar la identidad del usuario, generalmente por medio del uso de credenciales o de datos biometricos; es visible y manejada principalmente por el usuario
Autorización: determina los permisos y niveles de acceso que tiene el usuario para acceder a recursos o información; ocurre inmediatamente después de la autenticación y gestionada por una organización

2. ¿Cuál es la función del token JWT en la guía?
El token JWT contiene información codificada sobre el usuario y sus permisos; actúa como una credencial que el usuario puede enviar en solicitudes posteriores para demostrar que está autenticado, permitiendo el acceso a recursos protegidos sin necesidad de enviar las credenciales nuevamente en cada petición. Como se pudo observar al hacer el metodo GET en Postman se obtuvo un mensaje diciendo que se ha accedido y que el usuario tiene un ID, la fecha en que se emitio el token y la fecha en que expirará.