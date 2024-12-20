Servidor en Deno que interactúa con MongoDB para gestionar datos de niños y ubicaciones en un contexto navideño. Permite:  

- **Crear y gestionar ubicaciones**: Registrar ubicaciones con nombre y coordenadas, asegurando unicidad.  
- **Registrar niños**: Almacenar niños con nombre, comportamiento ("bueno" o "malo") y ubicación asociada. Incrementa automáticamente el contador de niños buenos en la ubicación correspondiente.  
- **Consultar datos**: 
  - Listar niños según su comportamiento.  
  - Ordenar ubicaciones por la cantidad de niños buenos.  
  - Calcular la distancia total entre ubicaciones usando la fórmula de Haversine.  
- **Gestión robusta**: Valida datos, previene duplicados y maneja errores comunes.  

Incluye un servidor REST que escucha en el puerto 6768 para procesar las solicitudes.
