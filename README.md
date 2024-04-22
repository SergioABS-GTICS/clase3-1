# clase3-1

## CASO COMPILADOR

![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/080c4c58-cd61-4e8e-8677-06afbf753657)

## Query Methods (Paso Previo)

En el repository, hacemos los Query y los implementamos mediante métodos, luego instanciamos el repositorio en el mismo Controller para poder usar los métodos.

![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/a7dcfbda-03c8-4203-a18a-fac7dc882e27)

**Instanciar Repository en el Controller (ya antes visto)**

![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/65f42949-60fb-445b-8f10-813205af5e27)

**Usar los Métodos en el Controller**

![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/2d61f753-45cf-4986-9e2f-fd5b066128af)

**NO USAR ; EN LOS @QUERY DE LOS REPOSITORIOSSSSSSSSSSSSSSSSSSSSSSSSS**

## Query Methods (Paso Aplicación)

**SELECT**

**SELECT NORMAL**

1) Realizar los Query en el repositorio:
   
![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/f82ed572-9d40-45b5-abef-50c46c8429f3)

2) Aplicar los métodos en el Controller mediante los RequestParam 

![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/248110cb-b6e1-4d8d-8599-52058042bc3f)

3) Mandar la data a las vistas:
   
![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/0da0eb1c-038f-4483-b7c7-84bb4c2a7f70)

**SELECT CON TIEMPO**

Función Now() en Query:

![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/e3784eeb-e383-4254-bc12-2af2d32c6b02)


**UPDATE**

1) Creamos método que busque por id a la mascota EN SU REPOSITORIO 

2) Aplicamos el método en el controller usandolo con el id que recepcionamos y mandamos el objeto: RECORDAR USAR EL OPTIONAL, luego mandamos a la vista forms por GET


![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/cedfb5cd-e293-4d09-b8b7-b3e81af4cc32)

   
![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/b0147219-a172-4491-b6a5-bf8db6737d5b)

3) Hacemos la vista Forms y mandamos por POST el objeto
   
![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/18cbc7d5-ea5a-4190-8036-2f935d49f83f)

5) Por PostMapping recepcionamos el objeto y lo actualizamos creando el método de UPDATE
   
![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/83bb99db-8232-4089-8ada-1e1dbfd99a69)


![image](https://github.com/SergioABS-GTICS/clase3-1/assets/154263057/2045d0d3-3c41-435f-bc3f-9792796f8407)





