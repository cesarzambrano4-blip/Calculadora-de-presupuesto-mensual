<h1 align="center"> CALCULADORA DE PRESUPUESTO MENSUAL </h1>

La calculadora del presupuesto mensual es una aplicación con el propósito de ofrecer una herramienta práctica y confiable para la gestión de las finanzas personales. Permite registrar los ingresos y gastos de cada mes, calculando de forma automática el balance general del usuario. 

## Objetivos 
- Registrar y organizar los ingresos y gastos mensuales.
- Generar un balance claro y fácil de interpretar.
- Facilitar la exportación de reportes para análisis.
- Mejorar el control financiero personal del usuario

## Requerimientos funcionales 
| ID     | Descripción                                                                                   |
|--------|------------------------------------------------------------------------------------------------|
| RF-01  | El sistema permitirá ingresar ingresos mensuales.                                              |
| RF-02  | El sistema permitirá registrar gastos por categoría (vivienda, alimentación, transporte, ocio, otros). |
| RF-03  | El sistema mostrará un balance mensual (ingresos - gastos).                                    |
| RF-04  | El sistema permitirá exportar reportes en CSV.                                                 |

## Requerimientos no funcionales 
| ID     | Descripción                                                                                   |
|--------|------------------------------------------------------------------------------------------------|
| RF-01  | El sistema permitirá ingresar ingresos mensuales.                                              |
| RF-02  | El sistema permitirá registrar gastos por categoría (vivienda, alimentación, transporte, ocio, otros). |
| RF-03  | El sistema mostrará un balance mensual (ingresos - gastos).                                    |
| RF-04  | El sistema permitirá exportar reportes en CSV.                                                 |

## Tabla de pruebas 
| ID Prueba | Descripción de la prueba            | Pasos                                                     | Datos de prueba                 | Resultado esperado                 |
|-----------|--------------------------------------|------------------------------------------------------------|----------------------------------|------------------------------------|
| TC-001    | Registrar ingresos mensuales         | Abrir app → Ir a Ingresos → Ingresar                      | Monto: 1200                      | Se guarda y aparece en el resumen  |
| TC-002    | Registrar gasto por categoría        | Abrir Gastos → Elegir categoría → Ingresar monto → Guardar | Cat: Alimentación, 50           | El gasto aparece en listado        |
| TC-003    | Validar error con monto negativo     | Abrir Gastos → Ingresar monto negativo                     | -20                              | Mensaje de error mostrado          |
| TC-004    | Calcular balance mensual             | Registrar ingresos → Registrar gastos → Ver balance        | Ingreso: 1000, Gasto: 400        | Balance = 600                      |
| TC-005    | Exportar reporte CSV                 | Crear presupuesto → Exportar CSV                           | Datos generados                  | CSV exportado correctamente        |

##   Tipo de Mantenimiento Propuesto 
Se espera la realizacion de **mantenimiento correctivo** para solucionar errores que afecten el funcionamiento **mantenimiento preventino** para evitar fallos futuros y mantener el sistema estable y el **mantenimiento evolutivo** para agaregar mejoras y nuevas funciones segun las necesidades del usuario. Asi juntos permiten que el sistema sea confiable, seguro y pueda seguir creciendo.

## Refleccion sobre el control de versiones
El control de versiones en GitHub permite trabajar de forma ordenada, segura y colaborativa. Facilita llevar un historial claro de cambios, recuperar versiones anteriores y evitar la pérdida de información. Además, mejora el trabajo en equipo al permitir que varias personas aporten sin generar conflictos. En resumen, es una herramienta clave para desarrollar software de manera profesional y eficiente.

---

# Investigacion del uso de Markdown
 ## ¿Que es Markdown y por que se utiliza en proyectos de software?
 - Markdown es un lenguaje de marcado ligero que permite formatear texto plano de forma sencilla su diseño prioriza la legibilidad del texto, tanto en su forma de escritura como en la de lectura, y puede convertirse fácilmente a HTML y otros formatos, lo que lo hace ampliamente flexible.
 - Se utiliza en proyectos de software porque es fácil de leer, escribir y convierte el texto con formato a HTML, lo que lo hace ideal para documentación como archivos README.md, comentarios, blogs y portales de ayuda, ya que el código es más legible y fácil de mantener que el HTML.
 
## Una guía breve sobre cómo escribir en Markdown para documentar el proyecto.

## Elementos comunes

1. Encabezados: `#`, `##`, `###`
2. Listas:
- `- Palabra`
- `1. Palabra` 
3. Enlaces:
- [Texto del enlace] (https://www.ejemplo.com)
4. Imagen:!
- [Texto descriptivo](URL de la imagen)
- insertar simplemente arrastrando la imagen
5. Tablas:
- | Numero | Dato | Descripcion |
- |--------|------|-------------|
- | 1. | Uno | Primer numero |
- | 2. | Dos | Segundo numero |
- | 3. | Tres | Tercer numero |

## Ventajas de utilizar Markdown en combinación con GitHub

Usar Markdown junto con GitHub ofrece varias ventajas claras, como permitir crear documentación clara y legible sin herramientas complejas, se integra perfectamente con el control de versiones, facilita la colaboración porque los archivos son ligeros y fáciles de editar, y además GitHub los renderiza automáticamente, permitiendo visualizar tablas, listas y estilos de forma profesional.
