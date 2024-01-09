## gen_octree

Función para construir un modelo octree. 

<!-- panels:start -->

<!-- div:title-panel -->

### gen_octree(x_min, x_max, y_min, y_max, z_min, z_max, size)

<!-- div:left-panel -->

**Parameters:**

<!-- div:right-panel -->

**x_min :** *float*  
Límite Oeste del modelo a construir.

**x_max :** *float*  
Límite Este del modelo a construir.

**y_min :** *float*  
Límite Norte del modelo a construir.

**y_max :** *float*    
Límite Sur del modelo a construir.

**z_min :** *float*  
Límite de cota inferior del modelo a construir.

**z_max :** *float*  
Límite de cota superior del modelo a construir.

**size :** *float*  
Tamaño del bloque inicial.

<!-- div:left-panel -->

**Returns:**

<!-- div:right-panel -->

**Modelo octree**

<!-- panels:end -->

> Ver también

## Notas

## Ejemplo de uso

```
call 'octree.fis'
[x_min = 10]
[x_max = 20]
[y_min = 10]
[y_max = 20]
[z_min = 10]
[z_max = 20]
[size = 1]
[gen_octree(x_min, x_max, y_min, y_max, z_min, z_max, size)]
```