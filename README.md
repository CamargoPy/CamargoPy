Documentación de Nomenclatura para Repositorios y Puertos

1. Introducción
Esta documentación establece la estructura de nomenclatura utilizada para la organización de repositorios y la asignación de puertos en la infraestructura TI. 
Se detallan los prefijos, rangos y descripciones que permiten la categorización eficiente de aplicaciones y servicios.

2. Estructura de Nomenclatura

2.1 Prefijos y Rangos de Repositorios
Los repositorios se clasifican según su función y el tipo de implementación:

| Prefijo     | Rango    | Total Apps| Descripción                      |
|-------------|----------|-----------|----------------------------------|
| REPO-       | 011-024  | 14        | Seguridad                        |
| REPO-       | 025-029  | 5         | Proyectos base                   |
| REPO-       | 030-099  | 69        | Aplicaciones core                |
| REPO-       | 100-199  | 200       | Servicios                        |
| REPO-       | 200-249  | 50        | Otros servicios en la nube       |
| REPO-       | 250-300  | 251       | Tecnologías especializadas       |
| REPO-       | 300-454  | 55        | Infraestructura y soporte        |
| REPO-       | 455-599  | 45        | Pruebas y prototipos (POCs)      |

Esta estructura facilita la gestión clara y ordenada de los repositorios.

2.2 Asignación de Puertos
Cada capa tecnológica se asocia con un área o repo y una asignación específica de puertos:

| Capa       | Área/Repo            | Proyecto/Repo| Módulo | Rango  | Puerto       |
|------------|----------------------|--------------|--------|--------|--------------|
| ARTIFACT   | Almacenamiento       | 200          | 99     | 99     | 200-11099    |
| FRONT      | Core/Layout          | 200          | 98     | 98-91  | 200-11098    |
| FRONT      | Módulos Web          | 200          | 90     | 90     | 200-11090    |
| FRONT      | Otras tecnologías    | 200          | 89     | 89-51  | 200-11089    |
| APIGATEWAY | Integraciones        | 200          | 51     | 51-89  | 200-11051    |
| APIGATEWAY | Acceso externo       | 200          | 50     | 50     | 200-11050    |
| APIGATEWAY | Acceso interno       | 200          | 49     | 49-46  | 200-11049    |
| APIINTERNA | Core/Servicios       | 200          | 41     | 41-44  | 200-11041    |
| APIINTERNA | Módulos internos     | 200          | 40     | 40     | 200-11040    |
| APIINTERNA | Otras tecnologías    | 200          | 39     | 39-00  | 200-11039    |

3. Herramientas y Versiones

Las herramientas utilizadas en esta infraestructura incluyen:

- GitHub/GitLab: Gestión de repositorios y control de versiones.
- IIS: Publicación de aplicaciones.
- .NET 8: Desarrollo de aplicaciones backend.
- Angular 19: Desarrollo de interfaces frontend.
- PrimeNG: Biblioteca de componentes para Angular.

4. Información Adicional

👋 Hola, soy @CamargoPy

👀 Me interesa la programación con buenas practicas, el desarrollo backend y los microservicios.

🌱 Actualmente estoy aprendiendo prácticas avanzadas de DevOps y ciberseguridad.

💞️ Busco colaborar en aplicaciones web innovadoras y arquitecturas escalables.

📫 Puedes contactarme en: ccamargobr@hotmail.com

😄 Pronombres: Él/Él

⚡ Dato curioso: ¡Me encanta automatizar todo lo posible!

5. Conclusión

La estructura de nomenclatura de repositorios y puertos facilita la organización, administración y escalabilidad de los proyectos dentro de la infraestructura TI.
Seguir este esquema mejora la gestión de versiones, la interoperabilidad entre servicios y la eficiencia operativa.
