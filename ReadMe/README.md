# Ejemplos de Web APIs
Ejercicios tomados del curso de **Felipe Gavilán: Construyendo Web APIs RESTful con ASP.NET Core**, y complementado con apuntes propios.

# Índice completo de contenidos 📋
2. **[Configurando el ambiente](#Tema_02_Ambiente)**
	1. Introducción a ASP.NET Core
	2. Instalando Visual Studio
	3. Instalando Visual Studio Code
	4. Instalando .NET 6
	5. Creando el Web API con VS
	6. Creando el Web API con VS Code
	7. Corriendo el Web API con VS
	8. Corriendo el Web API con VS Code
	9. Creando la clase startup
	10. Desactivando los Tipos de Referencia no Nulos
3. **[Nuestro primer API](#Tema_03_Primer_API)**	
	1. Introducción
	2. Iniciando el Desarrollo del Web API
	3. Instalando Entity Framework Core
	4. Leyendo y Creando Recursos desde el Controlador
	5. Actualizando y Borrando Recursos
	6. Data Relacionada - Segundo Controlador
4. **[Fundamentos ASP Net Core y Web API](#Tema_04_Fundamentos)**
	1. Controladores y Acciones
	2. Reglas de Ruteo
	3. Variables de Ruta
	4. Tipos de Datos de Retorno
	5. Programación Asíncrona
	6. Haciendo Asíncronos los Métodos del Controlador
	7. Introducción al Model Binding
	8. Validaciones por Defecto
	9. Validaciones Personalizadas por Atributo
	10. Validaciones por Modelo
	11. Validando desde el Controlador - Validando Contra la BD
	12. Inyección de Dependencias y Acoplamiento
	13. Servicios en ASP.NET Core
	14. Ejemplo de Tiempo de Vida de los Servicios
	15. Loggers
	16. Introducción al Middleware
	17. Ejemplos de Middleware
	18. Colocando el Middleware en su Propia Clase
	19. Introducción a los Filtros
	20. Filtros Personalizados y Globales
	21. Ejecutar Código Recurrente con IHostedService
5. **[Manipulando recursos](#Tema_05_Recursos)**
	1. Limpiando el Proyecto
	2. Repaso de Cómo Configurar EF Core
	3. Repaso de Cómo Insertar Registros en la Base de Datos
	4. DTOs y Automapper
	5. Leyendo Registros con EF Core
	6. Entidad Libro
	7. Relación Uno a Muchos
	8. Controlador de un Recurso Dependiente
	9. Utilizando Include
	10. Relación Muchos a Muchos
	11. Insertando Datos en una Relación Muchos a Muchos
	12. Usando Include y ThenInclude
	13. Corrigiendo el Null - Herencia
	14. Creando Recursos con POST (retornando 201 ```CreatedAtRoute```)
	15. Actualizacion Completa de Recursos con PUT (retornando 204 ```NoContent```)
	16. Actualizando Libros y sus Autores
	17. HTTP Patch y JSON Patch: introducción
    18. HTTP Patch y JSON Patch: actualizando Solo Algunos Campos con HTTP PATCH (uso de ```JsonPatchDocument```)
	19. Borrando Recursos
6. **[Configuraciones](#Tema_06_Configuraciones)**
	1. Introducción a las Configuraciones
	2. Ejemplo de IConfiguration
	3. Usando el AppSettings
	4. Variables de Ambiente
	5. Orden de Declaración de los Proveedores de Configuración
	6. User Secrets
	7. Línea de Comandos
	8. Consideraciones de Seguridad
7. **[Configuraciones](#Tema_07_Seguridad)**
	1. Autenticación y Autorización
	2. Configurando Identity
	3. Funcionalidad de Registro de Usuarios
	4. Login - Partes del JSON Web Token (JWT)
	5. Configurando Swagger Para Que Envíe el JWT
	6. AllowAnonymous
	7. Relación Entre Usuarios y Comentarios
	8. Authorize y Claims
	9. Renovando el Token
	10. Configurando la Autorización Basada en Claims
	11. Agregando Claims a un Usuario
	12. Deslogueo
	13. Introducción a CORS
	14. Configurando CORS en ASP.NET Core
	15. Entendiendo la Encriptación
	16. Encriptación en ASP.NET Core
	17. Llaves de Protección de Datos
	18. Entendiendo Hashing
	19. Hashes en ASP.NET Core
	20. HTTPS
8. **[Escenarios avanzados](#Tema_08_Escenarios_Avanzados)**
	1. Introducción
	2. Introducción a HATEOAS
	3. Implementando HATEOAS
	4. Agregando Rutas - IAuthorizationService
	5. Enlaces de HATEOAS en un DTO
	6. Enlaces de HATEOAS en un Listado
	7. Excluir HATEOAS con un Query String
	8. HATEOAS y Filtros (Parte 1)
	9. HATEOAS y Filtros (Parte 2)
	10. Filtro de HATEOAS para un Listado
	11. Removiendo el Parámetro Innecesario - IOperationFilter
	12. Introducción al Versionamiento
	13. Versionando con URL
	14. Configurando Swagger para que Maneje Versiones
	15. Versionando con la Cabecera
	16. Agregando Información Extra a Swagger
	17. Paginación
9. **[Escenarios avanzados](#Tema_09_Pruebas_Automaticas)**
	1. ¿Qué es una Prueba?
	2. Pruebas Automáticas
	3. Nuestra Primera Prueba Unitaria
	4. Agregando Más Pruebas Unitarias
	5. Mocks para Suplantar Dependencias
	6. Librería Moq
	7. Probando EF Core
	8. Pruebas de Integración
10. **[Despliegues](#Tema_10_Despliegues)**
	1. Publicando el Web API en Azure usando Visual Studio
	2. Publicando el Web API en Azure usando VS Code
	3. Utilizando Application Insights para ver Errores en Producción
	4. Publicando el Web API en IIS
	5. Despliegues Automáticos
	6. Subiendo el Código a Github
	7. Integración Continua
	8. Entrega Continua
11. **[Proyecto final](#Tema_11_Proyecto_Final)**
	1. Introducción a Postman
	2. Esquema de las Entidades del Proyecto
	3. Creando el Proyecto
	4. Configurando EF Core
	5. Creando el Controlador de Géneros de Películas
	6. Entidad Actor
	7. Subiendo una Imagen al Web API
	8. Validando Imágenes
	9. Subiendo Imágenes hacia Azure Storage
	10. Subiendo Imágenes hacia Azure Storage (Parte 2)
	11. Subiendo Imágenes hacia el wwwroot (alternativa a Azure Storage)
	12. HTTP Patch
	13. Paginación
	14. Entidad Película
	15. Relaciones Muchos a Muchos
	16. Model Binder Personalizado
	17. Filtrando Películas
	19. Data Relacionada
	19. Order By
	20. CustomBaseController
	21. Entidad Sala de Cine - CRUD
	22. Configurando NetTopologySuite
	23. Queries Espaciales
	24. Sistema de Usuarios
	25. Entidad Reviews - Relación con Usuarios
	26. Pruebas Unitarias - Proveedor En Memoria de EF Core
	27. Controlador de Géneros - Pruebas Unitarias
	28. Controlador de Actores - Pruebas Unitarias
	29. Controlador de Películas - Pruebas Unitarias
	30. Controlador de Cuentas - Pruebas Unitarias
	31. Controlador de Cines - Pruebas Unitarias
	32. Controlador de Reviews - Pruebas Unitarias
	33. Métodos Auxiliares - Pruebas de Integración
	34. Controlador de Géneros - Pruebas de Integración
	35. Controlador de Reviews - Pruebas de Integración
	36. Publicando el Proyecto en un Azure App Service - Application Insights	
---

# Migraciones de base de datos? 🔩 <a name="Migraciones"></a>
* Practicamente todos los proyectos acceden a la base de datos, por lo que hay que:
  * Ejecutar la siquiente sentencia en el **Package Manager Console** (cuidado con el proyecto de inicio en la consola), la cual ejecutará todas las migraciones:
    * ```Update-Database```
  * La conexión se encuentra en el archivo ```appsettings.Development.json```.
