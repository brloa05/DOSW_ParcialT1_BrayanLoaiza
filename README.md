# DOSW_ParcialT1_BrayanLoaiza

### Punto6
## Epica 
# Permitir crear tipos de reservas considerando las reglas de cada tipo de recurso

## Historia de usario 
#  como usuario quiero crear reservas teniendo en cuenta las reglas para poder realizar mis actividades

## Tareas
# 1. realizar el diseño de este requerimiento teniendo en cuenta el patron
# 2. implentarla en el codigo 
# 3. verificar que no tenga errores
# 📄 Requerimientos del Sistema

## 1. Lista general de requerimientos

El sistema de Bankify tiene los siguientes requerimientos (descripción a alto nivel):

### 1.1 Requerimientos funcionales

El sistema de Bankify debe tener la capacidad de:

1. permitir que los salones solo puedan ser reservados por profesores
2. premitir acepta el correo si terminar en @mail.escuelaing.edu.co.
3.permitir que solo las oficinas puedan ser creadas por profesores.
4.Permitir Confirmar o denegar la reserva al usuario de acuerdo con las reglas de cada recurso.
5.Permitir crear tipos de reservas considerando las reglas de cada tipo de recurso. (Patron Factory Method)

### 1.2 Requerimientos funcionales

El sistema de Bankify debe tener:

1. colores alusivos al programa de Ingeniería de Sistemas
2.Debe ser responsive
3.Debe tener tipología legible
4.
5.

## 2. Diagramas de caso de uso

### 2.1 Requerimiento Funcional 1

| Campo | Descripción |
|------|-------------|
| **ID** | RF-01 |
| **Validacion de salones** | |
| **Descripción** | *El sistema debe permitir que los salones solo puedan ser reservados por profesore |
| **Precondiciones** | *Que el programa valide que es un profesor* |
| **Actor** | *profesor* |
| **Flujo principal** | 1. El actor …<br>2. El sistema …<br>3. El sistema … |
| **Diagrama de caso de uso** | *<img width="941" height="474" alt="image" src="https://github.com/user-attachments/assets/ebabeb43-58e8-4e8a-b979-dba79e3129ba" />
*|
| **Poscondiciones** | *Se espera como resultado que el profesor pueda reservar su salon* |


### 2.2 Requerimiento Funcional 2

| Campo | Descripción |
|------|-------------|
| **ID** | RF-02 |
| **validador Oficinas** | |
| **Descripción** | *El sistema debe permitir que solo las oficinas puedan ser creadas por profesores* |
| **Precondiciones** | *Para que el sistema cumpla con este requerimiento debe tener previamente un validador de que es un profesor* |
| **Actor** | *profesor* |
| **Flujo principal** | 1. El actor …<br>2. El sistema …<br>3. El sistema … |
| **Diagrama de caso de uso** | *<img width="705" height="360" alt="image" src="https://github.com/user-attachments/assets/8fb1522c-3bb9-4211-9035-2c6e5c692835" />
*|
| **Poscondiciones** | *Se espera como resultado que el profesor puedar reservar su oficina* |


### Punto1
## Diagrama de contexto

![alt text](image.png)

### Punto2 Patrones
## Factory Method
 # Creacional
 - En las misiones del sistema aparece que se pueden crear tipo
 de reservas considerando las reglas de cada tipo de recurso. Nosostros sabemos que este 
 patro me permite crear objetos teniendo en cuenta que todos son resursos, sin embargo 
 se comportan (reglas) de manera diferente.

 ## Builder 
# Creacional
 - Este patron se puede utilizar ya este nos permite crear objetos de manera
 flexible en el caso de crear la reserva el usuario tiene que ingresar muchos parametros, 
 builder nos puede servir mucho de ayuda para no tener constructores muy grandes.

### diagrama casos de 

<img width="705" height="360" alt="image" src="https://github.com/user-attachments/assets/0fc631fe-e7b2-47bc-a13f-27146023a2db" />


<img width="941" height="474" alt="image" src="https://github.com/user-attachments/assets/3cec76c3-66e8-4c80-9e99-c670c3dadcf3" />



### Punto3 requerimientos
## funcionales
 - permitir que los salones solo puedan ser reservados por profesores
 - premitir  acepta el correo si terminar en @mail.escuelaing.edu.co.
 - permitir que solo las oficinas puedan ser creadas por profesores.
 - Permitir Confirmar o denegar la reserva al usuario de acuerdo con las reglas de
cada recurso.
 -  Permitir crear tipos de reservas considerando las reglas de cada tipo de
recurso. (Patron Factory Method)

## No funcionales
- colores alusivos al programa de
Ingeniería de Sistemas

- Debe ser  responsive

- Debe tener  tipología legible 
