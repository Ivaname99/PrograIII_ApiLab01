## API de Productos


Este proyecto es una API desarrollada con ASP.NET Core Web API, cuyo objetivo es realizar peticiones a una base de datos SQL Server sobre una tabla llamada Productos.


#### Configurar la Cadena de Conexión

En el archivo appsettings.json, dentro del apartado ConnectionStrings, actualice la instancia del servidor SQL Server Express con su propia instancia.

```csharp
"ConnectionStrings": {
    "DefaultConnection": "Data Source=DESKTOP-P9OK1JK\\SQLEXPRESS;Initial Catalog=PrograIII_ApiLab01;Integrated Security=True;Trust Server Certificate=True"
}
```

#### Actualizar Base de Datos

Crear la base de datos llendo a la consola de administrador de paquetes NuGet ejecutando:
```
update-database
```

###### Datos de prueba para ingresar
Datos a ingresar para probar en sql server
```sql
INSERT INTO Productos (Nombre, Precio, Stock) VALUES
('Laptop Gamer ASUS ROG', 1899.99, 15),
('Teclado Mecánico HyperX Alloy', 89.50, 30),
('Monitor Samsung 27" 144Hz', 299.99, 20),
('Mouse Logitech G502', 49.99, 50),
('Disco Duro Externo 1TB WD', 79.99, 25),
('Memoria RAM Corsair 16GB DDR4', 99.99, 40),
('Tarjeta Gráfica NVIDIA RTX 4070', 649.99, 10),
('Fuente de Poder EVGA 750W', 120.75, 18),
('Silla Gamer Cougar Armor One', 199.99, 12),
('SSD NVMe 1TB Kingston', 129.99, 35)
```

###### Nota para el ingeniero
Este proyecto no tiene commits debido a que hice el proyecto en otro repositorio, pero decidi pasarlo a un repositorio propio para el proyecto. Aquí esta el repositorio por si quiere verificar.

Proyecto: https://github.com/Ivaname99/ProjectRepository_PrograIII
