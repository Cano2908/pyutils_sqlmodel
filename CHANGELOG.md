# Changelog

## [0.1.0] - 2025-01-06
### Added
- Implementación inicial del paquete `pyutils_sqlmodel`.
- Soporte para conexión a bases de datos PostgreSQL con `postgres_connection.py`.
- Modelo base para repositorios con `model_repository.py`.


## [0.2.0] - 2025-01-06
### Added
- Implementacion a conexion a diferentes db como SQLite y MySQL
- Uso de nueva variable de entorno SGDB que tendra el  valor de postgres, mysql o sqlite

# [0.2.1] - 2025-01-11
## FIX
- Conexion a Sqlite corregida y logs desactivados a la hora de usar el get_engine

# [0.2.2] - 2025-01-18
## FIX 
- Modificacion para tener create_all sin configurar algo de sqlmodel
- Variables para ver los logs o no

# [0.2.4] - 2025-01-27
## FIX
- Option de pasar URL completa para conectarse a una db en la nube