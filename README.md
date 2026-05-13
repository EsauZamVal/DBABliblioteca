# DBABblioteca
 
Sistema de gestión bibliotecaria de escritorio desarrollado en C# con Windows Forms y SQL Server. Permite administrar préstamos, cobros de adeudos y autenticación de usuarios mediante código de verificación.
 
## Funcionalidades
 
- Registro y gestión de alumnos (nombre, número de control, departamento, semestre, contacto, correo)
- Control de préstamos y devoluciones
- Módulo de cobro de adeudos
- Autenticación mediante código de verificación antes de operaciones críticas
- Validación de duplicados por número de control
## Stack
 
| Capa | Tecnología |
|---|---|
| Frontend | Windows Forms (.NET) |
| Backend | C# |
| Base de datos | SQL Server |
| ORM / Acceso a datos | ADO.NET (SqlClient) |
| IDE | Visual Studio |
 
## Estructura del proyecto
 
```
DBABblioteca/
├── Bblioteca/          # Proyecto principal (Forms, lógica)
├── packages/           # Dependencias NuGet
├── Bblioteca.sln       # Solución de Visual Studio
└── .gitignore
```
 
