<h1 align="center"> Sistema de Gestión de Inventario </h1>

## 📁 Acceso y ejecución del proyecto

1. Descarga Python [aquí](https://www.python.org/downloads/).

Da click en el sistema operativo de tu computador y descarga el _Latest release_, luego simplemente sigue el paso a paso del descargable.

![imagen](https://github.com/user-attachments/assets/d037aaff-2adb-42f1-a512-a118adf4a04a)
![imagen](https://github.com/user-attachments/assets/5c802e84-cee0-4a81-81ed-725cc447a58c)

2. Descargamos el archivo `.py`.

![imagen](https://github.com/user-attachments/assets/9def2f5c-4b6b-4807-91c4-94fa3a9c1ad3)![imagen](https://github.com/user-attachments/assets/2cd09504-db58-4c61-a223-0f3944139117)



3. Abrimos la terminal del computador.

![imagen](https://github.com/user-attachments/assets/8d36087b-131e-4bc6-a256-1edd8274637e)

4. Búscamos la carpeta en la que descargamos el archivo `.py`.
- Usa `ls` para visualizar los archivos y carpetas que se encuentran donde estas situado.
- Usa `cd` para ingresar a la carpeta que necesites.

En este caso está dentro de la carpeta Prueba, que está dentro de la carpeta Examen:
5. Luego ejecutamos el proyecto usando `python3` y el nombre del ejecutable, como se muestra a continuación:

![imagen](https://github.com/user-attachments/assets/62723ac4-51da-4e84-8f62-e9ee9706074b)


## :hammer: Funcionalidades del proyecto

- `Funcionalidad 1: Añadir productos`: 

Se prodrán añadir productos incluyendo nombre, precio y cantidad en cada uno, el precio debe ser un número positivo, mayor a cero , y la cantidad debe ser un numero entero mayor o igual a 0; si el producto ya existe, saldrá un error y volverá a pedir la información del nuevo producto, el usuario cuenta con tres intentos para ingresar la información correctamente, si pasan los 3 intentos, sale un error y volverá al menú principal.

![imagen](https://github.com/user-attachments/assets/746ca541-b429-4c82-ba4e-d929db50d5fd)


- `Funcionalidad 2: Consultar productos`: 

Se podrá consultar si el producto ya existe en el inventario ingresando el nombre, en caso de estar en el inventario se mostrará en pantalla el nombre, precio y cantidad de ese producto, en caso de no estar saldrá un error y volverá al menú principal.

![imagen](https://github.com/user-attachments/assets/4ee9981b-e6bd-4164-806b-611a83957198)


- `Funcionalidad 3: Actualizar productos`:

Se puede actualizar un producto ingresando el nombre, si el producto existe en el inventario se pedirá el precio actualizado y la cantidad actual de producto; si el producto no existe, saldrá un error y volverá al menú principal, el precio y la cantidad que se ingrese debe cumplir con los mismos criterios que en la `funcionalidad 1`.

![imagen](https://github.com/user-attachments/assets/e752a1e2-1630-431a-9717-507b0711307d)


- `Funcionalidad 4: Actualizar cantidad`:

Se puede actualizar un producto ingresando el nombre, si el producto existe en el inventario se pedirá la cantidad actualizado y la cantidad actual de producto; si el producto no existe, saldrá un error y volverá al menú principal, el precio y la cantidad que se ingrese debe cumplir con los mismos criterios que en la `funcionalidad 1`.

![imagen](https://github.com/user-attachments/assets/8a4cb5b5-d738-43cf-8ad7-b9a4598473af)


- `Funcionalidad 5: Eliminar producto`:
 
Se podrán eliminar los productos ingresando el nombre, si el producto no está en el inventario, mostrará un error y volverá al menú principal, en caso de si estar pero la cantidad que queda de este producto es mayor a 0 entonces este no se podrá eliminar pues es necesario que este producto ya no esté disponible para que sea eliminado, de lo contrario, se eliminará satisfactoriamente.

![imagen](https://github.com/user-attachments/assets/d63bbdb3-1b19-4854-91fe-5f9cbd44013b)


- `Funcionalidad 6: Calcular el valor total`:

Esta funcionalidad mostrará en pantalla el valor total del inventario (la sumatoria de la multiplicación de el precio por la cantidad de cada uno de los productos)

![imagen](https://github.com/user-attachments/assets/6feffdb7-9d3c-4be3-b0af-d244aa9d606f)


- `Funcionalidad 0: Salir`: 

Esta es la única manera de salir del sistema, si selecciona otra opción o ingresa una opción invalida simplemente le seguirá mostrando el menú una y otra vez.

![imagen](https://github.com/user-attachments/assets/2ce973f1-dffa-458a-8c84-6ca8d1d7c07f)

