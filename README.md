<h1 align="center">
  <img src="https://github.com/hachemartin/it-academy-hachemartin/blob/master/img/itacademylogo.png" alt="IT Academy logo" width=200">
  <br>
    <br>Proyecto Web App Programación Cibernarium <br/>
</h1>

**Cliente:** [Cibernarium](https://cibernarium.barcelonactiva.cat) / [IT Academy](https://cibernarium.barcelonactiva.cat/es/it-academy) <br/>
**Fecha de inicio:** 29/11/2018 <br/>

<br>

## Tabla de contenido <br/>

[**Descripción**](#descripción) <br/>
[**Proceso de trabajo**](#proceso-de-trabajo)
  * [**1. Espacios físicos de formación del Cibernarium**](#1-espacios-físicos-de-formación-del-cibernarium) <br/>
  * [**2. Actividades de formación**](#2-actividades-de-formación) <br/>
  * [**3. Proveeedores**](#3-proveeedores) <br/>
  * [**4. Estado de la situación**](#4-estado-de-la-situación) <br/>
  * [**5. ¿Qué se nos pide?**](#5-qué-se-nos-pide) <br/>

<br>
<br>

## **Descripción**<br/>

El [Cibernàrium](https://cibernarium.barcelonactiva.cat) es el programa de capacitación y divulgación tecnológica de [Barcelona Activa](https://www.barcelonactiva.cat) - [Ajuntament de Barcelona](https://ajuntament.barcelona.cat). Ofrece formación para profesionales y empresas, así como actividades de iniciación a Internet para toda la ciudadanía.

Esther Farre e Iván, encargados de la organización de las capsulas de formación acuden a nosotros para solicitarnos una herramienta que facilite la administración de los recursos, ya que en la actualidad se lleva de manera precaria lo que dificulta el manejo óptimo de la información. 

<br>

## **Proceso de trabajo**<br/>

Las características que tiene el proceso que lleva Esther son las siguientes:

### **1. Espacios físicos de formación del Cibernarium**<br/>
  El espacio determinado para el desarrollo de los cursos cuenta  con siete (7) aulas en total con las    siguientes características:
* 5 aulas cuentan con permisos totalmente restringidos para instalar o modificar cualquier tipo de software. 
* 2 aulas de  estas 5, a pesar de contar con permisos restringidos, cuentan con máquinas virtuales específicas.
* Cada Aula tiene un horario asignado. 
* Cada aula tiene la capacidad de recibir 20 alumnos. 

<br>

### **2. Actividades de formación**<br/>

  El Cibernarium ofrece 160 actividades diferentes, en una programación trimestral. Las características de los cursos o actividades son las siguientes:
* Cada actividad tiene un número ID fijo, que le identifica en el sistema.
* Existen actividades que duran solo 3 horas, por lo cual se realizan en un solo día. 
* Existen actividades que duran entre 4 horas y 16 horas, por lo cual se programan a un máximo de 15 días para su ejecución. 
* Las actividades pueden repetirse X veces trimestralmente (Cada 15 días, una vez al mes, una o dos veces por semestre, etc)
* Cada actividad puede tener restricciones específicas.
* Las actividades se progrman generalmente en las siguientes franjas:
  Mañana   9:00    / 9:30  / 10:00 
  Tarde       16:00 / 16:30 / 17:00
  Noche      21:00 (Este horario es esporádico. Solo si se solicita)

<br>

### **3. Proveeedores**<br/>
  El Cibernarium cuenta con dos tipos de proveedores para ejecutar las actividades de formación programadas. 
* Los proveedores fijos, son aquellos que cuentan con una disponibilidad completa, dentro de su horario laboral y por lo general no cambian. 
* Por otro lado, existen proveedores licitantes, que son aquellos que exponen cuál es su disponibilidad horaria, antes de iniciar cada trimestre. Estos pueden cambiar cada trimestre, en razón de ganar la licitación o no.  

<br>

### **4. Estado de la situación**<br/>

En la actualidad Esther e  Iván llevan la programación de estos recursos en un documento Excel, donde organizan la distribución de las aulas, los códigos de cada cursos, las personas inscritas, las personas que han cancelado, la programación de los proveedores, las horas que estos han trabajado y el calculo de cuánto se les ha de pagar al final de cada mes, con respecto a las horas trabajadas. 

La información básica como aulas y cursos, es estática dentro del formato Excel ya que no cambia constantemente. Según explicación dada por Esther, se valen de formulas para cotejar la información contenida en el cuadro, para luego de manera manual, ir completando las columnas con la información faltante. 

El sistema del Cibernarium, arroja una base de datos con los inscritos a cada uno de los cursos. Las cancelaciones se hacen generalmente de manera manual, por el personal administrativo encargado. 

Los proveedores deben pasar dos días antes de iniciar el trimestre un documento Word, (que no está estandarizado), donde muestran cuáles son sus horas y espacios libres. Esto hace que se tenga que organizar el horario e tiempo record. 

Cada proveedor tiene un número específico  de horas a ejecutar por día y debe distribuirlas en la mañana y en la tarde.  En pocas excepciones se permite que un proveedor solo trabaje una jornada única de mañana o tarde. 

Cuando un instructor no puede trabajar en las horas programadas, inicialmente se reprograman para reemplazar las horas perdidas. Si al final de mes no se trabajan y no se pueden reemplazar. 

<br>

### **5. ¿Qué se nos pide?**<br/>

Por medio de una web app, gestionar todo lo anteriormente descrito, teniendo en cuenta estos requerimientos: 

1.	App o web App de fácil manejo. 
2.	Que la solución sea accesible para todos los involucrados en el proceso(administrativos, directivos, proveedores). 
3.	Que la solución tenga roles determinados con permisos para cada uno de los usuarios. (Ejemplo: administrador pueda modificar y reorganizar/ proveedores puedan  incluir información y consultar, etc) 
4.	Que se pueda obtener, como lo hacen del formato Excel, un informe con las horas trabajadas por cada proveedor. 
