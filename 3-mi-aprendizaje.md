# COMPLETAR  
Antes de la Práctica
Antes de realizar esta práctica, tenía conocimientos básicos sobre Docker y Docker Compose, pero mi comprensión sobre la configuración y orquestación de servicios complejos era limitada. Conocía conceptos fundamentales como la creación de contenedores y la utilización de imágenes de Docker, pero no había tenido la oportunidad de configurar un entorno multi-contenedor complejo como SonarQube y PostgreSQL utilizando Docker Compose.

Después de la Práctica
Después de completar esta práctica, he logrado una comprensión mucho más profunda y detallada sobre varios aspectos importantes:

Configuración de Servicios Multi-Contenedor:

Aprendí a definir y configurar múltiples servicios en un solo archivo docker-compose.yaml, lo que facilita la administración y orquestación de aplicaciones complejas.
Ahora entiendo cómo mapear puertos entre el host y los contenedores para permitir el acceso desde el exterior.
Gestión de Volúmenes:

Comprendí la importancia de los volúmenes en Docker para la persistencia de datos. Aprendí a configurar volúmenes para ambos servicios (SonarQube y PostgreSQL) y a asignarlos correctamente en el archivo docker-compose.yaml.
Variables de Entorno:

Aprendí a utilizar variables de entorno para configurar servicios de manera flexible y segura, lo cual es esencial para la configuración de bases de datos y otros servicios dependientes.
Healthchecks:

Descubrí cómo implementar healthchecks en Docker Compose para asegurarse de que los servicios se inicien y operen correctamente. Esta es una práctica crucial para mantener la disponibilidad y la fiabilidad de las aplicaciones.
Redes en Docker:

Entendí cómo crear y utilizar redes personalizadas en Docker para permitir la comunicación entre contenedores, asegurando que los servicios puedan interactuar entre sí de manera efectiva y segura.
Problemas Solucionados y Lecciones Aprendidas
Problema de Archivo no Encontrado:

Inicialmente, enfrenté un problema donde Docker Compose no encontraba el archivo compose.yaml. Esto se debió a una confusión entre el archivo compose.yaml y docker-compose.yaml. Solucioné el problema renombrando y utilizando el archivo correcto (docker-compose.yaml), y asegurándome de estar en el directorio correcto.
Configuración Incorrecta de Healthchecks:

Tuve que investigar y ajustar los comandos de healthcheck para asegurarme de que los servicios se verificaran correctamente. Esto me enseñó la importancia de configurar correctamente los healthchecks para cada servicio.
Persistencia de Datos:

Al configurar los volúmenes, aprendí a mantener la persistencia de datos en los contenedores. Esto es fundamental para aplicaciones que requieren almacenamiento de datos a largo plazo.
Beneficios para mi Formación Profesional
Estos aprendizajes tienen un impacto significativo en mi formación profesional:

Habilidades de Orquestación: La capacidad de orquestar múltiples servicios utilizando Docker Compose es una habilidad valiosa que mejora mi capacidad para gestionar entornos de desarrollo y producción complejos.
Conocimiento Práctico: La experiencia práctica con configuraciones reales fortalece mi comprensión teórica y me prepara mejor para enfrentar desafíos en el mundo real.
Mejora en la Eficiencia: Estas habilidades me permitirán configurar y desplegar aplicaciones de manera más eficiente, reduciendo el tiempo de configuración y minimizando errores.
En conclusión, esta práctica ha sido altamente beneficiosa, incrementando significativamente mis competencias en la gestión de aplicaciones contenedorizadas y mejorando mis habilidades técnicas de manera integral.
