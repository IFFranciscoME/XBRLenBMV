# XBRLenBMV
Ingeniería Financiera utilizando el protocolo e**X**tensible **B**usiness **R**eporting **L**anguage en la Bolsa Mexicana de Valores. **BMV**

### Introducción

Según el documento oficial de la Bolsa Mexicana de Valores (BMV), que se puede consultar , en febrero del 2010 además de resolver temas referentes a la adopción de las Normas de Información Financiera NIIF o International Financial Rules Standard (IFRS), también se planeó el análisis y planeación para la implementación en las empresas que cotizan en BMV del protocolo XBRL. Éste último es básicamente un lenguaje o protocolo de almacenamiento y ordenamiento de información financiera basado en  XML para  la  comunicación  electrónica de la misma. Esto tiene la finalidad principal de estandarizar el formato con el que la información financiera se distribuye entre los diferentes proveedores y consumidores. XBRL es un estándar abierto y este es desarrollado por XBRL Internacional (integrado por 480 compañias y organizaciones gubernamentales de 37 paises).

Low elementos del protocolo XBRL son : 1.- **Taxonomía** y 2.- **Documento de instancia**

### 1- Taxonomía

Según la **(RAE)**, taxonomía es la ciencia que trata de los principios, métodos y fines de la clasificación. Acorde con el protocolo **XBRL**, el término se utiliza en el mismo sentido, se refiere como la  descripción y clasificación de los conceptos de un reporte financiero. En otras palabras, la parte de la taxonomía que se define en un protocolo XBRL solamente incluye la descripción y clasificación de conceptos, no incluye valores de ningún de estos. Por esta razón se establece que la taxonomía básicamente sirve a dos propósitos principales y claros: 1) definir conceptos o elementos en los estados financieros a través de atributos básicos y definir relaciones entre estos a través de los atributos de relación.

### 2.- Documento de instancia

Documento con datos que está hecho con base en los elementos de una taxonomía, el cual contiene:

- **Hechos** financieros y no financieros: Cuentas contables y notas
- **Valores** de los hechos reportados: Importe correspondiente a cada cuenta.
- **Contexto** en el que se reportan los hechos: Periodos, entidad que reporta, si es dictaminado.
- **Unidad** La unidad en la que se reportan los **Hechos**

De tal manera que: Elementos de la Taxonomia + Datos financieros de la compañía = INSTANCIA

En el mes de Diciembre de 2014, la BMV publicó en su página de internet, la nueva extensión de la taxonomía Mexicana, además que estableció que *"...A partir del primer trimestre de 2016, será obligatorio que las emisoras que reportan bajo IFRS envíen su archivo XBRL con la nueva taxonomía a la BMV y CNBV"*



