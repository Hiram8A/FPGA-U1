

## Examen U1 a
***
### Sistemas Embebidos
***
#### IEEE
- Diseñado para realizar una o muy pocas funciones (dedicadas o especificas)
- RTOS (En tiempo real)
- Está embebido "enfrascado, dentro"  en un sistema  (Normalmente incluye Hardware Adicional y partes Mecánicas)

#### General
- Sistema electrónico parte de un sistema más grande


### Diferencias
- **RTOS**
- **Diseñado para una o pocas funciones especificas**


***
### Herramientas (Dispositivos) de procesamiento que se utilizan en sistemas embebidos
- Microcontrolador
- CPLD
- FPGA

* * *

### Principal ventaja de diseñar y desarrollar sistemas digitales usando Circuitos Integrados por Software

Son más baratos y requieren menor tiempo de implementación
(Sistemas complejo en tiempo corto).

* * *
### Un Microprocesador es un Circuito Integrado Reconfigurable por Software

**Falso**
 * * *
### Estructura General de los sPLD

![Diagrama](https://raw.githubusercontent.com/Hiram8A/VHDL---Estudio/main/Estructura_Gen_sPLD.png)

### Método tradicional de diseño en Sistemas Digitales utiliza Circuitos Integrados de...

**Función Fija**

### ¿Por que los sPLD existe un Plan o (Matriz) de Compuertas AND y un Plano (Matriz) de Compuertas OR?

Debido a que su funcionamiento es la sumatoria de términos producto.

### Nombre de 3 Circuitos Integrados Reconfigurables por Software

- PROM / EPROM / EEPROM
- GAL
- FPGA
***




***
## Examen U1 b
***
### Nombre de 2 Componentes PRINCIPALES de un SoC, de acuerdo a la definición de SoC vista en clase

FPGA y Microprocesador
***
### De manera natural, los FPGA realizan el procesamiento de forma

Paralela
***
### La sigla FPGA se refiere a la expresión en ingles "Field Programmable Gate Array" significa que:

El FPGA esta diseñado para ser configurado después de que el chip fue manufacturado
***
### Escriba en español el nombre del elemento fundamental de los Bloques Configurables de los FPGA

Tablas de búsqueda
***
### La estructura general de los FPGA está compuesto de 3 Bloques. Escriba el nombre en español de estos 3 Bloques básicos.

- Bloques Lógicos
- Bloques de Entrada / Salida
- Bloques de Interconexión 
***
### Dada la forma natural en que realizan el procesamiento, los microcontroladores tienen una respuesta más rápida que los FPGA
- **Falso**
***
### Que es un SoC?

Circuito Integrado
***
### CPLD significa "PLD Complejo", donde "Complejo" es porque:

Integra varios Bloques Lógicos parecidos a PAL/GAL
***
### Como se implementan las funciones lógicas en los FPGA.

Mapeando la función en las tablas de búsqueda.

***
### Un componente de un FPGA tipo SRAM es:

**LUTs**

_The LUT is the basic building block of an FPGA and is capable of implementing any logic function of N Boolean variables._
****
### La PRINCIPAL Ventaja de los CPLD's  (Respuesta en 1 sola palabra)

**Velocidad**

***
### Un microprocesador es un circuito integrado reconfigurable

**Falso**
***
### Los FPGA tienen mayo retardo en su respuesta que los CPLD

**Verdadero**
***
### Los FPGA tipo SRAM son No-Volátiles

**Falso**
***
### Un Algoritmo solo se puede implementar por Software

**Falso**
***

## NOTAS

### sPLD
El principio de funcionamiento es la sumatoria de términos productos (Con matrices AND OR)

### GAL 
AND reconfigurable

* * * 
### PROM
OR reconfigurable

* * * 

### Principio funcionamientos de los FPGA

Mapear las funciones logicas en las tablas de busqueda

### Tabla de busqueda

- Celdas Binarias (Estan en la tabla de busqueda)
- MUX
- Flips Flops (F/Fs)

